# Introduction server-side-ui-starter
server-side-ui-starter provides you an out-of-the-box application setup to fast start development of a Web Application based
on a service side rendering architecture.

It is leveraging Spring Boot as a technology stack, which provides:
- a way to implement Model, View and Controller(s) using Spring Web annotations and Thymeleaf template engine
- an Inversion of Control Container to wire together your classes at running without the need to write tightly-coupled code
- an integrated Web Server, so no need to deploy the built artifact to a separate running web or application server

The application contains example code to have a first public page. This page is built using 
Thymeleaf and WebJars, so that common web libraries are available without the need to copy and paste them in the `resources/static` folder.

It provides a way to test the controller logic.

## Prerequisites
In order to further develop this application the following tools needs to be setup:
- Java Development Kit (https://bell-sw.com/)
- Visual Studio Code or IntelliJ IDEA as Integrated Development Environment (IDE)
- Tanzu Developer Tools plugin for the mentioned IDE

# Local
## Build
In order to compile the production code:
```bash
./mvnw clean compile
```


After that it is a good habit to compile the test classes and execute those tests to see if your application is still behaving as you would expect:
```bash
./mvnw verify
```


## Start and interact
Spring Boot has its own integrated Web Server (Apache Tomcat (https://tomcat.apache.org/)).

Launch application using default profile:
```bash
./mvnw spring-boot:run
```


### Accessing home page

You can access the public page at `http://localhost:8080/` by a web browser or using `curl`:

```bash
curl -X GET -H 'Content-Type: application/html' http://localhost:8080/
```

# Deployment
## Tanzu Application Platform (TAP)
Using the `config/workload.yaml` it is possible to build, test and deploy this application onto a
Kubernetes cluster that is provisioned with Tanzu Application Platform (https://tanzu.vmware.com/application-platform).

> The workload is set up by default to autoconfigure the actuators. This results in that the Spring Actuators are available at TCP port 8081 and will be used by Application Live View.
> Application Live View allows you see all health metrics in the TAP GUI. If you would like to have the Actuators available at TCP port 8080 you can set the
> annotation `apps.tanzu.vmware.com/auto-configure-actuators` to `false`.

### Tanzu CLI
Using the Tanzu CLI one could apply the workload using the local sources:
```bash
tanzu apps workload apply \
  --file config/workload.yaml \
  --namespace <namespace> \
  --local-path . \
  --yes \
  --tail
````

> Change the namespace to where you would like to deploy this workload.

### Visual Studio Code Tanzu Plugin
When developing locally but would like to deploy the local code to the cluster, the Tanzu Plugin could help.
By using `Tanzu: Apply` on the `workload.yaml` it will create the Workload resource with the local source (pushed to an image registry) as
starting point.

# How to proceed from here?
Having the application locally running and deployed to a cluster you could add your domain logic, related persistence and new Spring MVC controllers.

Some tips:
- You can add images, additional CSS, etc to `src/main/resources/static` folder. It will be served by Spring Boot under `/static`. Those resources can be referenced to by Thymeleaf `@` character.
- In order to add a new page, create a new Controller, method and .html file in `src/main/resource/template` folder.

# References
- [Spring Boot](https://spring.io/projects/spring-boot/)
- [Spring Web MVC](https://docs.spring.io/spring-framework/docs/current/reference/html/web.html#spring-web)
- [Tanzu Application Platform](https://tanzu.vmware.com/application-platform)
- [Tanzu Developer Tools for Visual Studio Code](https://docs.vmware.com/en/VMware-Tanzu-Application-Platform/1.2/tap/GUID-vscode-extension-about.html)
- [Tanzu Developer Tools for IntelliJ](https://docs.vmware.com/en/VMware-Tanzu-Application-Platform/1.2/tap/GUID-intellij-extension-about.html)
- [Thymeleaf](https://www.thymeleaf.org/)
- [WebJars](https://www.webjars.org)

> **_NOTE:_** Below you can find additional information concerning creation of AppSSO relevant resources. 

## Resources needed for AppSSO integration

Please first familiarize yourself with basic concepts around using AppSSO to secure your workload on TAP following 
[AppSSO's documentation](https://docs.vmware.com/en/VMware-Tanzu-Application-Platform/1.6/tap/app-sso-about.html)
.

This repository includes an integration to set up an authentication mechanism with AppSSO.

## Getting Started

1. Discover your `AppSSO` service offerings

   ```bash
   tanzu services classes list
   ```

   If there isn't one,

     - ask your service operator `OR`
     - [create your own `ClusterUnsafeTestLogin`](https://docs.vmware.com/en/VMware-Tanzu-Application-Platform/1.6/tap/app-sso-reference-api-clusterunsafetestlogin.html)

2. Select the service offering you'd like to connect

4. Claim an instance from the offering

   ```bash
   tanzu services class-claims create server-side-ui-starter \
     --class sample-full \
     --parameter workloadRef.name=server-side-ui-starter \
     --parameter redirectPaths='["/login/oauth2/code/server-side-ui-starter"]'
   ```

5. Apply your workload

   ```bash
   tanzu apps workload apply \
     --file config/workload.yaml \
     --namespace <namespace> \
     --yes \
     --tail
   ```

> **_NOTE:_** Below you can find additional information concerning AppSSO integration. 

## AppSSO Configuration
Apart from the default `application.yaml` an `application-local.yaml` is included which can be used for
local development.

> If you start the application locally please be sure that `local` profile is active.
