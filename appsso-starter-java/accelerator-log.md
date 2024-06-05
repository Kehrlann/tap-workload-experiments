# Accelerator Log

## Options
```json
{
  "projectName" : "appsso-starter-java",
  "appssoOfferingName" : "ci",
  "includeBuildToolWrapper" : true
}
```
## Log
```
┏ engine (Chain)
┃  Info Running Chain(GeneratorValidationTransform, UniquePath)
┃ ┏ ┏ engine.transformations[0].validated (Combo)
┃ ┃ ┃  Info Combo running as Chain
┃ ┃ ┃ engine.transformations[0].validated.delegate (Chain)
┃ ┃ ┃  Info Running Chain(Combo, Combo, Provenance)
┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0] (Combo)
┃ ┃ ┃ ┃  Info Combo running as Chain
┃ ┃ ┃ ┃ engine.transformations[0].validated.delegate.transformations[0].delegate (Chain)
┃ ┃ ┃ ┃  Info Running Chain(Merge, UniquePath)
┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].delegate.transformations[0] (Merge)
┃ ┃ ┃ ┃ ┃  Info Running Merge(Combo, Combo, Combo, Combo)
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].delegate.transformations[0].sources[0] (Combo)
┃ ┃ ┃ ┃ ┃ ┃  Info Combo running as Chain
┃ ┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.delegate.transformations[0].delegate.transformations[0].sources[0].delegate (Chain)
┃ ┃ ┃ ┃ ┃ ┃  Info Running Chain(Include, Exclude)
┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].delegate.transformations[0].sources[0].delegate.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Will include [**]
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug LICENSE matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .tanzuignore matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug config/workload.yaml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug README.md matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradle/wrapper/gradle-wrapper.jar matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradle/wrapper/gradle-wrapper.properties matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradlew matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gitignore matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build.gradle matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/file-system.probe matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/vcs-1/gc.properties matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/buildOutputCleanup/cache.properties matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/buildOutputCleanup/outputFiles.bin matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/buildOutputCleanup/buildOutputCleanup.lock matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/executionHistory/executionHistory.lock matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/executionHistory/executionHistory.bin matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/gc.properties matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileChanges/last-build.bin matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/dependencies-accessors/gc.properties matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/dependencies-accessors/dependencies-accessors.lock matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/checksums/checksums.lock matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/checksums/md5-checksums.bin matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/checksums/sha1-checksums.bin matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileHashes/fileHashes.lock matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileHashes/fileHashes.bin matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileHashes/resourceHashesCache.bin matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/test/com/vmware/tanzu/apps/sso/accelerator/TestAcceleratorConfiguration.class matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/test/com/vmware/tanzu/apps/sso/accelerator/AppSSOAcceleratorApplicationTest.class matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/main/com/vmware/tanzu/apps/sso/accelerator/config/WebSecurityConfig.class matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/main/com/vmware/tanzu/apps/sso/accelerator/config/IssuerTrust.class matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/main/com/vmware/tanzu/apps/sso/accelerator/web/AuthenticatedHomeController.class matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/main/com/vmware/tanzu/apps/sso/accelerator/web/HomeController.class matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/main/com/vmware/tanzu/apps/sso/accelerator/AppSSOAcceleratorApplication.class matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resolvedMainClassName matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/dex.yaml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/static/images/tanzu-logomark.svg matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/static/styles/main.css matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/compose.yaml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/templates/home.html matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/templates/authenticated-home.html matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/application-local.yml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/libs/appsso-starter-java-0.0.1-SNAPSHOT.jar matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/tmp/bootJar/MANIFEST.MF matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/tmp/compileJava/previous-compilation-data.bin matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/tmp/compileTestJava/previous-compilation-data.bin matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradlew.bat matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug settings.gradle matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/jarRepositories.xml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/gradle.xml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/vcs.xml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/.gitignore matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/workspace.xml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/misc.xml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/compiler.xml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/com/vmware/tanzu/apps/sso/accelerator/AppSSOAcceleratorApplicationTest.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/dex.yaml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/images/tanzu-logomark.svg matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/styles/main.css matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/compose.yaml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/home.html matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/authenticated-home.html matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/application-local.yml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vmware/tanzu/apps/sso/accelerator/config/WebSecurityConfig.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vmware/tanzu/apps/sso/accelerator/config/IssuerTrust.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vmware/tanzu/apps/sso/accelerator/web/AuthenticatedHomeController.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vmware/tanzu/apps/sso/accelerator/web/HomeController.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┗ Debug src/main/java/com/vmware/tanzu/apps/sso/accelerator/AppSSOAcceleratorApplication.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].delegate.transformations[0].sources[0].delegate.transformations[1] (Exclude)
┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Will exclude [catalog/*.yaml, config/workload.yaml]
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug LICENSE didn't match [catalog/*.yaml, config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .tanzuignore didn't match [catalog/*.yaml, config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug config/workload.yaml matched [catalog/*.yaml, config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml matched [catalog/*.yaml, config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [catalog/*.yaml, config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradle/wrapper/gradle-wrapper.jar didn't match [catalog/*.yaml, config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradle/wrapper/gradle-wrapper.properties didn't match [catalog/*.yaml, config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradlew didn't match [catalog/*.yaml, config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gitignore didn't match [catalog/*.yaml, config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build.gradle didn't match [catalog/*.yaml, config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/file-system.probe didn't match [catalog/*.yaml, config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/vcs-1/gc.properties didn't match [catalog/*.yaml, config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/buildOutputCleanup/cache.properties didn't match [catalog/*.yaml, config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/buildOutputCleanup/outputFiles.bin didn't match [catalog/*.yaml, config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/buildOutputCleanup/buildOutputCleanup.lock didn't match [catalog/*.yaml, config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/executionHistory/executionHistory.lock didn't match [catalog/*.yaml, config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/executionHistory/executionHistory.bin didn't match [catalog/*.yaml, config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/gc.properties didn't match [catalog/*.yaml, config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileChanges/last-build.bin didn't match [catalog/*.yaml, config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/dependencies-accessors/gc.properties didn't match [catalog/*.yaml, config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/dependencies-accessors/dependencies-accessors.lock didn't match [catalog/*.yaml, config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/checksums/checksums.lock didn't match [catalog/*.yaml, config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/checksums/md5-checksums.bin didn't match [catalog/*.yaml, config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/checksums/sha1-checksums.bin didn't match [catalog/*.yaml, config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileHashes/fileHashes.lock didn't match [catalog/*.yaml, config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileHashes/fileHashes.bin didn't match [catalog/*.yaml, config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileHashes/resourceHashesCache.bin didn't match [catalog/*.yaml, config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/test/com/vmware/tanzu/apps/sso/accelerator/TestAcceleratorConfiguration.class didn't match [catalog/*.yaml, config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/test/com/vmware/tanzu/apps/sso/accelerator/AppSSOAcceleratorApplicationTest.class didn't match [catalog/*.yaml, config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/main/com/vmware/tanzu/apps/sso/accelerator/config/WebSecurityConfig.class didn't match [catalog/*.yaml, config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/main/com/vmware/tanzu/apps/sso/accelerator/config/IssuerTrust.class didn't match [catalog/*.yaml, config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/main/com/vmware/tanzu/apps/sso/accelerator/web/AuthenticatedHomeController.class didn't match [catalog/*.yaml, config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/main/com/vmware/tanzu/apps/sso/accelerator/web/HomeController.class didn't match [catalog/*.yaml, config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/main/com/vmware/tanzu/apps/sso/accelerator/AppSSOAcceleratorApplication.class didn't match [catalog/*.yaml, config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resolvedMainClassName didn't match [catalog/*.yaml, config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/dex.yaml didn't match [catalog/*.yaml, config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/static/images/tanzu-logomark.svg didn't match [catalog/*.yaml, config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/static/styles/main.css didn't match [catalog/*.yaml, config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/compose.yaml didn't match [catalog/*.yaml, config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/templates/home.html didn't match [catalog/*.yaml, config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/templates/authenticated-home.html didn't match [catalog/*.yaml, config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/application-local.yml didn't match [catalog/*.yaml, config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/libs/appsso-starter-java-0.0.1-SNAPSHOT.jar didn't match [catalog/*.yaml, config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/tmp/bootJar/MANIFEST.MF didn't match [catalog/*.yaml, config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/tmp/compileJava/previous-compilation-data.bin didn't match [catalog/*.yaml, config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/tmp/compileTestJava/previous-compilation-data.bin didn't match [catalog/*.yaml, config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradlew.bat didn't match [catalog/*.yaml, config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug settings.gradle didn't match [catalog/*.yaml, config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/jarRepositories.xml didn't match [catalog/*.yaml, config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/gradle.xml didn't match [catalog/*.yaml, config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/vcs.xml didn't match [catalog/*.yaml, config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/.gitignore didn't match [catalog/*.yaml, config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/workspace.xml didn't match [catalog/*.yaml, config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/misc.xml didn't match [catalog/*.yaml, config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/compiler.xml didn't match [catalog/*.yaml, config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/com/vmware/tanzu/apps/sso/accelerator/AppSSOAcceleratorApplicationTest.java didn't match [catalog/*.yaml, config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/dex.yaml didn't match [catalog/*.yaml, config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/images/tanzu-logomark.svg didn't match [catalog/*.yaml, config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/styles/main.css didn't match [catalog/*.yaml, config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/compose.yaml didn't match [catalog/*.yaml, config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/home.html didn't match [catalog/*.yaml, config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/authenticated-home.html didn't match [catalog/*.yaml, config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/application-local.yml didn't match [catalog/*.yaml, config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vmware/tanzu/apps/sso/accelerator/config/WebSecurityConfig.java didn't match [catalog/*.yaml, config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vmware/tanzu/apps/sso/accelerator/config/IssuerTrust.java didn't match [catalog/*.yaml, config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vmware/tanzu/apps/sso/accelerator/web/AuthenticatedHomeController.java didn't match [catalog/*.yaml, config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vmware/tanzu/apps/sso/accelerator/web/HomeController.java didn't match [catalog/*.yaml, config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┗ ┗ Debug src/main/java/com/vmware/tanzu/apps/sso/accelerator/AppSSOAcceleratorApplication.java didn't match [catalog/*.yaml, config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].delegate.transformations[0].sources[1] (Combo)
┃ ┃ ┃ ┃ ┃ ┃  Info Combo running as Chain
┃ ┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.delegate.transformations[0].delegate.transformations[0].sources[1].delegate (Chain)
┃ ┃ ┃ ┃ ┃ ┃  Info Running Chain(Include, ReplaceText)
┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].delegate.transformations[0].sources[1].delegate.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Will include [catalog/*.yaml]
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug LICENSE didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .tanzuignore didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug config/workload.yaml didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml matched [catalog/*.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradle/wrapper/gradle-wrapper.jar didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradle/wrapper/gradle-wrapper.properties didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradlew didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gitignore didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build.gradle didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/file-system.probe didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/vcs-1/gc.properties didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/buildOutputCleanup/cache.properties didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/buildOutputCleanup/outputFiles.bin didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/buildOutputCleanup/buildOutputCleanup.lock didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/executionHistory/executionHistory.lock didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/executionHistory/executionHistory.bin didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/gc.properties didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileChanges/last-build.bin didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/dependencies-accessors/gc.properties didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/dependencies-accessors/dependencies-accessors.lock didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/checksums/checksums.lock didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/checksums/md5-checksums.bin didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/checksums/sha1-checksums.bin didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileHashes/fileHashes.lock didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileHashes/fileHashes.bin didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileHashes/resourceHashesCache.bin didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/test/com/vmware/tanzu/apps/sso/accelerator/TestAcceleratorConfiguration.class didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/test/com/vmware/tanzu/apps/sso/accelerator/AppSSOAcceleratorApplicationTest.class didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/main/com/vmware/tanzu/apps/sso/accelerator/config/WebSecurityConfig.class didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/main/com/vmware/tanzu/apps/sso/accelerator/config/IssuerTrust.class didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/main/com/vmware/tanzu/apps/sso/accelerator/web/AuthenticatedHomeController.class didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/main/com/vmware/tanzu/apps/sso/accelerator/web/HomeController.class didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/main/com/vmware/tanzu/apps/sso/accelerator/AppSSOAcceleratorApplication.class didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resolvedMainClassName didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/dex.yaml didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/static/images/tanzu-logomark.svg didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/static/styles/main.css didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/compose.yaml didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/templates/home.html didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/templates/authenticated-home.html didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/application-local.yml didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/libs/appsso-starter-java-0.0.1-SNAPSHOT.jar didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/tmp/bootJar/MANIFEST.MF didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/tmp/compileJava/previous-compilation-data.bin didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/tmp/compileTestJava/previous-compilation-data.bin didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradlew.bat didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug settings.gradle didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/jarRepositories.xml didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/gradle.xml didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/vcs.xml didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/.gitignore didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/workspace.xml didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/misc.xml didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/compiler.xml didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/com/vmware/tanzu/apps/sso/accelerator/AppSSOAcceleratorApplicationTest.java didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/dex.yaml didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/images/tanzu-logomark.svg didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/styles/main.css didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/compose.yaml didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/home.html didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/authenticated-home.html didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/application-local.yml didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vmware/tanzu/apps/sso/accelerator/config/WebSecurityConfig.java didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vmware/tanzu/apps/sso/accelerator/config/IssuerTrust.java didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vmware/tanzu/apps/sso/accelerator/web/AuthenticatedHomeController.java didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vmware/tanzu/apps/sso/accelerator/web/HomeController.java didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┗ Debug src/main/java/com/vmware/tanzu/apps/sso/accelerator/AppSSOAcceleratorApplication.java didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].delegate.transformations[0].sources[1].delegate.transformations[1] (ReplaceText)
┃ ┃ ┃ ┃ ┃ ┗ ┗  Info Will replace [appsso-starter-java->appsso-starter-java]
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].delegate.transformations[0].sources[2] (Combo)
┃ ┃ ┃ ┃ ┃ ┃  Info Combo running as Chain
┃ ┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.delegate.transformations[0].delegate.transformations[0].sources[2].delegate (Chain)
┃ ┃ ┃ ┃ ┃ ┃  Info Running Chain(Include, ReplaceText)
┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].delegate.transformations[0].sources[2].delegate.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Will include [config/workload.yaml]
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug LICENSE didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .tanzuignore didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug config/workload.yaml matched [config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradle/wrapper/gradle-wrapper.jar didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradle/wrapper/gradle-wrapper.properties didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradlew didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gitignore didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build.gradle didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/file-system.probe didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/vcs-1/gc.properties didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/buildOutputCleanup/cache.properties didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/buildOutputCleanup/outputFiles.bin didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/buildOutputCleanup/buildOutputCleanup.lock didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/executionHistory/executionHistory.lock didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/executionHistory/executionHistory.bin didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/gc.properties didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileChanges/last-build.bin didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/dependencies-accessors/gc.properties didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/dependencies-accessors/dependencies-accessors.lock didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/checksums/checksums.lock didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/checksums/md5-checksums.bin didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/checksums/sha1-checksums.bin didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileHashes/fileHashes.lock didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileHashes/fileHashes.bin didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileHashes/resourceHashesCache.bin didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/test/com/vmware/tanzu/apps/sso/accelerator/TestAcceleratorConfiguration.class didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/test/com/vmware/tanzu/apps/sso/accelerator/AppSSOAcceleratorApplicationTest.class didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/main/com/vmware/tanzu/apps/sso/accelerator/config/WebSecurityConfig.class didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/main/com/vmware/tanzu/apps/sso/accelerator/config/IssuerTrust.class didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/main/com/vmware/tanzu/apps/sso/accelerator/web/AuthenticatedHomeController.class didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/main/com/vmware/tanzu/apps/sso/accelerator/web/HomeController.class didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/main/com/vmware/tanzu/apps/sso/accelerator/AppSSOAcceleratorApplication.class didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resolvedMainClassName didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/dex.yaml didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/static/images/tanzu-logomark.svg didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/static/styles/main.css didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/compose.yaml didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/templates/home.html didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/templates/authenticated-home.html didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/application-local.yml didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/libs/appsso-starter-java-0.0.1-SNAPSHOT.jar didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/tmp/bootJar/MANIFEST.MF didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/tmp/compileJava/previous-compilation-data.bin didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/tmp/compileTestJava/previous-compilation-data.bin didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradlew.bat didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug settings.gradle didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/jarRepositories.xml didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/gradle.xml didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/vcs.xml didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/.gitignore didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/workspace.xml didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/misc.xml didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/compiler.xml didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/com/vmware/tanzu/apps/sso/accelerator/AppSSOAcceleratorApplicationTest.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/dex.yaml didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/images/tanzu-logomark.svg didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/styles/main.css didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/compose.yaml didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/home.html didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/authenticated-home.html didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/application-local.yml didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vmware/tanzu/apps/sso/accelerator/config/WebSecurityConfig.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vmware/tanzu/apps/sso/accelerator/config/IssuerTrust.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vmware/tanzu/apps/sso/accelerator/web/AuthenticatedHomeController.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vmware/tanzu/apps/sso/accelerator/web/HomeController.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┗ Debug src/main/java/com/vmware/tanzu/apps/sso/accelerator/AppSSOAcceleratorApplication.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].delegate.transformations[0].sources[2].delegate.transformations[1] (ReplaceText)
┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Will replace [
┃ ┃ ┃ ┃ ┃ ┃ ┃  Info   name: appsso-starter-java->
┃ ┃ ┃ ┃ ┃ ┗ ┗  Info   name: appsso-star...(truncated), app.kubernetes.io/part-of: appsso-starter-java->app.kubernetes.io/pa...(truncated)]
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].delegate.transformations[0].sources[3] (Combo)
┃ ┃ ┃ ┃ ┃ ┃  Info Combo running as Chain
┃ ┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.delegate.transformations[0].delegate.transformations[0].sources[3].delegate (Chain)
┃ ┃ ┃ ┃ ┃ ┃  Info Running Chain(Include, ReplaceText)
┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].delegate.transformations[0].sources[3].delegate.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Will include [README.md]
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug LICENSE didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .tanzuignore didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug config/workload.yaml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug README.md matched [README.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradle/wrapper/gradle-wrapper.jar didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradle/wrapper/gradle-wrapper.properties didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradlew didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gitignore didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build.gradle didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/file-system.probe didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/vcs-1/gc.properties didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/buildOutputCleanup/cache.properties didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/buildOutputCleanup/outputFiles.bin didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/buildOutputCleanup/buildOutputCleanup.lock didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/executionHistory/executionHistory.lock didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/executionHistory/executionHistory.bin didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/gc.properties didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileChanges/last-build.bin didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/dependencies-accessors/gc.properties didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/dependencies-accessors/dependencies-accessors.lock didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/checksums/checksums.lock didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/checksums/md5-checksums.bin didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/checksums/sha1-checksums.bin didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileHashes/fileHashes.lock didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileHashes/fileHashes.bin didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileHashes/resourceHashesCache.bin didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/test/com/vmware/tanzu/apps/sso/accelerator/TestAcceleratorConfiguration.class didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/test/com/vmware/tanzu/apps/sso/accelerator/AppSSOAcceleratorApplicationTest.class didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/main/com/vmware/tanzu/apps/sso/accelerator/config/WebSecurityConfig.class didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/main/com/vmware/tanzu/apps/sso/accelerator/config/IssuerTrust.class didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/main/com/vmware/tanzu/apps/sso/accelerator/web/AuthenticatedHomeController.class didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/main/com/vmware/tanzu/apps/sso/accelerator/web/HomeController.class didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/main/com/vmware/tanzu/apps/sso/accelerator/AppSSOAcceleratorApplication.class didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resolvedMainClassName didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/dex.yaml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/static/images/tanzu-logomark.svg didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/static/styles/main.css didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/compose.yaml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/templates/home.html didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/templates/authenticated-home.html didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/application-local.yml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/libs/appsso-starter-java-0.0.1-SNAPSHOT.jar didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/tmp/bootJar/MANIFEST.MF didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/tmp/compileJava/previous-compilation-data.bin didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/tmp/compileTestJava/previous-compilation-data.bin didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradlew.bat didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug settings.gradle didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/jarRepositories.xml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/gradle.xml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/vcs.xml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/.gitignore didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/workspace.xml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/misc.xml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/compiler.xml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/com/vmware/tanzu/apps/sso/accelerator/AppSSOAcceleratorApplicationTest.java didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/dex.yaml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/images/tanzu-logomark.svg didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/styles/main.css didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/compose.yaml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/home.html didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/authenticated-home.html didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/application-local.yml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vmware/tanzu/apps/sso/accelerator/config/WebSecurityConfig.java didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vmware/tanzu/apps/sso/accelerator/config/IssuerTrust.java didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vmware/tanzu/apps/sso/accelerator/web/AuthenticatedHomeController.java didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vmware/tanzu/apps/sso/accelerator/web/HomeController.java didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┗ Debug src/main/java/com/vmware/tanzu/apps/sso/accelerator/AppSSOAcceleratorApplication.java didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].delegate.transformations[0].sources[3].delegate.transformations[1] (ReplaceText)
┃ ┃ ┃ ┃ ┗ ┗ ┗  Info Will replace [<your-selected-appsso-offering>->ci]
┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].delegate.transformations[1] (UniquePath)
┃ ┃ ┃ ┗ ┗ Debug Multiple representations for path 'README.md', will use the one appearing last 
┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[1] (Combo)
┃ ┃ ┃ ┃  Info Combo running as Chain
┃ ┃ ┃ ┃ engine.transformations[0].validated.delegate.transformations[1].delegate (Chain)
┃ ┃ ┃ ┃  Info Running Chain(Merge, UniquePath)
┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[1].delegate.transformations[0] (Merge)
┃ ┃ ┃ ┃ ┃  Info Running Merge(InvokeFragment, InvokeFragment, Combo)
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[1].delegate.transformations[0].sources[0] (InvokeFragment)
┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[1].delegate.transformations[0].sources[0].validated (Combo)
┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Combo running as Chain
┃ ┃ ┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.delegate.transformations[1].delegate.transformations[0].sources[0].validated.delegate (Chain)
┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Running Chain(Merge, UniquePath)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[1].delegate.transformations[0].sources[0].validated.delegate.transformations[0] (Merge)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Running Merge(Combo)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[1].delegate.transformations[0].sources[0].validated.delegate.transformations[0].sources[0] (Combo)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Condition (#includeBuildToolWrapper) evaluated to true
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Combo running as Include
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.delegate.transformations[1].delegate.transformations[0].sources[0].validated.delegate.transformations[0].sources[0].delegate (Include)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Will include [gradlew*, gradle/**]
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/application-local.yml didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/application-local.yml didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/buildOutputCleanup/buildOutputCleanup.lock didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/dex.yaml didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/tmp/bootJar/MANIFEST.MF didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/main/com/vmware/tanzu/apps/sso/accelerator/config/IssuerTrust.class didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vmware/tanzu/apps/sso/accelerator/config/WebSecurityConfig.java didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/executionHistory/executionHistory.lock didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradlew.bat matched [gradlew*, gradle/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/misc.xml didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vmware/tanzu/apps/sso/accelerator/AppSSOAcceleratorApplication.java didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/templates/authenticated-home.html didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vmware/tanzu/apps/sso/accelerator/config/IssuerTrust.java didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/workspace.xml didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/libs/appsso-starter-java-0.0.1-SNAPSHOT.jar didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/gradle.xml didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/buildOutputCleanup/cache.properties didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/dex.yaml didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug LICENSE didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/file-system.probe didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradlew matched [gradlew*, gradle/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/jarRepositories.xml didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/main/com/vmware/tanzu/apps/sso/accelerator/web/AuthenticatedHomeController.class didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/home.html didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/.gitignore didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/checksums/sha1-checksums.bin didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/test/com/vmware/tanzu/apps/sso/accelerator/TestAcceleratorConfiguration.class didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/templates/home.html didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vmware/tanzu/apps/sso/accelerator/web/AuthenticatedHomeController.java didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/com/vmware/tanzu/apps/sso/accelerator/AppSSOAcceleratorApplicationTest.java didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/compiler.xml didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileHashes/fileHashes.lock didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gitignore didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/vcs-1/gc.properties didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/compose.yaml didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradle/wrapper/gradle-wrapper.jar matched [gradlew*, gradle/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/static/styles/main.css didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/main/com/vmware/tanzu/apps/sso/accelerator/web/HomeController.class didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileChanges/last-build.bin didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradle/wrapper/gradle-wrapper.properties matched [gradlew*, gradle/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/main/com/vmware/tanzu/apps/sso/accelerator/config/WebSecurityConfig.class didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vmware/tanzu/apps/sso/accelerator/web/HomeController.java didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/images/tanzu-logomark.svg didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/vcs.xml didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/static/images/tanzu-logomark.svg didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/main/com/vmware/tanzu/apps/sso/accelerator/AppSSOAcceleratorApplication.class didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build.gradle didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/test/com/vmware/tanzu/apps/sso/accelerator/AppSSOAcceleratorApplicationTest.class didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/styles/main.css didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/dependencies-accessors/gc.properties didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .tanzuignore didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/tmp/compileTestJava/previous-compilation-data.bin didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug settings.gradle didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/authenticated-home.html didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/tmp/compileJava/previous-compilation-data.bin didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileHashes/resourceHashesCache.bin didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/buildOutputCleanup/outputFiles.bin didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/executionHistory/executionHistory.bin didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileHashes/fileHashes.bin didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/checksums/md5-checksums.bin didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug config/workload.yaml didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/checksums/checksums.lock didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/gc.properties didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/compose.yaml didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resolvedMainClassName didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/dependencies-accessors/dependencies-accessors.lock didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradle/wrapper/gradle-wrapper.jar matched [gradlew*, gradle/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradle/wrapper/gradle-wrapper.properties matched [gradlew*, gradle/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradlew matched [gradlew*, gradle/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ ┗ Debug gradlew.bat matched [gradlew*, gradle/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[1].delegate.transformations[0].sources[0].validated.delegate.transformations[1] (UniquePath)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'gradlew', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'gradle/wrapper/gradle-wrapper.jar', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'gradle/wrapper/gradle-wrapper.properties', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┗ ┗ ┗ Debug Multiple representations for path 'gradlew.bat', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[1].delegate.transformations[0].sources[1] (InvokeFragment)
┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[1].delegate.transformations[0].sources[1].validated (Include)
┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Will include [**]
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/application-local.yml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/application-local.yml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/buildOutputCleanup/buildOutputCleanup.lock matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/dex.yaml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/tmp/bootJar/MANIFEST.MF matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/main/com/vmware/tanzu/apps/sso/accelerator/config/IssuerTrust.class matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vmware/tanzu/apps/sso/accelerator/config/WebSecurityConfig.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/executionHistory/executionHistory.lock matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradlew.bat matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/misc.xml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vmware/tanzu/apps/sso/accelerator/AppSSOAcceleratorApplication.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/templates/authenticated-home.html matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vmware/tanzu/apps/sso/accelerator/config/IssuerTrust.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/workspace.xml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/libs/appsso-starter-java-0.0.1-SNAPSHOT.jar matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/gradle.xml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/buildOutputCleanup/cache.properties matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/dex.yaml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug LICENSE matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/file-system.probe matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradlew matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/jarRepositories.xml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/main/com/vmware/tanzu/apps/sso/accelerator/web/AuthenticatedHomeController.class matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/home.html matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/.gitignore matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/checksums/sha1-checksums.bin matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/test/com/vmware/tanzu/apps/sso/accelerator/TestAcceleratorConfiguration.class matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/templates/home.html matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vmware/tanzu/apps/sso/accelerator/web/AuthenticatedHomeController.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/com/vmware/tanzu/apps/sso/accelerator/AppSSOAcceleratorApplicationTest.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/compiler.xml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileHashes/fileHashes.lock matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gitignore matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/vcs-1/gc.properties matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/compose.yaml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradle/wrapper/gradle-wrapper.jar matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/static/styles/main.css matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/main/com/vmware/tanzu/apps/sso/accelerator/web/HomeController.class matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileChanges/last-build.bin matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradle/wrapper/gradle-wrapper.properties matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/main/com/vmware/tanzu/apps/sso/accelerator/config/WebSecurityConfig.class matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vmware/tanzu/apps/sso/accelerator/web/HomeController.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/images/tanzu-logomark.svg matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/vcs.xml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/static/images/tanzu-logomark.svg matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/main/com/vmware/tanzu/apps/sso/accelerator/AppSSOAcceleratorApplication.class matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build.gradle matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/test/com/vmware/tanzu/apps/sso/accelerator/AppSSOAcceleratorApplicationTest.class matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/styles/main.css matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/dependencies-accessors/gc.properties matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .tanzuignore matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/tmp/compileTestJava/previous-compilation-data.bin matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug settings.gradle matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/authenticated-home.html matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/tmp/compileJava/previous-compilation-data.bin matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileHashes/resourceHashesCache.bin matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/buildOutputCleanup/outputFiles.bin matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/executionHistory/executionHistory.bin matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileHashes/fileHashes.bin matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/checksums/md5-checksums.bin matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug config/workload.yaml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/checksums/checksums.lock matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/gc.properties matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/compose.yaml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resolvedMainClassName matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/dependencies-accessors/dependencies-accessors.lock matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug README.md matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug accelerator.axl matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┗ ┗ Debug README.md matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[1].delegate.transformations[0].sources[2] (Combo)
┃ ┃ ┃ ┃ ┃ ┃  Info Combo running as Include
┃ ┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.delegate.transformations[1].delegate.transformations[0].sources[2].delegate (Include)
┃ ┃ ┃ ┃ ┃ ┃  Info Will include [**]
┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/application-local.yml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/application-local.yml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/buildOutputCleanup/buildOutputCleanup.lock matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/dex.yaml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug build/tmp/bootJar/MANIFEST.MF matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/main/com/vmware/tanzu/apps/sso/accelerator/config/IssuerTrust.class matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vmware/tanzu/apps/sso/accelerator/config/WebSecurityConfig.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/executionHistory/executionHistory.lock matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug gradlew.bat matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/misc.xml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vmware/tanzu/apps/sso/accelerator/AppSSOAcceleratorApplication.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/templates/authenticated-home.html matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vmware/tanzu/apps/sso/accelerator/config/IssuerTrust.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/workspace.xml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug build/libs/appsso-starter-java-0.0.1-SNAPSHOT.jar matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/gradle.xml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/buildOutputCleanup/cache.properties matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/dex.yaml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug LICENSE matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/file-system.probe matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug gradlew matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/jarRepositories.xml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/main/com/vmware/tanzu/apps/sso/accelerator/web/AuthenticatedHomeController.class matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/home.html matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/.gitignore matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/checksums/sha1-checksums.bin matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/test/com/vmware/tanzu/apps/sso/accelerator/TestAcceleratorConfiguration.class matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/templates/home.html matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vmware/tanzu/apps/sso/accelerator/web/AuthenticatedHomeController.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/com/vmware/tanzu/apps/sso/accelerator/AppSSOAcceleratorApplicationTest.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/compiler.xml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileHashes/fileHashes.lock matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug .gitignore matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/vcs-1/gc.properties matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/compose.yaml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug gradle/wrapper/gradle-wrapper.jar matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/static/styles/main.css matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/main/com/vmware/tanzu/apps/sso/accelerator/web/HomeController.class matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileChanges/last-build.bin matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug gradle/wrapper/gradle-wrapper.properties matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/main/com/vmware/tanzu/apps/sso/accelerator/config/WebSecurityConfig.class matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vmware/tanzu/apps/sso/accelerator/web/HomeController.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/images/tanzu-logomark.svg matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/vcs.xml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/static/images/tanzu-logomark.svg matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/main/com/vmware/tanzu/apps/sso/accelerator/AppSSOAcceleratorApplication.class matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug build.gradle matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/test/com/vmware/tanzu/apps/sso/accelerator/AppSSOAcceleratorApplicationTest.class matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/styles/main.css matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/dependencies-accessors/gc.properties matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug .tanzuignore matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug build/tmp/compileTestJava/previous-compilation-data.bin matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug settings.gradle matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/authenticated-home.html matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug build/tmp/compileJava/previous-compilation-data.bin matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileHashes/resourceHashesCache.bin matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/buildOutputCleanup/outputFiles.bin matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/executionHistory/executionHistory.bin matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileHashes/fileHashes.bin matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/checksums/md5-checksums.bin matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug config/workload.yaml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/checksums/checksums.lock matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/gc.properties matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/compose.yaml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug build/resolvedMainClassName matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/dependencies-accessors/dependencies-accessors.lock matched [**] -> included
┃ ┃ ┃ ┃ ┗ ┗ Debug README.md matched [**] -> included
┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[1].delegate.transformations[1] (UniquePath)
┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'build/resources/main/application-local.yml', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'src/main/resources/application-local.yml', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path '.gradle/buildOutputCleanup/buildOutputCleanup.lock', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'build/resources/main/dex.yaml', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'build/tmp/bootJar/MANIFEST.MF', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'build/classes/java/main/com/vmware/tanzu/apps/sso/accelerator/config/IssuerTrust.class', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/com/vmware/tanzu/apps/sso/accelerator/config/WebSecurityConfig.java', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path '.gradle/7.5.1/executionHistory/executionHistory.lock', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'gradlew.bat', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path '.idea/misc.xml', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'build/resources/main/templates/authenticated-home.html', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/com/vmware/tanzu/apps/sso/accelerator/AppSSOAcceleratorApplication.java', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/com/vmware/tanzu/apps/sso/accelerator/config/IssuerTrust.java', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'build/libs/appsso-starter-java-0.0.1-SNAPSHOT.jar', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path '.idea/workspace.xml', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path '.idea/gradle.xml', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path '.gradle/buildOutputCleanup/cache.properties', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'src/main/resources/dex.yaml', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'LICENSE', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path '.gradle/file-system.probe', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'gradlew', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'build/classes/java/main/com/vmware/tanzu/apps/sso/accelerator/web/AuthenticatedHomeController.class', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path '.idea/jarRepositories.xml', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'src/main/resources/templates/home.html', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path '.idea/.gitignore', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path '.gradle/7.5.1/checksums/sha1-checksums.bin', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'build/classes/java/test/com/vmware/tanzu/apps/sso/accelerator/TestAcceleratorConfiguration.class', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'README.md', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'build/resources/main/templates/home.html', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/com/vmware/tanzu/apps/sso/accelerator/web/AuthenticatedHomeController.java', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path '.gradle/7.5.1/fileHashes/fileHashes.lock', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path '.idea/compiler.xml', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'src/test/java/com/vmware/tanzu/apps/sso/accelerator/AppSSOAcceleratorApplicationTest.java', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path '.gitignore', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path '.gradle/vcs-1/gc.properties', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'src/main/resources/compose.yaml', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'gradle/wrapper/gradle-wrapper.jar', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'build/resources/main/static/styles/main.css', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path '.gradle/7.5.1/fileChanges/last-build.bin', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'build/classes/java/main/com/vmware/tanzu/apps/sso/accelerator/web/HomeController.class', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'gradle/wrapper/gradle-wrapper.properties', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'build/classes/java/main/com/vmware/tanzu/apps/sso/accelerator/config/WebSecurityConfig.class', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'src/main/resources/static/images/tanzu-logomark.svg', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/com/vmware/tanzu/apps/sso/accelerator/web/HomeController.java', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'build/classes/java/main/com/vmware/tanzu/apps/sso/accelerator/AppSSOAcceleratorApplication.class', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'build/resources/main/static/images/tanzu-logomark.svg', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path '.idea/vcs.xml', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'build.gradle', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'build/classes/java/test/com/vmware/tanzu/apps/sso/accelerator/AppSSOAcceleratorApplicationTest.class', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path '.gradle/7.5.1/dependencies-accessors/gc.properties', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'src/main/resources/static/styles/main.css', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path '.tanzuignore', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'build/tmp/compileTestJava/previous-compilation-data.bin', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'settings.gradle', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'src/main/resources/templates/authenticated-home.html', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'build/tmp/compileJava/previous-compilation-data.bin', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path '.gradle/7.5.1/fileHashes/resourceHashesCache.bin', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path '.gradle/buildOutputCleanup/outputFiles.bin', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path '.gradle/7.5.1/executionHistory/executionHistory.bin', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path '.gradle/7.5.1/fileHashes/fileHashes.bin', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path '.gradle/7.5.1/checksums/md5-checksums.bin', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'catalog/catalog-info.yaml', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path '.gradle/7.5.1/checksums/checksums.lock', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'config/workload.yaml', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path '.gradle/7.5.1/gc.properties', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'build/resources/main/compose.yaml', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'build/resolvedMainClassName', will use the one appearing first 
┃ ┃ ┃ ┗ ┗ Debug Multiple representations for path '.gradle/7.5.1/dependencies-accessors/dependencies-accessors.lock', will use the one appearing first 
┃ ┗ ┗ ╺ engine.transformations[0].validated.delegate.transformations[2] (Provenance)
┗ ╺ engine.transformations[1] (UniquePath)
```
