# Accelerator Log

## Options
```json
{
  "projectName" : "java-server-side-ui",
  "artifactId" : "server-side-ui-starter",
  "groupId" : "com.example",
  "packageName" : "com.example.serversideuistarter",
  "javaVersion" : "17",
  "buildTool" : "maven",
  "includeAppSsoIntegration" : true,
  "appssoOfferingName" : "ci",
  "liveUpdateIDESupport" : true,
  "includeBuildToolWrapper" : true
}
```
## Log
```
┏ engine (Chain)
┃  Info Running Chain(GeneratorValidationTransform, UniquePath)
┃ ┏ ┏ engine.transformations[0].validated (Combo)
┃ ┃ ┃  Info Combo running as Let
┃ ┃ ┃ engine.transformations[0].validated.delegate (Let)
┃ ┃ ┃ Debug Adding symbol packageDirectory with value 'com/example/serversideuistarter'
┃ ┃ ┃ Debug Adding symbol workloadResourceName with value 'server-side-ui-starter'
┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in (Chain)
┃ ┃ ┃ ┃  Info Running Chain(Combo, Combo, Combo, Combo, Combo, Combo, Combo, Combo, Combo, Combo, Combo, Provenance)
┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[0] (Combo)
┃ ┃ ┃ ┃ ┃  Info Condition (#buildTool == 'maven') evaluated to true
┃ ┃ ┃ ┃ ┃  Info Combo running as Chain
┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.delegate.in.transformations[0].delegate (Chain)
┃ ┃ ┃ ┃ ┃  Info Running Chain(Exclude, Merge, UniquePath)
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[0].delegate.transformations[0] (Exclude)
┃ ┃ ┃ ┃ ┃ ┃  Info Will exclude [settings.gradle.kts, build.gradle.kts]
┃ ┃ ┃ ┃ ┃ ┃ Debug LICENSE didn't match [settings.gradle.kts, build.gradle.kts] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug .tanzuignore didn't match [settings.gradle.kts, build.gradle.kts] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug config/workload.yaml didn't match [settings.gradle.kts, build.gradle.kts] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug target/test-classes/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest$Get.class didn't match [settings.gradle.kts, build.gradle.kts] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug target/test-classes/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest.class didn't match [settings.gradle.kts, build.gradle.kts] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug target/test-classes/com/vmware/tap/accelerators/javaserversideui/ApplicationTest.class didn't match [settings.gradle.kts, build.gradle.kts] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/static/styles/bootstrap-custom.css didn't match [settings.gradle.kts, build.gradle.kts] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/templates/index.html didn't match [settings.gradle.kts, build.gradle.kts] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/application.yml didn't match [settings.gradle.kts, build.gradle.kts] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/com/vmware/tap/accelerators/javaserversideui/web/IndexController.class didn't match [settings.gradle.kts, build.gradle.kts] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/com/vmware/tap/accelerators/javaserversideui/Application.class didn't match [settings.gradle.kts, build.gradle.kts] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug target/maven-status/maven-compiler-plugin/testCompile/default-testCompile/inputFiles.lst didn't match [settings.gradle.kts, build.gradle.kts] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug target/maven-status/maven-compiler-plugin/testCompile/default-testCompile/createdFiles.lst didn't match [settings.gradle.kts, build.gradle.kts] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug target/maven-status/maven-compiler-plugin/compile/default-compile/inputFiles.lst didn't match [settings.gradle.kts, build.gradle.kts] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug target/maven-status/maven-compiler-plugin/compile/default-compile/createdFiles.lst didn't match [settings.gradle.kts, build.gradle.kts] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml didn't match [settings.gradle.kts, build.gradle.kts] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug pom.xml didn't match [settings.gradle.kts, build.gradle.kts] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug .grype.yaml didn't match [settings.gradle.kts, build.gradle.kts] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [settings.gradle.kts, build.gradle.kts] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug gradle/wrapper/gradle-wrapper.jar didn't match [settings.gradle.kts, build.gradle.kts] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug gradle/wrapper/gradle-wrapper.properties didn't match [settings.gradle.kts, build.gradle.kts] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug gradlew didn't match [settings.gradle.kts, build.gradle.kts] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug .gitignore didn't match [settings.gradle.kts, build.gradle.kts] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug build.gradle.kts matched [settings.gradle.kts, build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/file-system.probe didn't match [settings.gradle.kts, build.gradle.kts] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/vcs-1/gc.properties didn't match [settings.gradle.kts, build.gradle.kts] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/buildOutputCleanup/cache.properties didn't match [settings.gradle.kts, build.gradle.kts] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/buildOutputCleanup/outputFiles.bin didn't match [settings.gradle.kts, build.gradle.kts] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/buildOutputCleanup/buildOutputCleanup.lock didn't match [settings.gradle.kts, build.gradle.kts] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/executionHistory/executionHistory.lock didn't match [settings.gradle.kts, build.gradle.kts] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/executionHistory/executionHistory.bin didn't match [settings.gradle.kts, build.gradle.kts] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/gc.properties didn't match [settings.gradle.kts, build.gradle.kts] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileChanges/last-build.bin didn't match [settings.gradle.kts, build.gradle.kts] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/dependencies-accessors/gc.properties didn't match [settings.gradle.kts, build.gradle.kts] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/dependencies-accessors/dependencies-accessors.lock didn't match [settings.gradle.kts, build.gradle.kts] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/checksums/checksums.lock didn't match [settings.gradle.kts, build.gradle.kts] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/checksums/md5-checksums.bin didn't match [settings.gradle.kts, build.gradle.kts] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/checksums/sha1-checksums.bin didn't match [settings.gradle.kts, build.gradle.kts] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileHashes/fileHashes.lock didn't match [settings.gradle.kts, build.gradle.kts] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileHashes/fileHashes.bin didn't match [settings.gradle.kts, build.gradle.kts] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileHashes/resourceHashesCache.bin didn't match [settings.gradle.kts, build.gradle.kts] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug settings.gradle.kts matched [settings.gradle.kts, build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/test/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest$Get.class didn't match [settings.gradle.kts, build.gradle.kts] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/test/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest.class didn't match [settings.gradle.kts, build.gradle.kts] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/test/com/vmware/tap/accelerators/javaserversideui/ApplicationTest.class didn't match [settings.gradle.kts, build.gradle.kts] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/main/com/vmware/tap/accelerators/javaserversideui/web/IndexController.class didn't match [settings.gradle.kts, build.gradle.kts] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/main/com/vmware/tap/accelerators/javaserversideui/Application.class didn't match [settings.gradle.kts, build.gradle.kts] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug build/resolvedMainClassName didn't match [settings.gradle.kts, build.gradle.kts] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/static/styles/bootstrap-custom.css didn't match [settings.gradle.kts, build.gradle.kts] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/templates/index.html didn't match [settings.gradle.kts, build.gradle.kts] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/application.yml didn't match [settings.gradle.kts, build.gradle.kts] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug build/libs/java-server-side-ui-0.0.1-SNAPSHOT.jar didn't match [settings.gradle.kts, build.gradle.kts] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/TEST-com.vmware.tap.accelerators.javaserversideui.web.IndexControllerTest.xml didn't match [settings.gradle.kts, build.gradle.kts] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/TEST-com.vmware.tap.accelerators.javaserversideui.ApplicationTest.xml didn't match [settings.gradle.kts, build.gradle.kts] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/TEST-com.vmware.tap.accelerators.javaserversideui.web.IndexControllerTest$Get.xml didn't match [settings.gradle.kts, build.gradle.kts] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/binary/results.bin didn't match [settings.gradle.kts, build.gradle.kts] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/binary/output.bin.idx didn't match [settings.gradle.kts, build.gradle.kts] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/binary/output.bin didn't match [settings.gradle.kts, build.gradle.kts] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug build/tmp/bootJar/MANIFEST.MF didn't match [settings.gradle.kts, build.gradle.kts] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug build/tmp/compileJava/previous-compilation-data.bin didn't match [settings.gradle.kts, build.gradle.kts] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug build/tmp/compileTestJava/previous-compilation-data.bin didn't match [settings.gradle.kts, build.gradle.kts] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/index.html didn't match [settings.gradle.kts, build.gradle.kts] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/css/base-style.css didn't match [settings.gradle.kts, build.gradle.kts] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/css/style.css didn't match [settings.gradle.kts, build.gradle.kts] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/classes/com.vmware.tap.accelerators.javaserversideui.ApplicationTest.html didn't match [settings.gradle.kts, build.gradle.kts] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/classes/com.vmware.tap.accelerators.javaserversideui.web.IndexControllerTest$Get.html didn't match [settings.gradle.kts, build.gradle.kts] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/classes/com.vmware.tap.accelerators.javaserversideui.web.IndexControllerTest.html didn't match [settings.gradle.kts, build.gradle.kts] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/js/report.js didn't match [settings.gradle.kts, build.gradle.kts] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/packages/com.vmware.tap.accelerators.javaserversideui.web.html didn't match [settings.gradle.kts, build.gradle.kts] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/packages/com.vmware.tap.accelerators.javaserversideui.html didn't match [settings.gradle.kts, build.gradle.kts] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/jarRepositories.xml didn't match [settings.gradle.kts, build.gradle.kts] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/gradle.xml didn't match [settings.gradle.kts, build.gradle.kts] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/vcs.xml didn't match [settings.gradle.kts, build.gradle.kts] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/.gitignore didn't match [settings.gradle.kts, build.gradle.kts] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/workspace.xml didn't match [settings.gradle.kts, build.gradle.kts] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/misc.xml didn't match [settings.gradle.kts, build.gradle.kts] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/compiler.xml didn't match [settings.gradle.kts, build.gradle.kts] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest.java didn't match [settings.gradle.kts, build.gradle.kts] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/com/vmware/tap/accelerators/javaserversideui/ApplicationTest.java didn't match [settings.gradle.kts, build.gradle.kts] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/styles/bootstrap-custom.css didn't match [settings.gradle.kts, build.gradle.kts] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/index.html didn't match [settings.gradle.kts, build.gradle.kts] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/application.yml didn't match [settings.gradle.kts, build.gradle.kts] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vmware/tap/accelerators/javaserversideui/Application.java didn't match [settings.gradle.kts, build.gradle.kts] -> included
┃ ┃ ┃ ┃ ┃ ┗ Debug src/main/java/com/vmware/tap/accelerators/javaserversideui/web/IndexController.java didn't match [settings.gradle.kts, build.gradle.kts] -> included
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[0].delegate.transformations[1] (Merge)
┃ ┃ ┃ ┃ ┃ ┃  Info Running Merge(Combo, Combo, Combo)
┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[0].delegate.transformations[1].sources[0] (Combo)
┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Combo running as Chain
┃ ┃ ┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.delegate.in.transformations[0].delegate.transformations[1].sources[0].delegate (Chain)
┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Running Chain(Include, Exclude)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[0].delegate.transformations[1].sources[0].delegate.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Will include [**]
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug LICENSE matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .tanzuignore matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug config/workload.yaml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/test-classes/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest$Get.class matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/test-classes/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest.class matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/test-classes/com/vmware/tap/accelerators/javaserversideui/ApplicationTest.class matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/static/styles/bootstrap-custom.css matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/templates/index.html matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/application.yml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/com/vmware/tap/accelerators/javaserversideui/web/IndexController.class matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/com/vmware/tap/accelerators/javaserversideui/Application.class matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/maven-status/maven-compiler-plugin/testCompile/default-testCompile/inputFiles.lst matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/maven-status/maven-compiler-plugin/testCompile/default-testCompile/createdFiles.lst matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/maven-status/maven-compiler-plugin/compile/default-compile/inputFiles.lst matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/maven-status/maven-compiler-plugin/compile/default-compile/createdFiles.lst matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug pom.xml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .grype.yaml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug README.md matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradle/wrapper/gradle-wrapper.jar matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradle/wrapper/gradle-wrapper.properties matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradlew matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gitignore matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/file-system.probe matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/vcs-1/gc.properties matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/buildOutputCleanup/cache.properties matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/buildOutputCleanup/outputFiles.bin matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/buildOutputCleanup/buildOutputCleanup.lock matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/executionHistory/executionHistory.lock matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/executionHistory/executionHistory.bin matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/gc.properties matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileChanges/last-build.bin matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/dependencies-accessors/gc.properties matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/dependencies-accessors/dependencies-accessors.lock matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/checksums/checksums.lock matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/checksums/md5-checksums.bin matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/checksums/sha1-checksums.bin matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileHashes/fileHashes.lock matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileHashes/fileHashes.bin matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileHashes/resourceHashesCache.bin matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/test/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest$Get.class matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/test/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest.class matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/test/com/vmware/tap/accelerators/javaserversideui/ApplicationTest.class matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/main/com/vmware/tap/accelerators/javaserversideui/web/IndexController.class matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/main/com/vmware/tap/accelerators/javaserversideui/Application.class matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resolvedMainClassName matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/static/styles/bootstrap-custom.css matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/templates/index.html matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/application.yml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/libs/java-server-side-ui-0.0.1-SNAPSHOT.jar matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/TEST-com.vmware.tap.accelerators.javaserversideui.web.IndexControllerTest.xml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/TEST-com.vmware.tap.accelerators.javaserversideui.ApplicationTest.xml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/TEST-com.vmware.tap.accelerators.javaserversideui.web.IndexControllerTest$Get.xml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/binary/results.bin matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/binary/output.bin.idx matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/binary/output.bin matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/tmp/bootJar/MANIFEST.MF matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/tmp/compileJava/previous-compilation-data.bin matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/tmp/compileTestJava/previous-compilation-data.bin matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/index.html matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/css/base-style.css matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/css/style.css matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/classes/com.vmware.tap.accelerators.javaserversideui.ApplicationTest.html matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/classes/com.vmware.tap.accelerators.javaserversideui.web.IndexControllerTest$Get.html matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/classes/com.vmware.tap.accelerators.javaserversideui.web.IndexControllerTest.html matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/js/report.js matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/packages/com.vmware.tap.accelerators.javaserversideui.web.html matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/packages/com.vmware.tap.accelerators.javaserversideui.html matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/jarRepositories.xml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/gradle.xml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/vcs.xml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/.gitignore matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/workspace.xml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/misc.xml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/compiler.xml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/com/vmware/tap/accelerators/javaserversideui/ApplicationTest.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/styles/bootstrap-custom.css matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/index.html matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/application.yml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vmware/tap/accelerators/javaserversideui/Application.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ Debug src/main/java/com/vmware/tap/accelerators/javaserversideui/web/IndexController.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[0].delegate.transformations[1].sources[0].delegate.transformations[1] (Exclude)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Will exclude [pom.xml, README.md]
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug LICENSE didn't match [pom.xml, README.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .tanzuignore didn't match [pom.xml, README.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug config/workload.yaml didn't match [pom.xml, README.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/test-classes/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest$Get.class didn't match [pom.xml, README.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/test-classes/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest.class didn't match [pom.xml, README.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/test-classes/com/vmware/tap/accelerators/javaserversideui/ApplicationTest.class didn't match [pom.xml, README.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/static/styles/bootstrap-custom.css didn't match [pom.xml, README.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/templates/index.html didn't match [pom.xml, README.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/application.yml didn't match [pom.xml, README.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/com/vmware/tap/accelerators/javaserversideui/web/IndexController.class didn't match [pom.xml, README.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/com/vmware/tap/accelerators/javaserversideui/Application.class didn't match [pom.xml, README.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/maven-status/maven-compiler-plugin/testCompile/default-testCompile/inputFiles.lst didn't match [pom.xml, README.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/maven-status/maven-compiler-plugin/testCompile/default-testCompile/createdFiles.lst didn't match [pom.xml, README.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/maven-status/maven-compiler-plugin/compile/default-compile/inputFiles.lst didn't match [pom.xml, README.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/maven-status/maven-compiler-plugin/compile/default-compile/createdFiles.lst didn't match [pom.xml, README.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml didn't match [pom.xml, README.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug pom.xml matched [pom.xml, README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .grype.yaml didn't match [pom.xml, README.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug README.md matched [pom.xml, README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradle/wrapper/gradle-wrapper.jar didn't match [pom.xml, README.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradle/wrapper/gradle-wrapper.properties didn't match [pom.xml, README.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradlew didn't match [pom.xml, README.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gitignore didn't match [pom.xml, README.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/file-system.probe didn't match [pom.xml, README.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/vcs-1/gc.properties didn't match [pom.xml, README.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/buildOutputCleanup/cache.properties didn't match [pom.xml, README.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/buildOutputCleanup/outputFiles.bin didn't match [pom.xml, README.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/buildOutputCleanup/buildOutputCleanup.lock didn't match [pom.xml, README.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/executionHistory/executionHistory.lock didn't match [pom.xml, README.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/executionHistory/executionHistory.bin didn't match [pom.xml, README.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/gc.properties didn't match [pom.xml, README.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileChanges/last-build.bin didn't match [pom.xml, README.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/dependencies-accessors/gc.properties didn't match [pom.xml, README.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/dependencies-accessors/dependencies-accessors.lock didn't match [pom.xml, README.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/checksums/checksums.lock didn't match [pom.xml, README.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/checksums/md5-checksums.bin didn't match [pom.xml, README.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/checksums/sha1-checksums.bin didn't match [pom.xml, README.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileHashes/fileHashes.lock didn't match [pom.xml, README.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileHashes/fileHashes.bin didn't match [pom.xml, README.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileHashes/resourceHashesCache.bin didn't match [pom.xml, README.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/test/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest$Get.class didn't match [pom.xml, README.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/test/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest.class didn't match [pom.xml, README.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/test/com/vmware/tap/accelerators/javaserversideui/ApplicationTest.class didn't match [pom.xml, README.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/main/com/vmware/tap/accelerators/javaserversideui/web/IndexController.class didn't match [pom.xml, README.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/main/com/vmware/tap/accelerators/javaserversideui/Application.class didn't match [pom.xml, README.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resolvedMainClassName didn't match [pom.xml, README.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/static/styles/bootstrap-custom.css didn't match [pom.xml, README.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/templates/index.html didn't match [pom.xml, README.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/application.yml didn't match [pom.xml, README.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/libs/java-server-side-ui-0.0.1-SNAPSHOT.jar didn't match [pom.xml, README.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/TEST-com.vmware.tap.accelerators.javaserversideui.web.IndexControllerTest.xml didn't match [pom.xml, README.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/TEST-com.vmware.tap.accelerators.javaserversideui.ApplicationTest.xml didn't match [pom.xml, README.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/TEST-com.vmware.tap.accelerators.javaserversideui.web.IndexControllerTest$Get.xml didn't match [pom.xml, README.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/binary/results.bin didn't match [pom.xml, README.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/binary/output.bin.idx didn't match [pom.xml, README.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/binary/output.bin didn't match [pom.xml, README.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/tmp/bootJar/MANIFEST.MF didn't match [pom.xml, README.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/tmp/compileJava/previous-compilation-data.bin didn't match [pom.xml, README.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/tmp/compileTestJava/previous-compilation-data.bin didn't match [pom.xml, README.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/index.html didn't match [pom.xml, README.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/css/base-style.css didn't match [pom.xml, README.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/css/style.css didn't match [pom.xml, README.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/classes/com.vmware.tap.accelerators.javaserversideui.ApplicationTest.html didn't match [pom.xml, README.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/classes/com.vmware.tap.accelerators.javaserversideui.web.IndexControllerTest$Get.html didn't match [pom.xml, README.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/classes/com.vmware.tap.accelerators.javaserversideui.web.IndexControllerTest.html didn't match [pom.xml, README.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/js/report.js didn't match [pom.xml, README.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/packages/com.vmware.tap.accelerators.javaserversideui.web.html didn't match [pom.xml, README.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/packages/com.vmware.tap.accelerators.javaserversideui.html didn't match [pom.xml, README.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/jarRepositories.xml didn't match [pom.xml, README.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/gradle.xml didn't match [pom.xml, README.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/vcs.xml didn't match [pom.xml, README.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/.gitignore didn't match [pom.xml, README.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/workspace.xml didn't match [pom.xml, README.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/misc.xml didn't match [pom.xml, README.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/compiler.xml didn't match [pom.xml, README.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest.java didn't match [pom.xml, README.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/com/vmware/tap/accelerators/javaserversideui/ApplicationTest.java didn't match [pom.xml, README.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/styles/bootstrap-custom.css didn't match [pom.xml, README.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/index.html didn't match [pom.xml, README.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/application.yml didn't match [pom.xml, README.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vmware/tap/accelerators/javaserversideui/Application.java didn't match [pom.xml, README.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┗ ┗ Debug src/main/java/com/vmware/tap/accelerators/javaserversideui/web/IndexController.java didn't match [pom.xml, README.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[0].delegate.transformations[1].sources[1] (Combo)
┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Combo running as Chain
┃ ┃ ┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.delegate.in.transformations[0].delegate.transformations[1].sources[1].delegate (Chain)
┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Running Chain(Include, ReplaceText)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[0].delegate.transformations[1].sources[1].delegate.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Will include [pom.xml]
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug LICENSE didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .tanzuignore didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug config/workload.yaml didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/test-classes/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest$Get.class didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/test-classes/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest.class didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/test-classes/com/vmware/tap/accelerators/javaserversideui/ApplicationTest.class didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/static/styles/bootstrap-custom.css didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/templates/index.html didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/application.yml didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/com/vmware/tap/accelerators/javaserversideui/web/IndexController.class didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/com/vmware/tap/accelerators/javaserversideui/Application.class didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/maven-status/maven-compiler-plugin/testCompile/default-testCompile/inputFiles.lst didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/maven-status/maven-compiler-plugin/testCompile/default-testCompile/createdFiles.lst didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/maven-status/maven-compiler-plugin/compile/default-compile/inputFiles.lst didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/maven-status/maven-compiler-plugin/compile/default-compile/createdFiles.lst didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug pom.xml matched [pom.xml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .grype.yaml didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradle/wrapper/gradle-wrapper.jar didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradle/wrapper/gradle-wrapper.properties didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradlew didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gitignore didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/file-system.probe didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/vcs-1/gc.properties didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/buildOutputCleanup/cache.properties didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/buildOutputCleanup/outputFiles.bin didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/buildOutputCleanup/buildOutputCleanup.lock didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/executionHistory/executionHistory.lock didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/executionHistory/executionHistory.bin didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/gc.properties didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileChanges/last-build.bin didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/dependencies-accessors/gc.properties didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/dependencies-accessors/dependencies-accessors.lock didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/checksums/checksums.lock didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/checksums/md5-checksums.bin didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/checksums/sha1-checksums.bin didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileHashes/fileHashes.lock didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileHashes/fileHashes.bin didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileHashes/resourceHashesCache.bin didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/test/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest$Get.class didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/test/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest.class didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/test/com/vmware/tap/accelerators/javaserversideui/ApplicationTest.class didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/main/com/vmware/tap/accelerators/javaserversideui/web/IndexController.class didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/main/com/vmware/tap/accelerators/javaserversideui/Application.class didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resolvedMainClassName didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/static/styles/bootstrap-custom.css didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/templates/index.html didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/application.yml didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/libs/java-server-side-ui-0.0.1-SNAPSHOT.jar didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/TEST-com.vmware.tap.accelerators.javaserversideui.web.IndexControllerTest.xml didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/TEST-com.vmware.tap.accelerators.javaserversideui.ApplicationTest.xml didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/TEST-com.vmware.tap.accelerators.javaserversideui.web.IndexControllerTest$Get.xml didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/binary/results.bin didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/binary/output.bin.idx didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/binary/output.bin didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/tmp/bootJar/MANIFEST.MF didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/tmp/compileJava/previous-compilation-data.bin didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/tmp/compileTestJava/previous-compilation-data.bin didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/index.html didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/css/base-style.css didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/css/style.css didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/classes/com.vmware.tap.accelerators.javaserversideui.ApplicationTest.html didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/classes/com.vmware.tap.accelerators.javaserversideui.web.IndexControllerTest$Get.html didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/classes/com.vmware.tap.accelerators.javaserversideui.web.IndexControllerTest.html didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/js/report.js didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/packages/com.vmware.tap.accelerators.javaserversideui.web.html didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/packages/com.vmware.tap.accelerators.javaserversideui.html didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/jarRepositories.xml didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/gradle.xml didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/vcs.xml didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/.gitignore didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/workspace.xml didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/misc.xml didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/compiler.xml didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/com/vmware/tap/accelerators/javaserversideui/ApplicationTest.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/styles/bootstrap-custom.css didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/index.html didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/application.yml didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vmware/tap/accelerators/javaserversideui/Application.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ Debug src/main/java/com/vmware/tap/accelerators/javaserversideui/web/IndexController.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[0].delegate.transformations[1].sources[1].delegate.transformations[1] (ReplaceText)
┃ ┃ ┃ ┃ ┃ ┃ ┗ ┗  Info Will replace [<groupId>com.vmware.tap.accelerators</groupId>-><groupId>com.example...(truncated)]
┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[0].delegate.transformations[1].sources[2] (Combo)
┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Combo running as Chain
┃ ┃ ┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.delegate.in.transformations[0].delegate.transformations[1].sources[2].delegate (Chain)
┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Running Chain(Include, ReplaceText, ReplaceText)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[0].delegate.transformations[1].sources[2].delegate.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Will include [README.md]
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug LICENSE didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .tanzuignore didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug config/workload.yaml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/test-classes/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest$Get.class didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/test-classes/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest.class didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/test-classes/com/vmware/tap/accelerators/javaserversideui/ApplicationTest.class didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/static/styles/bootstrap-custom.css didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/templates/index.html didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/application.yml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/com/vmware/tap/accelerators/javaserversideui/web/IndexController.class didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/com/vmware/tap/accelerators/javaserversideui/Application.class didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/maven-status/maven-compiler-plugin/testCompile/default-testCompile/inputFiles.lst didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/maven-status/maven-compiler-plugin/testCompile/default-testCompile/createdFiles.lst didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/maven-status/maven-compiler-plugin/compile/default-compile/inputFiles.lst didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/maven-status/maven-compiler-plugin/compile/default-compile/createdFiles.lst didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug pom.xml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .grype.yaml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug README.md matched [README.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradle/wrapper/gradle-wrapper.jar didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradle/wrapper/gradle-wrapper.properties didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradlew didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gitignore didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/file-system.probe didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/vcs-1/gc.properties didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/buildOutputCleanup/cache.properties didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/buildOutputCleanup/outputFiles.bin didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/buildOutputCleanup/buildOutputCleanup.lock didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/executionHistory/executionHistory.lock didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/executionHistory/executionHistory.bin didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/gc.properties didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileChanges/last-build.bin didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/dependencies-accessors/gc.properties didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/dependencies-accessors/dependencies-accessors.lock didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/checksums/checksums.lock didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/checksums/md5-checksums.bin didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/checksums/sha1-checksums.bin didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileHashes/fileHashes.lock didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileHashes/fileHashes.bin didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileHashes/resourceHashesCache.bin didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/test/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest$Get.class didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/test/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest.class didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/test/com/vmware/tap/accelerators/javaserversideui/ApplicationTest.class didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/main/com/vmware/tap/accelerators/javaserversideui/web/IndexController.class didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/main/com/vmware/tap/accelerators/javaserversideui/Application.class didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resolvedMainClassName didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/static/styles/bootstrap-custom.css didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/templates/index.html didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/application.yml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/libs/java-server-side-ui-0.0.1-SNAPSHOT.jar didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/TEST-com.vmware.tap.accelerators.javaserversideui.web.IndexControllerTest.xml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/TEST-com.vmware.tap.accelerators.javaserversideui.ApplicationTest.xml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/TEST-com.vmware.tap.accelerators.javaserversideui.web.IndexControllerTest$Get.xml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/binary/results.bin didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/binary/output.bin.idx didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/binary/output.bin didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/tmp/bootJar/MANIFEST.MF didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/tmp/compileJava/previous-compilation-data.bin didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/tmp/compileTestJava/previous-compilation-data.bin didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/index.html didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/css/base-style.css didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/css/style.css didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/classes/com.vmware.tap.accelerators.javaserversideui.ApplicationTest.html didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/classes/com.vmware.tap.accelerators.javaserversideui.web.IndexControllerTest$Get.html didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/classes/com.vmware.tap.accelerators.javaserversideui.web.IndexControllerTest.html didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/js/report.js didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/packages/com.vmware.tap.accelerators.javaserversideui.web.html didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/packages/com.vmware.tap.accelerators.javaserversideui.html didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/jarRepositories.xml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/gradle.xml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/vcs.xml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/.gitignore didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/workspace.xml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/misc.xml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/compiler.xml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest.java didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/com/vmware/tap/accelerators/javaserversideui/ApplicationTest.java didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/styles/bootstrap-custom.css didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/index.html didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/application.yml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vmware/tap/accelerators/javaserversideui/Application.java didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ Debug src/main/java/com/vmware/tap/accelerators/javaserversideui/web/IndexController.java didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[0].delegate.transformations[1].sources[2].delegate.transformations[1] (ReplaceText)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗  Info Will replace regex '--- StartGradle[\s\S]+?--- EndGradle' with ''
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[0].delegate.transformations[1].sources[2].delegate.transformations[2] (ReplaceText)
┃ ┃ ┃ ┃ ┃ ┗ ┗ ┗  Info Will replace regex '--- StartMaven\s|--- EndMaven\s' with ''
┃ ┃ ┃ ┃ ┗ ╺ engine.transformations[0].validated.delegate.in.transformations[0].delegate.transformations[2] (UniquePath)
┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[1] (Combo)
┃ ┃ ┃ ┃ ┃  Info Condition (#buildTool == 'gradle') evaluated to false
┃ ┃ ┃ ┃ ┗ null ()
┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[2] (Combo)
┃ ┃ ┃ ┃ ┃  Info Combo running as Chain
┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.delegate.in.transformations[2].delegate (Chain)
┃ ┃ ┃ ┃ ┃  Info Running Chain(Merge, UniquePath)
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[2].delegate.transformations[0] (Merge)
┃ ┃ ┃ ┃ ┃ ┃  Info Running Merge(Combo, Combo)
┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[2].delegate.transformations[0].sources[0] (Combo)
┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Combo running as Chain
┃ ┃ ┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.delegate.in.transformations[2].delegate.transformations[0].sources[0].delegate (Chain)
┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Running Chain(Include, Exclude)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[2].delegate.transformations[0].sources[0].delegate.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Will include [**]
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vmware/tap/accelerators/javaserversideui/web/IndexController.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/packages/com.vmware.tap.accelerators.javaserversideui.web.html matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/css/base-style.css matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/buildOutputCleanup/buildOutputCleanup.lock matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/binary/output.bin.idx matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/tmp/bootJar/MANIFEST.MF matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/executionHistory/executionHistory.lock matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/misc.xml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/js/report.js matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/templates/index.html matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/maven-status/maven-compiler-plugin/compile/default-compile/createdFiles.lst matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/styles/bootstrap-custom.css matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/workspace.xml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/gradle.xml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/libs/java-server-side-ui-0.0.1-SNAPSHOT.jar matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/main/com/vmware/tap/accelerators/javaserversideui/web/IndexController.class matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/TEST-com.vmware.tap.accelerators.javaserversideui.web.IndexControllerTest.xml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/buildOutputCleanup/cache.properties matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug LICENSE matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/file-system.probe matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/maven-status/maven-compiler-plugin/compile/default-compile/inputFiles.lst matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradlew matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/jarRepositories.xml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/binary/results.bin matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/templates/index.html matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/.gitignore matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/checksums/sha1-checksums.bin matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug README.md matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/TEST-com.vmware.tap.accelerators.javaserversideui.ApplicationTest.xml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/compiler.xml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileHashes/fileHashes.lock matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/com/vmware/tap/accelerators/javaserversideui/ApplicationTest.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/test-classes/com/vmware/tap/accelerators/javaserversideui/ApplicationTest.class matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/test/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest$Get.class matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gitignore matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/vcs-1/gc.properties matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/com/vmware/tap/accelerators/javaserversideui/web/IndexController.class matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradle/wrapper/gradle-wrapper.jar matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/main/com/vmware/tap/accelerators/javaserversideui/Application.class matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/TEST-com.vmware.tap.accelerators.javaserversideui.web.IndexControllerTest$Get.xml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileChanges/last-build.bin matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradle/wrapper/gradle-wrapper.properties matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/css/style.css matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug pom.xml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/classes/com.vmware.tap.accelerators.javaserversideui.web.IndexControllerTest.html matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/vcs.xml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/maven-status/maven-compiler-plugin/testCompile/default-testCompile/createdFiles.lst matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/static/styles/bootstrap-custom.css matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/test/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest.class matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/test-classes/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest$Get.class matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/test/com/vmware/tap/accelerators/javaserversideui/ApplicationTest.class matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/dependencies-accessors/gc.properties matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .tanzuignore matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/packages/com.vmware.tap.accelerators.javaserversideui.html matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/static/styles/bootstrap-custom.css matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .grype.yaml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/tmp/compileTestJava/previous-compilation-data.bin matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/application.yml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/index.html matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/maven-status/maven-compiler-plugin/testCompile/default-testCompile/inputFiles.lst matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/com/vmware/tap/accelerators/javaserversideui/Application.class matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/tmp/compileJava/previous-compilation-data.bin matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileHashes/resourceHashesCache.bin matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/classes/com.vmware.tap.accelerators.javaserversideui.web.IndexControllerTest$Get.html matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/buildOutputCleanup/outputFiles.bin matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/test-classes/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest.class matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/binary/output.bin matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/executionHistory/executionHistory.bin matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileHashes/fileHashes.bin matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/checksums/md5-checksums.bin matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/classes/com.vmware.tap.accelerators.javaserversideui.ApplicationTest.html matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/checksums/checksums.lock matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug config/workload.yaml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/gc.properties matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/application.yml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resolvedMainClassName matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/index.html matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vmware/tap/accelerators/javaserversideui/Application.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/dependencies-accessors/dependencies-accessors.lock matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ Debug src/main/resources/application.yml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[2].delegate.transformations[0].sources[0].delegate.transformations[1] (Exclude)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Will exclude [config/workload.yaml]
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vmware/tap/accelerators/javaserversideui/web/IndexController.java didn't match [config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/packages/com.vmware.tap.accelerators.javaserversideui.web.html didn't match [config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest.java didn't match [config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/css/base-style.css didn't match [config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/buildOutputCleanup/buildOutputCleanup.lock didn't match [config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/binary/output.bin.idx didn't match [config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/tmp/bootJar/MANIFEST.MF didn't match [config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/executionHistory/executionHistory.lock didn't match [config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/misc.xml didn't match [config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/js/report.js didn't match [config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/templates/index.html didn't match [config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/maven-status/maven-compiler-plugin/compile/default-compile/createdFiles.lst didn't match [config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/styles/bootstrap-custom.css didn't match [config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/workspace.xml didn't match [config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/gradle.xml didn't match [config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/libs/java-server-side-ui-0.0.1-SNAPSHOT.jar didn't match [config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/main/com/vmware/tap/accelerators/javaserversideui/web/IndexController.class didn't match [config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/TEST-com.vmware.tap.accelerators.javaserversideui.web.IndexControllerTest.xml didn't match [config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/buildOutputCleanup/cache.properties didn't match [config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug LICENSE didn't match [config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/file-system.probe didn't match [config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/maven-status/maven-compiler-plugin/compile/default-compile/inputFiles.lst didn't match [config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradlew didn't match [config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/jarRepositories.xml didn't match [config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/binary/results.bin didn't match [config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/templates/index.html didn't match [config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/.gitignore didn't match [config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/checksums/sha1-checksums.bin didn't match [config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/TEST-com.vmware.tap.accelerators.javaserversideui.ApplicationTest.xml didn't match [config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/compiler.xml didn't match [config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileHashes/fileHashes.lock didn't match [config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/com/vmware/tap/accelerators/javaserversideui/ApplicationTest.java didn't match [config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/test-classes/com/vmware/tap/accelerators/javaserversideui/ApplicationTest.class didn't match [config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/test/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest$Get.class didn't match [config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gitignore didn't match [config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/vcs-1/gc.properties didn't match [config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/com/vmware/tap/accelerators/javaserversideui/web/IndexController.class didn't match [config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradle/wrapper/gradle-wrapper.jar didn't match [config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/main/com/vmware/tap/accelerators/javaserversideui/Application.class didn't match [config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/TEST-com.vmware.tap.accelerators.javaserversideui.web.IndexControllerTest$Get.xml didn't match [config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileChanges/last-build.bin didn't match [config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradle/wrapper/gradle-wrapper.properties didn't match [config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/css/style.css didn't match [config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug pom.xml didn't match [config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/classes/com.vmware.tap.accelerators.javaserversideui.web.IndexControllerTest.html didn't match [config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/vcs.xml didn't match [config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/maven-status/maven-compiler-plugin/testCompile/default-testCompile/createdFiles.lst didn't match [config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/static/styles/bootstrap-custom.css didn't match [config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/test/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest.class didn't match [config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/test-classes/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest$Get.class didn't match [config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/test/com/vmware/tap/accelerators/javaserversideui/ApplicationTest.class didn't match [config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/dependencies-accessors/gc.properties didn't match [config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .tanzuignore didn't match [config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/packages/com.vmware.tap.accelerators.javaserversideui.html didn't match [config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/static/styles/bootstrap-custom.css didn't match [config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .grype.yaml didn't match [config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/tmp/compileTestJava/previous-compilation-data.bin didn't match [config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/application.yml didn't match [config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/index.html didn't match [config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/maven-status/maven-compiler-plugin/testCompile/default-testCompile/inputFiles.lst didn't match [config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/com/vmware/tap/accelerators/javaserversideui/Application.class didn't match [config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/tmp/compileJava/previous-compilation-data.bin didn't match [config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileHashes/resourceHashesCache.bin didn't match [config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/classes/com.vmware.tap.accelerators.javaserversideui.web.IndexControllerTest$Get.html didn't match [config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/buildOutputCleanup/outputFiles.bin didn't match [config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/test-classes/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest.class didn't match [config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/binary/output.bin didn't match [config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/executionHistory/executionHistory.bin didn't match [config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileHashes/fileHashes.bin didn't match [config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/checksums/md5-checksums.bin didn't match [config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml didn't match [config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/classes/com.vmware.tap.accelerators.javaserversideui.ApplicationTest.html didn't match [config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/checksums/checksums.lock didn't match [config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug config/workload.yaml matched [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/gc.properties didn't match [config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/application.yml didn't match [config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resolvedMainClassName didn't match [config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/index.html didn't match [config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vmware/tap/accelerators/javaserversideui/Application.java didn't match [config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/dependencies-accessors/dependencies-accessors.lock didn't match [config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┗ ┗ Debug src/main/resources/application.yml didn't match [config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[2].delegate.transformations[0].sources[1] (Combo)
┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Combo running as Chain
┃ ┃ ┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.delegate.in.transformations[2].delegate.transformations[0].sources[1].delegate (Chain)
┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Running Chain(Include, ReplaceText)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[2].delegate.transformations[0].sources[1].delegate.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Will include [config/workload.yaml]
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vmware/tap/accelerators/javaserversideui/web/IndexController.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/packages/com.vmware.tap.accelerators.javaserversideui.web.html didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/css/base-style.css didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/buildOutputCleanup/buildOutputCleanup.lock didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/binary/output.bin.idx didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/tmp/bootJar/MANIFEST.MF didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/executionHistory/executionHistory.lock didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/misc.xml didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/js/report.js didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/templates/index.html didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/maven-status/maven-compiler-plugin/compile/default-compile/createdFiles.lst didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/styles/bootstrap-custom.css didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/workspace.xml didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/gradle.xml didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/libs/java-server-side-ui-0.0.1-SNAPSHOT.jar didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/main/com/vmware/tap/accelerators/javaserversideui/web/IndexController.class didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/TEST-com.vmware.tap.accelerators.javaserversideui.web.IndexControllerTest.xml didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/buildOutputCleanup/cache.properties didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug LICENSE didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/file-system.probe didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/maven-status/maven-compiler-plugin/compile/default-compile/inputFiles.lst didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradlew didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/jarRepositories.xml didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/binary/results.bin didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/templates/index.html didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/.gitignore didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/checksums/sha1-checksums.bin didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/TEST-com.vmware.tap.accelerators.javaserversideui.ApplicationTest.xml didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/compiler.xml didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileHashes/fileHashes.lock didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/com/vmware/tap/accelerators/javaserversideui/ApplicationTest.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/test-classes/com/vmware/tap/accelerators/javaserversideui/ApplicationTest.class didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/test/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest$Get.class didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gitignore didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/vcs-1/gc.properties didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/com/vmware/tap/accelerators/javaserversideui/web/IndexController.class didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradle/wrapper/gradle-wrapper.jar didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/main/com/vmware/tap/accelerators/javaserversideui/Application.class didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/TEST-com.vmware.tap.accelerators.javaserversideui.web.IndexControllerTest$Get.xml didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileChanges/last-build.bin didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradle/wrapper/gradle-wrapper.properties didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/css/style.css didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug pom.xml didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/classes/com.vmware.tap.accelerators.javaserversideui.web.IndexControllerTest.html didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/vcs.xml didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/maven-status/maven-compiler-plugin/testCompile/default-testCompile/createdFiles.lst didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/static/styles/bootstrap-custom.css didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/test/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest.class didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/test-classes/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest$Get.class didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/test/com/vmware/tap/accelerators/javaserversideui/ApplicationTest.class didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/dependencies-accessors/gc.properties didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .tanzuignore didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/packages/com.vmware.tap.accelerators.javaserversideui.html didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/static/styles/bootstrap-custom.css didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .grype.yaml didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/tmp/compileTestJava/previous-compilation-data.bin didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/application.yml didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/index.html didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/maven-status/maven-compiler-plugin/testCompile/default-testCompile/inputFiles.lst didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/com/vmware/tap/accelerators/javaserversideui/Application.class didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/tmp/compileJava/previous-compilation-data.bin didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileHashes/resourceHashesCache.bin didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/classes/com.vmware.tap.accelerators.javaserversideui.web.IndexControllerTest$Get.html didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/buildOutputCleanup/outputFiles.bin didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/test-classes/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest.class didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/binary/output.bin didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/executionHistory/executionHistory.bin didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileHashes/fileHashes.bin didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/checksums/md5-checksums.bin didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/classes/com.vmware.tap.accelerators.javaserversideui.ApplicationTest.html didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/checksums/checksums.lock didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug config/workload.yaml matched [config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/gc.properties didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/application.yml didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resolvedMainClassName didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/index.html didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vmware/tap/accelerators/javaserversideui/Application.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/dependencies-accessors/dependencies-accessors.lock didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ Debug src/main/resources/application.yml didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[2].delegate.transformations[0].sources[1].delegate.transformations[1] (ReplaceText)
┃ ┃ ┃ ┃ ┃ ┗ ┗ ┗  Info Will replace [java-server-side-ui->server-side-ui-start...(truncated)]
┃ ┃ ┃ ┃ ┗ ╺ engine.transformations[0].validated.delegate.in.transformations[2].delegate.transformations[1] (UniquePath)
┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[3] (Combo)
┃ ┃ ┃ ┃ ┃  Info Combo running as Chain
┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.delegate.in.transformations[3].delegate (Chain)
┃ ┃ ┃ ┃ ┃  Info Running Chain(Merge, UniquePath)
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[3].delegate.transformations[0] (Merge)
┃ ┃ ┃ ┃ ┃ ┃  Info Running Merge(InvokeFragment, Combo)
┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[3].delegate.transformations[0].sources[0] (InvokeFragment)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[3].delegate.transformations[0].sources[0].validated (Combo)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Combo running as Let
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.delegate.in.transformations[3].delegate.transformations[0].sources[0].validated.delegate (Let)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug Adding symbol workloadJavaVersion with value '17'
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[3].delegate.transformations[0].sources[0].validated.delegate.in (Chain)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Running Chain(Merge, UniquePath)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[3].delegate.transformations[0].sources[0].validated.delegate.in.transformations[0] (Merge)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Running Merge(Combo, Combo, Combo, Combo, Combo)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[3].delegate.transformations[0].sources[0].validated.delegate.in.transformations[0].sources[0] (Combo)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Combo running as Chain
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.delegate.in.transformations[3].delegate.transformations[0].sources[0].validated.delegate.in.transformations[0].sources[0].delegate (Chain)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Running Chain(Include, ReplaceText)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[3].delegate.transformations[0].sources[0].validated.delegate.in.transformations[0].sources[0].delegate.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Will include [pom.xml]
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vmware/tap/accelerators/javaserversideui/web/IndexController.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/packages/com.vmware.tap.accelerators.javaserversideui.web.html didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/buildOutputCleanup/buildOutputCleanup.lock didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/css/base-style.css didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/binary/output.bin.idx didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/tmp/bootJar/MANIFEST.MF didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/executionHistory/executionHistory.lock didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/js/report.js didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/misc.xml didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/templates/index.html didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/maven-status/maven-compiler-plugin/compile/default-compile/createdFiles.lst didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/workspace.xml didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/styles/bootstrap-custom.css didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/main/com/vmware/tap/accelerators/javaserversideui/web/IndexController.class didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/libs/java-server-side-ui-0.0.1-SNAPSHOT.jar didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/gradle.xml didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/buildOutputCleanup/cache.properties didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/TEST-com.vmware.tap.accelerators.javaserversideui.web.IndexControllerTest.xml didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug LICENSE didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/file-system.probe didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/maven-status/maven-compiler-plugin/compile/default-compile/inputFiles.lst didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradlew didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/binary/results.bin didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/jarRepositories.xml didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/templates/index.html didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/.gitignore didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/checksums/sha1-checksums.bin didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/TEST-com.vmware.tap.accelerators.javaserversideui.ApplicationTest.xml didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileHashes/fileHashes.lock didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/compiler.xml didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/test-classes/com/vmware/tap/accelerators/javaserversideui/ApplicationTest.class didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/com/vmware/tap/accelerators/javaserversideui/ApplicationTest.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/test/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest$Get.class didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gitignore didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/com/vmware/tap/accelerators/javaserversideui/web/IndexController.class didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/vcs-1/gc.properties didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradle/wrapper/gradle-wrapper.jar didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/main/com/vmware/tap/accelerators/javaserversideui/Application.class didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradle/wrapper/gradle-wrapper.properties didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileChanges/last-build.bin didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/TEST-com.vmware.tap.accelerators.javaserversideui.web.IndexControllerTest$Get.xml didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/css/style.css didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/classes/com.vmware.tap.accelerators.javaserversideui.web.IndexControllerTest.html didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug pom.xml matched [pom.xml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/static/styles/bootstrap-custom.css didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/maven-status/maven-compiler-plugin/testCompile/default-testCompile/createdFiles.lst didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/vcs.xml didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/test-classes/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest$Get.class didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/test/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest.class didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/test/com/vmware/tap/accelerators/javaserversideui/ApplicationTest.class didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/dependencies-accessors/gc.properties didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .tanzuignore didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/static/styles/bootstrap-custom.css didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/packages/com.vmware.tap.accelerators.javaserversideui.html didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .grype.yaml didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/tmp/compileTestJava/previous-compilation-data.bin didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/application.yml didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/index.html didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/com/vmware/tap/accelerators/javaserversideui/Application.class didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/maven-status/maven-compiler-plugin/testCompile/default-testCompile/inputFiles.lst didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/tmp/compileJava/previous-compilation-data.bin didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileHashes/resourceHashesCache.bin didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/test-classes/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest.class didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/buildOutputCleanup/outputFiles.bin didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/classes/com.vmware.tap.accelerators.javaserversideui.web.IndexControllerTest$Get.html didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/executionHistory/executionHistory.bin didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/binary/output.bin didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileHashes/fileHashes.bin didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/checksums/md5-checksums.bin didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug config/workload.yaml didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/checksums/checksums.lock didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/classes/com.vmware.tap.accelerators.javaserversideui.ApplicationTest.html didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/gc.properties didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/application.yml didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resolvedMainClassName didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/index.html didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/dependencies-accessors/dependencies-accessors.lock didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vmware/tap/accelerators/javaserversideui/Application.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/application.yml didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ Debug README.md didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[3].delegate.transformations[0].sources[0].validated.delegate.in.transformations[0].sources[0].delegate.transformations[1] (ReplaceText)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ ┗  Info Will replace regex '<java.version>.*<' with '<java.version>17<'
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[3].delegate.transformations[0].sources[0].validated.delegate.in.transformations[0].sources[1] (Combo)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Combo running as Chain
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.delegate.in.transformations[3].delegate.transformations[0].sources[0].validated.delegate.in.transformations[0].sources[1].delegate (Chain)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Running Chain(Include, ReplaceText)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[3].delegate.transformations[0].sources[0].validated.delegate.in.transformations[0].sources[1].delegate.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Will include [build.gradle]
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vmware/tap/accelerators/javaserversideui/web/IndexController.java didn't match [build.gradle] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/packages/com.vmware.tap.accelerators.javaserversideui.web.html didn't match [build.gradle] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/buildOutputCleanup/buildOutputCleanup.lock didn't match [build.gradle] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/css/base-style.css didn't match [build.gradle] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest.java didn't match [build.gradle] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/binary/output.bin.idx didn't match [build.gradle] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/tmp/bootJar/MANIFEST.MF didn't match [build.gradle] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/executionHistory/executionHistory.lock didn't match [build.gradle] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/js/report.js didn't match [build.gradle] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/misc.xml didn't match [build.gradle] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/templates/index.html didn't match [build.gradle] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/maven-status/maven-compiler-plugin/compile/default-compile/createdFiles.lst didn't match [build.gradle] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/workspace.xml didn't match [build.gradle] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/styles/bootstrap-custom.css didn't match [build.gradle] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/main/com/vmware/tap/accelerators/javaserversideui/web/IndexController.class didn't match [build.gradle] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/libs/java-server-side-ui-0.0.1-SNAPSHOT.jar didn't match [build.gradle] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/gradle.xml didn't match [build.gradle] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/buildOutputCleanup/cache.properties didn't match [build.gradle] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/TEST-com.vmware.tap.accelerators.javaserversideui.web.IndexControllerTest.xml didn't match [build.gradle] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug LICENSE didn't match [build.gradle] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/file-system.probe didn't match [build.gradle] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/maven-status/maven-compiler-plugin/compile/default-compile/inputFiles.lst didn't match [build.gradle] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradlew didn't match [build.gradle] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/binary/results.bin didn't match [build.gradle] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/jarRepositories.xml didn't match [build.gradle] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/templates/index.html didn't match [build.gradle] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/.gitignore didn't match [build.gradle] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/checksums/sha1-checksums.bin didn't match [build.gradle] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [build.gradle] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/TEST-com.vmware.tap.accelerators.javaserversideui.ApplicationTest.xml didn't match [build.gradle] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileHashes/fileHashes.lock didn't match [build.gradle] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/compiler.xml didn't match [build.gradle] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/test-classes/com/vmware/tap/accelerators/javaserversideui/ApplicationTest.class didn't match [build.gradle] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/com/vmware/tap/accelerators/javaserversideui/ApplicationTest.java didn't match [build.gradle] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/test/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest$Get.class didn't match [build.gradle] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gitignore didn't match [build.gradle] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/com/vmware/tap/accelerators/javaserversideui/web/IndexController.class didn't match [build.gradle] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/vcs-1/gc.properties didn't match [build.gradle] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradle/wrapper/gradle-wrapper.jar didn't match [build.gradle] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/main/com/vmware/tap/accelerators/javaserversideui/Application.class didn't match [build.gradle] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradle/wrapper/gradle-wrapper.properties didn't match [build.gradle] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileChanges/last-build.bin didn't match [build.gradle] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/TEST-com.vmware.tap.accelerators.javaserversideui.web.IndexControllerTest$Get.xml didn't match [build.gradle] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/css/style.css didn't match [build.gradle] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/classes/com.vmware.tap.accelerators.javaserversideui.web.IndexControllerTest.html didn't match [build.gradle] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug pom.xml didn't match [build.gradle] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/static/styles/bootstrap-custom.css didn't match [build.gradle] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/maven-status/maven-compiler-plugin/testCompile/default-testCompile/createdFiles.lst didn't match [build.gradle] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/vcs.xml didn't match [build.gradle] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/test-classes/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest$Get.class didn't match [build.gradle] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/test/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest.class didn't match [build.gradle] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/test/com/vmware/tap/accelerators/javaserversideui/ApplicationTest.class didn't match [build.gradle] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/dependencies-accessors/gc.properties didn't match [build.gradle] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .tanzuignore didn't match [build.gradle] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/static/styles/bootstrap-custom.css didn't match [build.gradle] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/packages/com.vmware.tap.accelerators.javaserversideui.html didn't match [build.gradle] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .grype.yaml didn't match [build.gradle] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/tmp/compileTestJava/previous-compilation-data.bin didn't match [build.gradle] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/application.yml didn't match [build.gradle] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/index.html didn't match [build.gradle] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/com/vmware/tap/accelerators/javaserversideui/Application.class didn't match [build.gradle] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/maven-status/maven-compiler-plugin/testCompile/default-testCompile/inputFiles.lst didn't match [build.gradle] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/tmp/compileJava/previous-compilation-data.bin didn't match [build.gradle] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileHashes/resourceHashesCache.bin didn't match [build.gradle] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/test-classes/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest.class didn't match [build.gradle] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/buildOutputCleanup/outputFiles.bin didn't match [build.gradle] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/classes/com.vmware.tap.accelerators.javaserversideui.web.IndexControllerTest$Get.html didn't match [build.gradle] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/executionHistory/executionHistory.bin didn't match [build.gradle] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/binary/output.bin didn't match [build.gradle] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileHashes/fileHashes.bin didn't match [build.gradle] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml didn't match [build.gradle] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/checksums/md5-checksums.bin didn't match [build.gradle] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug config/workload.yaml didn't match [build.gradle] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/checksums/checksums.lock didn't match [build.gradle] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/classes/com.vmware.tap.accelerators.javaserversideui.ApplicationTest.html didn't match [build.gradle] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/gc.properties didn't match [build.gradle] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/application.yml didn't match [build.gradle] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resolvedMainClassName didn't match [build.gradle] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/index.html didn't match [build.gradle] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/dependencies-accessors/dependencies-accessors.lock didn't match [build.gradle] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vmware/tap/accelerators/javaserversideui/Application.java didn't match [build.gradle] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/application.yml didn't match [build.gradle] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ Debug README.md didn't match [build.gradle] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[3].delegate.transformations[0].sources[0].validated.delegate.in.transformations[0].sources[1].delegate.transformations[1] (ReplaceText)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ ┗  Info Will replace regex 'sourceCompatibility = .*' with 'sourceCompatibility ...(truncated)'
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[3].delegate.transformations[0].sources[0].validated.delegate.in.transformations[0].sources[2] (Combo)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Combo running as Chain
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.delegate.in.transformations[3].delegate.transformations[0].sources[0].validated.delegate.in.transformations[0].sources[2].delegate (Chain)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Running Chain(Include, ReplaceText)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[3].delegate.transformations[0].sources[0].validated.delegate.in.transformations[0].sources[2].delegate.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Will include [build.gradle.kts]
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vmware/tap/accelerators/javaserversideui/web/IndexController.java didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/packages/com.vmware.tap.accelerators.javaserversideui.web.html didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/buildOutputCleanup/buildOutputCleanup.lock didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/css/base-style.css didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest.java didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/binary/output.bin.idx didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/tmp/bootJar/MANIFEST.MF didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/executionHistory/executionHistory.lock didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/js/report.js didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/misc.xml didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/templates/index.html didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/maven-status/maven-compiler-plugin/compile/default-compile/createdFiles.lst didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/workspace.xml didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/styles/bootstrap-custom.css didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/main/com/vmware/tap/accelerators/javaserversideui/web/IndexController.class didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/libs/java-server-side-ui-0.0.1-SNAPSHOT.jar didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/gradle.xml didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/buildOutputCleanup/cache.properties didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/TEST-com.vmware.tap.accelerators.javaserversideui.web.IndexControllerTest.xml didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug LICENSE didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/file-system.probe didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/maven-status/maven-compiler-plugin/compile/default-compile/inputFiles.lst didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradlew didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/binary/results.bin didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/jarRepositories.xml didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/templates/index.html didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/.gitignore didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/checksums/sha1-checksums.bin didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/TEST-com.vmware.tap.accelerators.javaserversideui.ApplicationTest.xml didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileHashes/fileHashes.lock didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/compiler.xml didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/test-classes/com/vmware/tap/accelerators/javaserversideui/ApplicationTest.class didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/com/vmware/tap/accelerators/javaserversideui/ApplicationTest.java didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/test/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest$Get.class didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gitignore didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/com/vmware/tap/accelerators/javaserversideui/web/IndexController.class didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/vcs-1/gc.properties didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradle/wrapper/gradle-wrapper.jar didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/main/com/vmware/tap/accelerators/javaserversideui/Application.class didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradle/wrapper/gradle-wrapper.properties didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileChanges/last-build.bin didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/TEST-com.vmware.tap.accelerators.javaserversideui.web.IndexControllerTest$Get.xml didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/css/style.css didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/classes/com.vmware.tap.accelerators.javaserversideui.web.IndexControllerTest.html didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug pom.xml didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/static/styles/bootstrap-custom.css didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/maven-status/maven-compiler-plugin/testCompile/default-testCompile/createdFiles.lst didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/vcs.xml didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/test-classes/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest$Get.class didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/test/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest.class didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/test/com/vmware/tap/accelerators/javaserversideui/ApplicationTest.class didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/dependencies-accessors/gc.properties didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .tanzuignore didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/static/styles/bootstrap-custom.css didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/packages/com.vmware.tap.accelerators.javaserversideui.html didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .grype.yaml didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/tmp/compileTestJava/previous-compilation-data.bin didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/application.yml didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/index.html didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/com/vmware/tap/accelerators/javaserversideui/Application.class didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/maven-status/maven-compiler-plugin/testCompile/default-testCompile/inputFiles.lst didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/tmp/compileJava/previous-compilation-data.bin didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileHashes/resourceHashesCache.bin didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/test-classes/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest.class didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/buildOutputCleanup/outputFiles.bin didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/classes/com.vmware.tap.accelerators.javaserversideui.web.IndexControllerTest$Get.html didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/executionHistory/executionHistory.bin didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/binary/output.bin didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileHashes/fileHashes.bin didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/checksums/md5-checksums.bin didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug config/workload.yaml didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/checksums/checksums.lock didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/classes/com.vmware.tap.accelerators.javaserversideui.ApplicationTest.html didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/gc.properties didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/application.yml didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resolvedMainClassName didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/index.html didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/dependencies-accessors/dependencies-accessors.lock didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vmware/tap/accelerators/javaserversideui/Application.java didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/application.yml didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ Debug README.md didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[3].delegate.transformations[0].sources[0].validated.delegate.in.transformations[0].sources[2].delegate.transformations[1] (ReplaceText)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ ┗  Info Will replace regex '(?<unmodified>JavaVersion\.VERSION_)(\d+)' with '${unmodified}17'
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[3].delegate.transformations[0].sources[0].validated.delegate.in.transformations[0].sources[3] (Combo)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Combo running as Chain
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.delegate.in.transformations[3].delegate.transformations[0].sources[0].validated.delegate.in.transformations[0].sources[3].delegate (Chain)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Running Chain(Include, OpenRewriteRecipe)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[3].delegate.transformations[0].sources[0].validated.delegate.in.transformations[0].sources[3].delegate.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Will include [config/workload.yaml, config/workload-native.yaml]
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vmware/tap/accelerators/javaserversideui/web/IndexController.java didn't match [config/workload.yaml, config/workload-native.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/packages/com.vmware.tap.accelerators.javaserversideui.web.html didn't match [config/workload.yaml, config/workload-native.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/buildOutputCleanup/buildOutputCleanup.lock didn't match [config/workload.yaml, config/workload-native.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/css/base-style.css didn't match [config/workload.yaml, config/workload-native.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest.java didn't match [config/workload.yaml, config/workload-native.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/binary/output.bin.idx didn't match [config/workload.yaml, config/workload-native.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/tmp/bootJar/MANIFEST.MF didn't match [config/workload.yaml, config/workload-native.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/executionHistory/executionHistory.lock didn't match [config/workload.yaml, config/workload-native.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/js/report.js didn't match [config/workload.yaml, config/workload-native.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/misc.xml didn't match [config/workload.yaml, config/workload-native.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/templates/index.html didn't match [config/workload.yaml, config/workload-native.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/maven-status/maven-compiler-plugin/compile/default-compile/createdFiles.lst didn't match [config/workload.yaml, config/workload-native.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/workspace.xml didn't match [config/workload.yaml, config/workload-native.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/styles/bootstrap-custom.css didn't match [config/workload.yaml, config/workload-native.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/main/com/vmware/tap/accelerators/javaserversideui/web/IndexController.class didn't match [config/workload.yaml, config/workload-native.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/libs/java-server-side-ui-0.0.1-SNAPSHOT.jar didn't match [config/workload.yaml, config/workload-native.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/gradle.xml didn't match [config/workload.yaml, config/workload-native.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/buildOutputCleanup/cache.properties didn't match [config/workload.yaml, config/workload-native.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/TEST-com.vmware.tap.accelerators.javaserversideui.web.IndexControllerTest.xml didn't match [config/workload.yaml, config/workload-native.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug LICENSE didn't match [config/workload.yaml, config/workload-native.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/file-system.probe didn't match [config/workload.yaml, config/workload-native.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/maven-status/maven-compiler-plugin/compile/default-compile/inputFiles.lst didn't match [config/workload.yaml, config/workload-native.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradlew didn't match [config/workload.yaml, config/workload-native.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/binary/results.bin didn't match [config/workload.yaml, config/workload-native.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/jarRepositories.xml didn't match [config/workload.yaml, config/workload-native.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/templates/index.html didn't match [config/workload.yaml, config/workload-native.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/.gitignore didn't match [config/workload.yaml, config/workload-native.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/checksums/sha1-checksums.bin didn't match [config/workload.yaml, config/workload-native.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [config/workload.yaml, config/workload-native.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/TEST-com.vmware.tap.accelerators.javaserversideui.ApplicationTest.xml didn't match [config/workload.yaml, config/workload-native.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileHashes/fileHashes.lock didn't match [config/workload.yaml, config/workload-native.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/compiler.xml didn't match [config/workload.yaml, config/workload-native.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/test-classes/com/vmware/tap/accelerators/javaserversideui/ApplicationTest.class didn't match [config/workload.yaml, config/workload-native.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/com/vmware/tap/accelerators/javaserversideui/ApplicationTest.java didn't match [config/workload.yaml, config/workload-native.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/test/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest$Get.class didn't match [config/workload.yaml, config/workload-native.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gitignore didn't match [config/workload.yaml, config/workload-native.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/com/vmware/tap/accelerators/javaserversideui/web/IndexController.class didn't match [config/workload.yaml, config/workload-native.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/vcs-1/gc.properties didn't match [config/workload.yaml, config/workload-native.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradle/wrapper/gradle-wrapper.jar didn't match [config/workload.yaml, config/workload-native.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/main/com/vmware/tap/accelerators/javaserversideui/Application.class didn't match [config/workload.yaml, config/workload-native.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradle/wrapper/gradle-wrapper.properties didn't match [config/workload.yaml, config/workload-native.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileChanges/last-build.bin didn't match [config/workload.yaml, config/workload-native.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/TEST-com.vmware.tap.accelerators.javaserversideui.web.IndexControllerTest$Get.xml didn't match [config/workload.yaml, config/workload-native.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/css/style.css didn't match [config/workload.yaml, config/workload-native.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/classes/com.vmware.tap.accelerators.javaserversideui.web.IndexControllerTest.html didn't match [config/workload.yaml, config/workload-native.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug pom.xml didn't match [config/workload.yaml, config/workload-native.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/static/styles/bootstrap-custom.css didn't match [config/workload.yaml, config/workload-native.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/maven-status/maven-compiler-plugin/testCompile/default-testCompile/createdFiles.lst didn't match [config/workload.yaml, config/workload-native.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/vcs.xml didn't match [config/workload.yaml, config/workload-native.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/test-classes/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest$Get.class didn't match [config/workload.yaml, config/workload-native.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/test/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest.class didn't match [config/workload.yaml, config/workload-native.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/test/com/vmware/tap/accelerators/javaserversideui/ApplicationTest.class didn't match [config/workload.yaml, config/workload-native.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/dependencies-accessors/gc.properties didn't match [config/workload.yaml, config/workload-native.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .tanzuignore didn't match [config/workload.yaml, config/workload-native.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/static/styles/bootstrap-custom.css didn't match [config/workload.yaml, config/workload-native.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/packages/com.vmware.tap.accelerators.javaserversideui.html didn't match [config/workload.yaml, config/workload-native.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .grype.yaml didn't match [config/workload.yaml, config/workload-native.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/tmp/compileTestJava/previous-compilation-data.bin didn't match [config/workload.yaml, config/workload-native.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/application.yml didn't match [config/workload.yaml, config/workload-native.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/index.html didn't match [config/workload.yaml, config/workload-native.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/com/vmware/tap/accelerators/javaserversideui/Application.class didn't match [config/workload.yaml, config/workload-native.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/maven-status/maven-compiler-plugin/testCompile/default-testCompile/inputFiles.lst didn't match [config/workload.yaml, config/workload-native.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/tmp/compileJava/previous-compilation-data.bin didn't match [config/workload.yaml, config/workload-native.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileHashes/resourceHashesCache.bin didn't match [config/workload.yaml, config/workload-native.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/test-classes/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest.class didn't match [config/workload.yaml, config/workload-native.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/buildOutputCleanup/outputFiles.bin didn't match [config/workload.yaml, config/workload-native.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/classes/com.vmware.tap.accelerators.javaserversideui.web.IndexControllerTest$Get.html didn't match [config/workload.yaml, config/workload-native.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/executionHistory/executionHistory.bin didn't match [config/workload.yaml, config/workload-native.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/binary/output.bin didn't match [config/workload.yaml, config/workload-native.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileHashes/fileHashes.bin didn't match [config/workload.yaml, config/workload-native.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml didn't match [config/workload.yaml, config/workload-native.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/checksums/md5-checksums.bin didn't match [config/workload.yaml, config/workload-native.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug config/workload.yaml matched [config/workload.yaml, config/workload-native.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/checksums/checksums.lock didn't match [config/workload.yaml, config/workload-native.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/classes/com.vmware.tap.accelerators.javaserversideui.ApplicationTest.html didn't match [config/workload.yaml, config/workload-native.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/gc.properties didn't match [config/workload.yaml, config/workload-native.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/application.yml didn't match [config/workload.yaml, config/workload-native.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resolvedMainClassName didn't match [config/workload.yaml, config/workload-native.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/index.html didn't match [config/workload.yaml, config/workload-native.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/dependencies-accessors/dependencies-accessors.lock didn't match [config/workload.yaml, config/workload-native.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vmware/tap/accelerators/javaserversideui/Application.java didn't match [config/workload.yaml, config/workload-native.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/application.yml didn't match [config/workload.yaml, config/workload-native.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ Debug README.md didn't match [config/workload.yaml, config/workload-native.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ ╺ engine.transformations[0].validated.delegate.in.transformations[3].delegate.transformations[0].sources[0].validated.delegate.in.transformations[0].sources[3].delegate.transformations[1] (OpenRewriteRecipe)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[3].delegate.transformations[0].sources[0].validated.delegate.in.transformations[0].sources[4] (Combo)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Combo running as Chain
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.delegate.in.transformations[3].delegate.transformations[0].sources[0].validated.delegate.in.transformations[0].sources[4].delegate (Chain)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Running Chain(Include, Exclude, ReplaceText)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[3].delegate.transformations[0].sources[0].validated.delegate.in.transformations[0].sources[4].delegate.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Will include [config/*.yaml]
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vmware/tap/accelerators/javaserversideui/web/IndexController.java didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/packages/com.vmware.tap.accelerators.javaserversideui.web.html didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/buildOutputCleanup/buildOutputCleanup.lock didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/css/base-style.css didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest.java didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/binary/output.bin.idx didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/tmp/bootJar/MANIFEST.MF didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/executionHistory/executionHistory.lock didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/js/report.js didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/misc.xml didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/templates/index.html didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/maven-status/maven-compiler-plugin/compile/default-compile/createdFiles.lst didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/workspace.xml didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/styles/bootstrap-custom.css didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/main/com/vmware/tap/accelerators/javaserversideui/web/IndexController.class didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/libs/java-server-side-ui-0.0.1-SNAPSHOT.jar didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/gradle.xml didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/buildOutputCleanup/cache.properties didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/TEST-com.vmware.tap.accelerators.javaserversideui.web.IndexControllerTest.xml didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug LICENSE didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/file-system.probe didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/maven-status/maven-compiler-plugin/compile/default-compile/inputFiles.lst didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradlew didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/binary/results.bin didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/jarRepositories.xml didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/templates/index.html didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/.gitignore didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/checksums/sha1-checksums.bin didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/TEST-com.vmware.tap.accelerators.javaserversideui.ApplicationTest.xml didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileHashes/fileHashes.lock didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/compiler.xml didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/test-classes/com/vmware/tap/accelerators/javaserversideui/ApplicationTest.class didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/com/vmware/tap/accelerators/javaserversideui/ApplicationTest.java didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/test/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest$Get.class didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gitignore didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/com/vmware/tap/accelerators/javaserversideui/web/IndexController.class didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/vcs-1/gc.properties didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradle/wrapper/gradle-wrapper.jar didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/main/com/vmware/tap/accelerators/javaserversideui/Application.class didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradle/wrapper/gradle-wrapper.properties didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileChanges/last-build.bin didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/TEST-com.vmware.tap.accelerators.javaserversideui.web.IndexControllerTest$Get.xml didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/css/style.css didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/classes/com.vmware.tap.accelerators.javaserversideui.web.IndexControllerTest.html didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug pom.xml didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/static/styles/bootstrap-custom.css didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/maven-status/maven-compiler-plugin/testCompile/default-testCompile/createdFiles.lst didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/vcs.xml didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/test-classes/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest$Get.class didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/test/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest.class didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/test/com/vmware/tap/accelerators/javaserversideui/ApplicationTest.class didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/dependencies-accessors/gc.properties didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .tanzuignore didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/static/styles/bootstrap-custom.css didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/packages/com.vmware.tap.accelerators.javaserversideui.html didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .grype.yaml didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/tmp/compileTestJava/previous-compilation-data.bin didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/application.yml didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/index.html didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/com/vmware/tap/accelerators/javaserversideui/Application.class didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/maven-status/maven-compiler-plugin/testCompile/default-testCompile/inputFiles.lst didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/tmp/compileJava/previous-compilation-data.bin didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileHashes/resourceHashesCache.bin didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/test-classes/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest.class didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/buildOutputCleanup/outputFiles.bin didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/classes/com.vmware.tap.accelerators.javaserversideui.web.IndexControllerTest$Get.html didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/executionHistory/executionHistory.bin didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/binary/output.bin didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileHashes/fileHashes.bin didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/checksums/md5-checksums.bin didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug config/workload.yaml matched [config/*.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/checksums/checksums.lock didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/classes/com.vmware.tap.accelerators.javaserversideui.ApplicationTest.html didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/gc.properties didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/application.yml didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resolvedMainClassName didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/index.html didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/dependencies-accessors/dependencies-accessors.lock didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vmware/tap/accelerators/javaserversideui/Application.java didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/application.yml didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ Debug README.md didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[3].delegate.transformations[0].sources[0].validated.delegate.in.transformations[0].sources[4].delegate.transformations[1] (Exclude)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Will exclude [config/workload*.yaml]
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ Debug config/workload.yaml matched [config/workload*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[3].delegate.transformations[0].sources[0].validated.delegate.in.transformations[0].sources[4].delegate.transformations[2] (ReplaceText)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ ┗ ┗  Info Will replace regex '(?<unmodified>image: bellsoft/liberica-openjdk-\w*:)(\d+)' with '${unmodified}17'
┃ ┃ ┃ ┃ ┃ ┃ ┗ ┗ ┗ ╺ engine.transformations[0].validated.delegate.in.transformations[3].delegate.transformations[0].sources[0].validated.delegate.in.transformations[1] (UniquePath)
┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[3].delegate.transformations[0].sources[1] (Combo)
┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Combo running as Include
┃ ┃ ┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.delegate.in.transformations[3].delegate.transformations[0].sources[1].delegate (Include)
┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Will include [**]
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vmware/tap/accelerators/javaserversideui/web/IndexController.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/packages/com.vmware.tap.accelerators.javaserversideui.web.html matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/buildOutputCleanup/buildOutputCleanup.lock matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/css/base-style.css matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/binary/output.bin.idx matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/tmp/bootJar/MANIFEST.MF matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/executionHistory/executionHistory.lock matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/js/report.js matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/misc.xml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/templates/index.html matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/maven-status/maven-compiler-plugin/compile/default-compile/createdFiles.lst matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/workspace.xml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/styles/bootstrap-custom.css matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/main/com/vmware/tap/accelerators/javaserversideui/web/IndexController.class matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/libs/java-server-side-ui-0.0.1-SNAPSHOT.jar matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/gradle.xml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/buildOutputCleanup/cache.properties matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/TEST-com.vmware.tap.accelerators.javaserversideui.web.IndexControllerTest.xml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug LICENSE matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/file-system.probe matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/maven-status/maven-compiler-plugin/compile/default-compile/inputFiles.lst matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradlew matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/binary/results.bin matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/jarRepositories.xml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/templates/index.html matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/.gitignore matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/checksums/sha1-checksums.bin matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug README.md matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/TEST-com.vmware.tap.accelerators.javaserversideui.ApplicationTest.xml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileHashes/fileHashes.lock matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/compiler.xml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/test-classes/com/vmware/tap/accelerators/javaserversideui/ApplicationTest.class matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/com/vmware/tap/accelerators/javaserversideui/ApplicationTest.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/test/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest$Get.class matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gitignore matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/com/vmware/tap/accelerators/javaserversideui/web/IndexController.class matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/vcs-1/gc.properties matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradle/wrapper/gradle-wrapper.jar matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/main/com/vmware/tap/accelerators/javaserversideui/Application.class matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradle/wrapper/gradle-wrapper.properties matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileChanges/last-build.bin matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/TEST-com.vmware.tap.accelerators.javaserversideui.web.IndexControllerTest$Get.xml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/css/style.css matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/classes/com.vmware.tap.accelerators.javaserversideui.web.IndexControllerTest.html matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug pom.xml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/static/styles/bootstrap-custom.css matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/maven-status/maven-compiler-plugin/testCompile/default-testCompile/createdFiles.lst matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/vcs.xml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/test-classes/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest$Get.class matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/test/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest.class matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/test/com/vmware/tap/accelerators/javaserversideui/ApplicationTest.class matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/dependencies-accessors/gc.properties matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .tanzuignore matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/static/styles/bootstrap-custom.css matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/packages/com.vmware.tap.accelerators.javaserversideui.html matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .grype.yaml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/tmp/compileTestJava/previous-compilation-data.bin matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/application.yml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/index.html matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/com/vmware/tap/accelerators/javaserversideui/Application.class matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/maven-status/maven-compiler-plugin/testCompile/default-testCompile/inputFiles.lst matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/tmp/compileJava/previous-compilation-data.bin matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileHashes/resourceHashesCache.bin matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/test-classes/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest.class matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/buildOutputCleanup/outputFiles.bin matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/classes/com.vmware.tap.accelerators.javaserversideui.web.IndexControllerTest$Get.html matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/executionHistory/executionHistory.bin matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/binary/output.bin matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileHashes/fileHashes.bin matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/checksums/md5-checksums.bin matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug config/workload.yaml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/checksums/checksums.lock matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/classes/com.vmware.tap.accelerators.javaserversideui.ApplicationTest.html matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/gc.properties matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/application.yml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resolvedMainClassName matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/index.html matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/dependencies-accessors/dependencies-accessors.lock matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vmware/tap/accelerators/javaserversideui/Application.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┗ ┗ Debug src/main/resources/application.yml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[3].delegate.transformations[1] (UniquePath)
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'pom.xml', will use the one appearing first 
┃ ┃ ┃ ┃ ┗ ┗ Debug Multiple representations for path 'config/workload.yaml', will use the one appearing first 
┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[4] (Combo)
┃ ┃ ┃ ┃ ┃  Info Condition (#includeAppSsoIntegration) evaluated to true
┃ ┃ ┃ ┃ ┃  Info Combo running as Chain
┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.delegate.in.transformations[4].delegate (Chain)
┃ ┃ ┃ ┃ ┃  Info Running Chain(Merge, UniquePath)
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[4].delegate.transformations[0] (Merge)
┃ ┃ ┃ ┃ ┃ ┃  Info Running Merge(InvokeFragment, Combo)
┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[4].delegate.transformations[0].sources[0] (InvokeFragment)
┃ ┃ ┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.delegate.in.transformations[4].delegate.transformations[0].sources[0] (Let)
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug Adding symbol workloadName with value 'server-side-ui-starter'
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ ┏ engine.transformations[0].validated.delegate.in.transformations[4].delegate.transformations[0].sources[0].in.validated (Combo)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Combo running as Chain
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.delegate.in.transformations[4].delegate.transformations[0].sources[0].in.validated.delegate (Chain)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Running Chain(Merge, UniquePath)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[4].delegate.transformations[0].sources[0].in.validated.delegate.transformations[0] (Merge)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Running Merge(Combo, Combo)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[4].delegate.transformations[0].sources[0].in.validated.delegate.transformations[0].sources[0] (Combo)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Combo running as Chain
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.delegate.in.transformations[4].delegate.transformations[0].sources[0].in.validated.delegate.transformations[0].sources[0].delegate (Chain)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Running Chain(Include, OpenRewriteRecipe)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[4].delegate.transformations[0].sources[0].in.validated.delegate.transformations[0].sources[0].delegate.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Will include [**/workload.yaml]
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vmware/tap/accelerators/javaserversideui/web/IndexController.java didn't match [**/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/packages/com.vmware.tap.accelerators.javaserversideui.web.html didn't match [**/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest.java didn't match [**/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/css/base-style.css didn't match [**/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/buildOutputCleanup/buildOutputCleanup.lock didn't match [**/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/binary/output.bin.idx didn't match [**/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/tmp/bootJar/MANIFEST.MF didn't match [**/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/executionHistory/executionHistory.lock didn't match [**/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/misc.xml didn't match [**/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/js/report.js didn't match [**/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/templates/index.html didn't match [**/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/maven-status/maven-compiler-plugin/compile/default-compile/createdFiles.lst didn't match [**/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/styles/bootstrap-custom.css didn't match [**/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/workspace.xml didn't match [**/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/gradle.xml didn't match [**/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/libs/java-server-side-ui-0.0.1-SNAPSHOT.jar didn't match [**/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/main/com/vmware/tap/accelerators/javaserversideui/web/IndexController.class didn't match [**/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/TEST-com.vmware.tap.accelerators.javaserversideui.web.IndexControllerTest.xml didn't match [**/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/buildOutputCleanup/cache.properties didn't match [**/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug LICENSE didn't match [**/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/file-system.probe didn't match [**/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/maven-status/maven-compiler-plugin/compile/default-compile/inputFiles.lst didn't match [**/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradlew didn't match [**/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/jarRepositories.xml didn't match [**/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/binary/results.bin didn't match [**/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/templates/index.html didn't match [**/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/.gitignore didn't match [**/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/checksums/sha1-checksums.bin didn't match [**/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [**/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/TEST-com.vmware.tap.accelerators.javaserversideui.ApplicationTest.xml didn't match [**/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/compiler.xml didn't match [**/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileHashes/fileHashes.lock didn't match [**/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/com/vmware/tap/accelerators/javaserversideui/ApplicationTest.java didn't match [**/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/test-classes/com/vmware/tap/accelerators/javaserversideui/ApplicationTest.class didn't match [**/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/test/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest$Get.class didn't match [**/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gitignore didn't match [**/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/vcs-1/gc.properties didn't match [**/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/com/vmware/tap/accelerators/javaserversideui/web/IndexController.class didn't match [**/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradle/wrapper/gradle-wrapper.jar didn't match [**/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/main/com/vmware/tap/accelerators/javaserversideui/Application.class didn't match [**/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/TEST-com.vmware.tap.accelerators.javaserversideui.web.IndexControllerTest$Get.xml didn't match [**/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileChanges/last-build.bin didn't match [**/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradle/wrapper/gradle-wrapper.properties didn't match [**/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/css/style.css didn't match [**/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/classes/com.vmware.tap.accelerators.javaserversideui.web.IndexControllerTest.html didn't match [**/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/vcs.xml didn't match [**/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/maven-status/maven-compiler-plugin/testCompile/default-testCompile/createdFiles.lst didn't match [**/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/static/styles/bootstrap-custom.css didn't match [**/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/test/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest.class didn't match [**/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/test-classes/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest$Get.class didn't match [**/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/test/com/vmware/tap/accelerators/javaserversideui/ApplicationTest.class didn't match [**/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/dependencies-accessors/gc.properties didn't match [**/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .tanzuignore didn't match [**/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/packages/com.vmware.tap.accelerators.javaserversideui.html didn't match [**/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/static/styles/bootstrap-custom.css didn't match [**/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .grype.yaml didn't match [**/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/tmp/compileTestJava/previous-compilation-data.bin didn't match [**/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/application.yml didn't match [**/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/index.html didn't match [**/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/maven-status/maven-compiler-plugin/testCompile/default-testCompile/inputFiles.lst didn't match [**/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/com/vmware/tap/accelerators/javaserversideui/Application.class didn't match [**/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/tmp/compileJava/previous-compilation-data.bin didn't match [**/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileHashes/resourceHashesCache.bin didn't match [**/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/classes/com.vmware.tap.accelerators.javaserversideui.web.IndexControllerTest$Get.html didn't match [**/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/buildOutputCleanup/outputFiles.bin didn't match [**/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/test-classes/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest.class didn't match [**/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/binary/output.bin didn't match [**/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/executionHistory/executionHistory.bin didn't match [**/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileHashes/fileHashes.bin didn't match [**/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/checksums/md5-checksums.bin didn't match [**/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml didn't match [**/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/classes/com.vmware.tap.accelerators.javaserversideui.ApplicationTest.html didn't match [**/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/checksums/checksums.lock didn't match [**/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/gc.properties didn't match [**/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/application.yml didn't match [**/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resolvedMainClassName didn't match [**/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/index.html didn't match [**/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vmware/tap/accelerators/javaserversideui/Application.java didn't match [**/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/dependencies-accessors/dependencies-accessors.lock didn't match [**/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/application.yml didn't match [**/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug pom.xml didn't match [**/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug config/workload.yaml matched [**/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ Debug FRAGMENT_README.md didn't match [**/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ ╺ engine.transformations[0].validated.delegate.in.transformations[4].delegate.transformations[0].sources[0].in.validated.delegate.transformations[0].sources[0].delegate.transformations[1] (OpenRewriteRecipe)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[4].delegate.transformations[0].sources[0].in.validated.delegate.transformations[0].sources[1] (Combo)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Combo running as Chain
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.delegate.in.transformations[4].delegate.transformations[0].sources[0].in.validated.delegate.transformations[0].sources[1].delegate (Chain)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Running Chain(Include, ReplaceText, ReplaceText)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[4].delegate.transformations[0].sources[0].in.validated.delegate.transformations[0].sources[1].delegate.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Will include [README.md]
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vmware/tap/accelerators/javaserversideui/web/IndexController.java didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/packages/com.vmware.tap.accelerators.javaserversideui.web.html didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest.java didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/css/base-style.css didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/buildOutputCleanup/buildOutputCleanup.lock didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/binary/output.bin.idx didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/tmp/bootJar/MANIFEST.MF didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/executionHistory/executionHistory.lock didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/misc.xml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/js/report.js didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/templates/index.html didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/maven-status/maven-compiler-plugin/compile/default-compile/createdFiles.lst didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/styles/bootstrap-custom.css didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/workspace.xml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/gradle.xml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/libs/java-server-side-ui-0.0.1-SNAPSHOT.jar didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/main/com/vmware/tap/accelerators/javaserversideui/web/IndexController.class didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/TEST-com.vmware.tap.accelerators.javaserversideui.web.IndexControllerTest.xml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/buildOutputCleanup/cache.properties didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug LICENSE didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/file-system.probe didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/maven-status/maven-compiler-plugin/compile/default-compile/inputFiles.lst didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradlew didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/jarRepositories.xml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/binary/results.bin didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/templates/index.html didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/.gitignore didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/checksums/sha1-checksums.bin didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug README.md matched [README.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/TEST-com.vmware.tap.accelerators.javaserversideui.ApplicationTest.xml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/compiler.xml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileHashes/fileHashes.lock didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/com/vmware/tap/accelerators/javaserversideui/ApplicationTest.java didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/test-classes/com/vmware/tap/accelerators/javaserversideui/ApplicationTest.class didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/test/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest$Get.class didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gitignore didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/vcs-1/gc.properties didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/com/vmware/tap/accelerators/javaserversideui/web/IndexController.class didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradle/wrapper/gradle-wrapper.jar didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/main/com/vmware/tap/accelerators/javaserversideui/Application.class didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/TEST-com.vmware.tap.accelerators.javaserversideui.web.IndexControllerTest$Get.xml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileChanges/last-build.bin didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradle/wrapper/gradle-wrapper.properties didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/css/style.css didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/classes/com.vmware.tap.accelerators.javaserversideui.web.IndexControllerTest.html didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/vcs.xml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/maven-status/maven-compiler-plugin/testCompile/default-testCompile/createdFiles.lst didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/static/styles/bootstrap-custom.css didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/test/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest.class didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/test-classes/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest$Get.class didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/test/com/vmware/tap/accelerators/javaserversideui/ApplicationTest.class didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/dependencies-accessors/gc.properties didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .tanzuignore didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/packages/com.vmware.tap.accelerators.javaserversideui.html didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/static/styles/bootstrap-custom.css didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .grype.yaml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/tmp/compileTestJava/previous-compilation-data.bin didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/application.yml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/index.html didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/maven-status/maven-compiler-plugin/testCompile/default-testCompile/inputFiles.lst didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/com/vmware/tap/accelerators/javaserversideui/Application.class didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/tmp/compileJava/previous-compilation-data.bin didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileHashes/resourceHashesCache.bin didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/classes/com.vmware.tap.accelerators.javaserversideui.web.IndexControllerTest$Get.html didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/buildOutputCleanup/outputFiles.bin didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/test-classes/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest.class didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/binary/output.bin didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/executionHistory/executionHistory.bin didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileHashes/fileHashes.bin didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/checksums/md5-checksums.bin didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/classes/com.vmware.tap.accelerators.javaserversideui.ApplicationTest.html didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/checksums/checksums.lock didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/gc.properties didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/application.yml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resolvedMainClassName didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/index.html didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vmware/tap/accelerators/javaserversideui/Application.java didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/dependencies-accessors/dependencies-accessors.lock didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/application.yml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug pom.xml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug config/workload.yaml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ Debug FRAGMENT_README.md didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[4].delegate.transformations[0].sources[0].in.validated.delegate.transformations[0].sources[1].delegate.transformations[1] (ReplaceText)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Will replace regex '(?<existingContent>[\s\S]*)(?<endOfFile>
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info )' with '${existingContent}
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info 
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗  Info ...(truncated)'
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[4].delegate.transformations[0].sources[0].in.validated.delegate.transformations[0].sources[1].delegate.transformations[2] (ReplaceText)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ ┗ ┗  Info Will replace [<your-selected-appsso-offering>->ci, <your-workload>->server-side-ui-start...(truncated)]
┃ ┃ ┃ ┃ ┃ ┃ ┗ ┗ ┗ ╺ engine.transformations[0].validated.delegate.in.transformations[4].delegate.transformations[0].sources[0].in.validated.delegate.transformations[1] (UniquePath)
┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[4].delegate.transformations[0].sources[1] (Combo)
┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Combo running as Include
┃ ┃ ┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.delegate.in.transformations[4].delegate.transformations[0].sources[1].delegate (Include)
┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Will include [**]
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vmware/tap/accelerators/javaserversideui/web/IndexController.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/packages/com.vmware.tap.accelerators.javaserversideui.web.html matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/css/base-style.css matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/buildOutputCleanup/buildOutputCleanup.lock matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/binary/output.bin.idx matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/tmp/bootJar/MANIFEST.MF matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/executionHistory/executionHistory.lock matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/misc.xml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/js/report.js matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/templates/index.html matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/maven-status/maven-compiler-plugin/compile/default-compile/createdFiles.lst matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/styles/bootstrap-custom.css matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/workspace.xml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/gradle.xml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/libs/java-server-side-ui-0.0.1-SNAPSHOT.jar matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/main/com/vmware/tap/accelerators/javaserversideui/web/IndexController.class matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/TEST-com.vmware.tap.accelerators.javaserversideui.web.IndexControllerTest.xml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/buildOutputCleanup/cache.properties matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug LICENSE matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/file-system.probe matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/maven-status/maven-compiler-plugin/compile/default-compile/inputFiles.lst matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradlew matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/jarRepositories.xml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/binary/results.bin matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/templates/index.html matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/.gitignore matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/checksums/sha1-checksums.bin matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug README.md matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/TEST-com.vmware.tap.accelerators.javaserversideui.ApplicationTest.xml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/compiler.xml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileHashes/fileHashes.lock matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/com/vmware/tap/accelerators/javaserversideui/ApplicationTest.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/test-classes/com/vmware/tap/accelerators/javaserversideui/ApplicationTest.class matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/test/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest$Get.class matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gitignore matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/vcs-1/gc.properties matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/com/vmware/tap/accelerators/javaserversideui/web/IndexController.class matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradle/wrapper/gradle-wrapper.jar matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/main/com/vmware/tap/accelerators/javaserversideui/Application.class matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/TEST-com.vmware.tap.accelerators.javaserversideui.web.IndexControllerTest$Get.xml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileChanges/last-build.bin matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradle/wrapper/gradle-wrapper.properties matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/css/style.css matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/classes/com.vmware.tap.accelerators.javaserversideui.web.IndexControllerTest.html matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/vcs.xml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/maven-status/maven-compiler-plugin/testCompile/default-testCompile/createdFiles.lst matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/static/styles/bootstrap-custom.css matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/test/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest.class matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/test-classes/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest$Get.class matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/test/com/vmware/tap/accelerators/javaserversideui/ApplicationTest.class matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/dependencies-accessors/gc.properties matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .tanzuignore matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/packages/com.vmware.tap.accelerators.javaserversideui.html matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/static/styles/bootstrap-custom.css matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .grype.yaml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/tmp/compileTestJava/previous-compilation-data.bin matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/application.yml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/index.html matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/maven-status/maven-compiler-plugin/testCompile/default-testCompile/inputFiles.lst matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/com/vmware/tap/accelerators/javaserversideui/Application.class matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/tmp/compileJava/previous-compilation-data.bin matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileHashes/resourceHashesCache.bin matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/classes/com.vmware.tap.accelerators.javaserversideui.web.IndexControllerTest$Get.html matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/buildOutputCleanup/outputFiles.bin matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/test-classes/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest.class matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/binary/output.bin matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/executionHistory/executionHistory.bin matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileHashes/fileHashes.bin matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/checksums/md5-checksums.bin matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/classes/com.vmware.tap.accelerators.javaserversideui.ApplicationTest.html matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/checksums/checksums.lock matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/gc.properties matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/application.yml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resolvedMainClassName matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/index.html matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vmware/tap/accelerators/javaserversideui/Application.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/dependencies-accessors/dependencies-accessors.lock matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/application.yml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug pom.xml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┗ ┗ Debug config/workload.yaml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[4].delegate.transformations[1] (UniquePath)
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'README.md', will use the one appearing first 
┃ ┃ ┃ ┃ ┗ ┗ Debug Multiple representations for path 'config/workload.yaml', will use the one appearing first 
┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[5] (Combo)
┃ ┃ ┃ ┃ ┃  Info Condition (#includeAppSsoIntegration) evaluated to true
┃ ┃ ┃ ┃ ┃  Info Combo running as Chain
┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.delegate.in.transformations[5].delegate (Chain)
┃ ┃ ┃ ┃ ┃  Info Running Chain(Merge, UniquePath)
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[5].delegate.transformations[0] (Merge)
┃ ┃ ┃ ┃ ┃ ┃  Info Running Merge(InvokeFragment, Combo)
┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[5].delegate.transformations[0].sources[0] (InvokeFragment)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[5].delegate.transformations[0].sources[0].validated (Combo)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Combo running as Chain
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.delegate.in.transformations[5].delegate.transformations[0].sources[0].validated.delegate (Chain)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Running Chain(Merge, UniquePath)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[5].delegate.transformations[0].sources[0].validated.delegate.transformations[0] (Merge)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Running Merge(Include, Combo, Combo, Combo, Combo, Combo)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[5].delegate.transformations[0].sources[0].validated.delegate.transformations[0].sources[0] (Include)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Will include [**/profile.html, **/application-local.yml]
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vmware/tap/accelerators/javaserversideui/web/IndexController.java didn't match [**/profile.html, **/application-local.yml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/packages/com.vmware.tap.accelerators.javaserversideui.web.html didn't match [**/profile.html, **/application-local.yml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/buildOutputCleanup/buildOutputCleanup.lock didn't match [**/profile.html, **/application-local.yml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/css/base-style.css didn't match [**/profile.html, **/application-local.yml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest.java didn't match [**/profile.html, **/application-local.yml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/binary/output.bin.idx didn't match [**/profile.html, **/application-local.yml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/tmp/bootJar/MANIFEST.MF didn't match [**/profile.html, **/application-local.yml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/executionHistory/executionHistory.lock didn't match [**/profile.html, **/application-local.yml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/js/report.js didn't match [**/profile.html, **/application-local.yml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/misc.xml didn't match [**/profile.html, **/application-local.yml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/templates/index.html didn't match [**/profile.html, **/application-local.yml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/maven-status/maven-compiler-plugin/compile/default-compile/createdFiles.lst didn't match [**/profile.html, **/application-local.yml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/workspace.xml didn't match [**/profile.html, **/application-local.yml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/styles/bootstrap-custom.css didn't match [**/profile.html, **/application-local.yml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/main/com/vmware/tap/accelerators/javaserversideui/web/IndexController.class didn't match [**/profile.html, **/application-local.yml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/libs/java-server-side-ui-0.0.1-SNAPSHOT.jar didn't match [**/profile.html, **/application-local.yml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/gradle.xml didn't match [**/profile.html, **/application-local.yml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/buildOutputCleanup/cache.properties didn't match [**/profile.html, **/application-local.yml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/TEST-com.vmware.tap.accelerators.javaserversideui.web.IndexControllerTest.xml didn't match [**/profile.html, **/application-local.yml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug LICENSE didn't match [**/profile.html, **/application-local.yml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/file-system.probe didn't match [**/profile.html, **/application-local.yml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/maven-status/maven-compiler-plugin/compile/default-compile/inputFiles.lst didn't match [**/profile.html, **/application-local.yml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradlew didn't match [**/profile.html, **/application-local.yml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/binary/results.bin didn't match [**/profile.html, **/application-local.yml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/jarRepositories.xml didn't match [**/profile.html, **/application-local.yml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/templates/index.html didn't match [**/profile.html, **/application-local.yml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/.gitignore didn't match [**/profile.html, **/application-local.yml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/checksums/sha1-checksums.bin didn't match [**/profile.html, **/application-local.yml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/TEST-com.vmware.tap.accelerators.javaserversideui.ApplicationTest.xml didn't match [**/profile.html, **/application-local.yml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileHashes/fileHashes.lock didn't match [**/profile.html, **/application-local.yml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/compiler.xml didn't match [**/profile.html, **/application-local.yml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/test-classes/com/vmware/tap/accelerators/javaserversideui/ApplicationTest.class didn't match [**/profile.html, **/application-local.yml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/com/vmware/tap/accelerators/javaserversideui/ApplicationTest.java didn't match [**/profile.html, **/application-local.yml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/test/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest$Get.class didn't match [**/profile.html, **/application-local.yml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gitignore didn't match [**/profile.html, **/application-local.yml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/com/vmware/tap/accelerators/javaserversideui/web/IndexController.class didn't match [**/profile.html, **/application-local.yml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/vcs-1/gc.properties didn't match [**/profile.html, **/application-local.yml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradle/wrapper/gradle-wrapper.jar didn't match [**/profile.html, **/application-local.yml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/main/com/vmware/tap/accelerators/javaserversideui/Application.class didn't match [**/profile.html, **/application-local.yml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradle/wrapper/gradle-wrapper.properties didn't match [**/profile.html, **/application-local.yml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileChanges/last-build.bin didn't match [**/profile.html, **/application-local.yml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/TEST-com.vmware.tap.accelerators.javaserversideui.web.IndexControllerTest$Get.xml didn't match [**/profile.html, **/application-local.yml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/css/style.css didn't match [**/profile.html, **/application-local.yml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug pom.xml didn't match [**/profile.html, **/application-local.yml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/classes/com.vmware.tap.accelerators.javaserversideui.web.IndexControllerTest.html didn't match [**/profile.html, **/application-local.yml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/static/styles/bootstrap-custom.css didn't match [**/profile.html, **/application-local.yml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/maven-status/maven-compiler-plugin/testCompile/default-testCompile/createdFiles.lst didn't match [**/profile.html, **/application-local.yml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/vcs.xml didn't match [**/profile.html, **/application-local.yml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/test-classes/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest$Get.class didn't match [**/profile.html, **/application-local.yml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/test/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest.class didn't match [**/profile.html, **/application-local.yml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/test/com/vmware/tap/accelerators/javaserversideui/ApplicationTest.class didn't match [**/profile.html, **/application-local.yml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/dependencies-accessors/gc.properties didn't match [**/profile.html, **/application-local.yml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .tanzuignore didn't match [**/profile.html, **/application-local.yml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/static/styles/bootstrap-custom.css didn't match [**/profile.html, **/application-local.yml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/packages/com.vmware.tap.accelerators.javaserversideui.html didn't match [**/profile.html, **/application-local.yml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .grype.yaml didn't match [**/profile.html, **/application-local.yml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/tmp/compileTestJava/previous-compilation-data.bin didn't match [**/profile.html, **/application-local.yml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/application.yml didn't match [**/profile.html, **/application-local.yml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/index.html didn't match [**/profile.html, **/application-local.yml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/com/vmware/tap/accelerators/javaserversideui/Application.class didn't match [**/profile.html, **/application-local.yml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/maven-status/maven-compiler-plugin/testCompile/default-testCompile/inputFiles.lst didn't match [**/profile.html, **/application-local.yml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/tmp/compileJava/previous-compilation-data.bin didn't match [**/profile.html, **/application-local.yml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileHashes/resourceHashesCache.bin didn't match [**/profile.html, **/application-local.yml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/test-classes/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest.class didn't match [**/profile.html, **/application-local.yml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/buildOutputCleanup/outputFiles.bin didn't match [**/profile.html, **/application-local.yml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/classes/com.vmware.tap.accelerators.javaserversideui.web.IndexControllerTest$Get.html didn't match [**/profile.html, **/application-local.yml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/executionHistory/executionHistory.bin didn't match [**/profile.html, **/application-local.yml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/binary/output.bin didn't match [**/profile.html, **/application-local.yml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileHashes/fileHashes.bin didn't match [**/profile.html, **/application-local.yml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml didn't match [**/profile.html, **/application-local.yml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/checksums/md5-checksums.bin didn't match [**/profile.html, **/application-local.yml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/checksums/checksums.lock didn't match [**/profile.html, **/application-local.yml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/classes/com.vmware.tap.accelerators.javaserversideui.ApplicationTest.html didn't match [**/profile.html, **/application-local.yml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/gc.properties didn't match [**/profile.html, **/application-local.yml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/application.yml didn't match [**/profile.html, **/application-local.yml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resolvedMainClassName didn't match [**/profile.html, **/application-local.yml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/index.html didn't match [**/profile.html, **/application-local.yml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/dependencies-accessors/dependencies-accessors.lock didn't match [**/profile.html, **/application-local.yml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vmware/tap/accelerators/javaserversideui/Application.java didn't match [**/profile.html, **/application-local.yml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/application.yml didn't match [**/profile.html, **/application-local.yml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [**/profile.html, **/application-local.yml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug config/workload.yaml didn't match [**/profile.html, **/application-local.yml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug FRAGMENT_README.md didn't match [**/profile.html, **/application-local.yml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/vcs.xml didn't match [**/profile.html, **/application-local.yml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/workspace.xml didn't match [**/profile.html, **/application-local.yml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/com/vmware/tap/fragments/appssoauthcodeflow/TestWebSecurityConfiguration.java didn't match [**/profile.html, **/application-local.yml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/com/vmware/tap/fragments/appssoauthcodeflow/web/OidcUserControllerTest.java didn't match [**/profile.html, **/application-local.yml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/protected/profile.html matched [**/profile.html, **/application-local.yml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/application-local.yml matched [**/profile.html, **/application-local.yml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vmware/tap/fragments/appssoauthcodeflow/web/OidcUserController.java didn't match [**/profile.html, **/application-local.yml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ Debug src/main/java/com/vmware/tap/fragments/appssoauthcodeflow/WebSecurityConfiguration.java didn't match [**/profile.html, **/application-local.yml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[5].delegate.transformations[0].sources[0].validated.delegate.transformations[0].sources[1] (Combo)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Combo running as Chain
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.delegate.in.transformations[5].delegate.transformations[0].sources[0].validated.delegate.transformations[0].sources[1].delegate (Chain)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Running Chain(Include, OpenRewriteRecipe)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[5].delegate.transformations[0].sources[0].validated.delegate.transformations[0].sources[1].delegate.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Will include [**/OidcUserController.java, **/OidcUserControllerTest.java, **/WebSecurityConfiguration.java, **/TestWebSecurityConfiguration.java]
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vmware/tap/accelerators/javaserversideui/web/IndexController.java didn't match [**/OidcUserController.java, **/OidcUserControllerTest.java, **/WebSecurityConfiguration.java, **/TestWebSecurityConfiguration.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/packages/com.vmware.tap.accelerators.javaserversideui.web.html didn't match [**/OidcUserController.java, **/OidcUserControllerTest.java, **/WebSecurityConfiguration.java, **/TestWebSecurityConfiguration.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/buildOutputCleanup/buildOutputCleanup.lock didn't match [**/OidcUserController.java, **/OidcUserControllerTest.java, **/WebSecurityConfiguration.java, **/TestWebSecurityConfiguration.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/css/base-style.css didn't match [**/OidcUserController.java, **/OidcUserControllerTest.java, **/WebSecurityConfiguration.java, **/TestWebSecurityConfiguration.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest.java didn't match [**/OidcUserController.java, **/OidcUserControllerTest.java, **/WebSecurityConfiguration.java, **/TestWebSecurityConfiguration.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/binary/output.bin.idx didn't match [**/OidcUserController.java, **/OidcUserControllerTest.java, **/WebSecurityConfiguration.java, **/TestWebSecurityConfiguration.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/tmp/bootJar/MANIFEST.MF didn't match [**/OidcUserController.java, **/OidcUserControllerTest.java, **/WebSecurityConfiguration.java, **/TestWebSecurityConfiguration.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/executionHistory/executionHistory.lock didn't match [**/OidcUserController.java, **/OidcUserControllerTest.java, **/WebSecurityConfiguration.java, **/TestWebSecurityConfiguration.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/js/report.js didn't match [**/OidcUserController.java, **/OidcUserControllerTest.java, **/WebSecurityConfiguration.java, **/TestWebSecurityConfiguration.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/misc.xml didn't match [**/OidcUserController.java, **/OidcUserControllerTest.java, **/WebSecurityConfiguration.java, **/TestWebSecurityConfiguration.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/templates/index.html didn't match [**/OidcUserController.java, **/OidcUserControllerTest.java, **/WebSecurityConfiguration.java, **/TestWebSecurityConfiguration.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/maven-status/maven-compiler-plugin/compile/default-compile/createdFiles.lst didn't match [**/OidcUserController.java, **/OidcUserControllerTest.java, **/WebSecurityConfiguration.java, **/TestWebSecurityConfiguration.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/workspace.xml didn't match [**/OidcUserController.java, **/OidcUserControllerTest.java, **/WebSecurityConfiguration.java, **/TestWebSecurityConfiguration.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/styles/bootstrap-custom.css didn't match [**/OidcUserController.java, **/OidcUserControllerTest.java, **/WebSecurityConfiguration.java, **/TestWebSecurityConfiguration.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/main/com/vmware/tap/accelerators/javaserversideui/web/IndexController.class didn't match [**/OidcUserController.java, **/OidcUserControllerTest.java, **/WebSecurityConfiguration.java, **/TestWebSecurityConfiguration.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/libs/java-server-side-ui-0.0.1-SNAPSHOT.jar didn't match [**/OidcUserController.java, **/OidcUserControllerTest.java, **/WebSecurityConfiguration.java, **/TestWebSecurityConfiguration.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/gradle.xml didn't match [**/OidcUserController.java, **/OidcUserControllerTest.java, **/WebSecurityConfiguration.java, **/TestWebSecurityConfiguration.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/buildOutputCleanup/cache.properties didn't match [**/OidcUserController.java, **/OidcUserControllerTest.java, **/WebSecurityConfiguration.java, **/TestWebSecurityConfiguration.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/TEST-com.vmware.tap.accelerators.javaserversideui.web.IndexControllerTest.xml didn't match [**/OidcUserController.java, **/OidcUserControllerTest.java, **/WebSecurityConfiguration.java, **/TestWebSecurityConfiguration.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug LICENSE didn't match [**/OidcUserController.java, **/OidcUserControllerTest.java, **/WebSecurityConfiguration.java, **/TestWebSecurityConfiguration.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/file-system.probe didn't match [**/OidcUserController.java, **/OidcUserControllerTest.java, **/WebSecurityConfiguration.java, **/TestWebSecurityConfiguration.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/maven-status/maven-compiler-plugin/compile/default-compile/inputFiles.lst didn't match [**/OidcUserController.java, **/OidcUserControllerTest.java, **/WebSecurityConfiguration.java, **/TestWebSecurityConfiguration.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradlew didn't match [**/OidcUserController.java, **/OidcUserControllerTest.java, **/WebSecurityConfiguration.java, **/TestWebSecurityConfiguration.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/binary/results.bin didn't match [**/OidcUserController.java, **/OidcUserControllerTest.java, **/WebSecurityConfiguration.java, **/TestWebSecurityConfiguration.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/jarRepositories.xml didn't match [**/OidcUserController.java, **/OidcUserControllerTest.java, **/WebSecurityConfiguration.java, **/TestWebSecurityConfiguration.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/templates/index.html didn't match [**/OidcUserController.java, **/OidcUserControllerTest.java, **/WebSecurityConfiguration.java, **/TestWebSecurityConfiguration.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/.gitignore didn't match [**/OidcUserController.java, **/OidcUserControllerTest.java, **/WebSecurityConfiguration.java, **/TestWebSecurityConfiguration.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/checksums/sha1-checksums.bin didn't match [**/OidcUserController.java, **/OidcUserControllerTest.java, **/WebSecurityConfiguration.java, **/TestWebSecurityConfiguration.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/TEST-com.vmware.tap.accelerators.javaserversideui.ApplicationTest.xml didn't match [**/OidcUserController.java, **/OidcUserControllerTest.java, **/WebSecurityConfiguration.java, **/TestWebSecurityConfiguration.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileHashes/fileHashes.lock didn't match [**/OidcUserController.java, **/OidcUserControllerTest.java, **/WebSecurityConfiguration.java, **/TestWebSecurityConfiguration.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/compiler.xml didn't match [**/OidcUserController.java, **/OidcUserControllerTest.java, **/WebSecurityConfiguration.java, **/TestWebSecurityConfiguration.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/test-classes/com/vmware/tap/accelerators/javaserversideui/ApplicationTest.class didn't match [**/OidcUserController.java, **/OidcUserControllerTest.java, **/WebSecurityConfiguration.java, **/TestWebSecurityConfiguration.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/com/vmware/tap/accelerators/javaserversideui/ApplicationTest.java didn't match [**/OidcUserController.java, **/OidcUserControllerTest.java, **/WebSecurityConfiguration.java, **/TestWebSecurityConfiguration.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/test/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest$Get.class didn't match [**/OidcUserController.java, **/OidcUserControllerTest.java, **/WebSecurityConfiguration.java, **/TestWebSecurityConfiguration.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gitignore didn't match [**/OidcUserController.java, **/OidcUserControllerTest.java, **/WebSecurityConfiguration.java, **/TestWebSecurityConfiguration.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/com/vmware/tap/accelerators/javaserversideui/web/IndexController.class didn't match [**/OidcUserController.java, **/OidcUserControllerTest.java, **/WebSecurityConfiguration.java, **/TestWebSecurityConfiguration.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/vcs-1/gc.properties didn't match [**/OidcUserController.java, **/OidcUserControllerTest.java, **/WebSecurityConfiguration.java, **/TestWebSecurityConfiguration.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradle/wrapper/gradle-wrapper.jar didn't match [**/OidcUserController.java, **/OidcUserControllerTest.java, **/WebSecurityConfiguration.java, **/TestWebSecurityConfiguration.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/main/com/vmware/tap/accelerators/javaserversideui/Application.class didn't match [**/OidcUserController.java, **/OidcUserControllerTest.java, **/WebSecurityConfiguration.java, **/TestWebSecurityConfiguration.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradle/wrapper/gradle-wrapper.properties didn't match [**/OidcUserController.java, **/OidcUserControllerTest.java, **/WebSecurityConfiguration.java, **/TestWebSecurityConfiguration.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileChanges/last-build.bin didn't match [**/OidcUserController.java, **/OidcUserControllerTest.java, **/WebSecurityConfiguration.java, **/TestWebSecurityConfiguration.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/TEST-com.vmware.tap.accelerators.javaserversideui.web.IndexControllerTest$Get.xml didn't match [**/OidcUserController.java, **/OidcUserControllerTest.java, **/WebSecurityConfiguration.java, **/TestWebSecurityConfiguration.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/css/style.css didn't match [**/OidcUserController.java, **/OidcUserControllerTest.java, **/WebSecurityConfiguration.java, **/TestWebSecurityConfiguration.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug pom.xml didn't match [**/OidcUserController.java, **/OidcUserControllerTest.java, **/WebSecurityConfiguration.java, **/TestWebSecurityConfiguration.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/classes/com.vmware.tap.accelerators.javaserversideui.web.IndexControllerTest.html didn't match [**/OidcUserController.java, **/OidcUserControllerTest.java, **/WebSecurityConfiguration.java, **/TestWebSecurityConfiguration.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/static/styles/bootstrap-custom.css didn't match [**/OidcUserController.java, **/OidcUserControllerTest.java, **/WebSecurityConfiguration.java, **/TestWebSecurityConfiguration.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/maven-status/maven-compiler-plugin/testCompile/default-testCompile/createdFiles.lst didn't match [**/OidcUserController.java, **/OidcUserControllerTest.java, **/WebSecurityConfiguration.java, **/TestWebSecurityConfiguration.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/vcs.xml didn't match [**/OidcUserController.java, **/OidcUserControllerTest.java, **/WebSecurityConfiguration.java, **/TestWebSecurityConfiguration.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/test-classes/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest$Get.class didn't match [**/OidcUserController.java, **/OidcUserControllerTest.java, **/WebSecurityConfiguration.java, **/TestWebSecurityConfiguration.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/test/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest.class didn't match [**/OidcUserController.java, **/OidcUserControllerTest.java, **/WebSecurityConfiguration.java, **/TestWebSecurityConfiguration.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/test/com/vmware/tap/accelerators/javaserversideui/ApplicationTest.class didn't match [**/OidcUserController.java, **/OidcUserControllerTest.java, **/WebSecurityConfiguration.java, **/TestWebSecurityConfiguration.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/dependencies-accessors/gc.properties didn't match [**/OidcUserController.java, **/OidcUserControllerTest.java, **/WebSecurityConfiguration.java, **/TestWebSecurityConfiguration.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .tanzuignore didn't match [**/OidcUserController.java, **/OidcUserControllerTest.java, **/WebSecurityConfiguration.java, **/TestWebSecurityConfiguration.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/static/styles/bootstrap-custom.css didn't match [**/OidcUserController.java, **/OidcUserControllerTest.java, **/WebSecurityConfiguration.java, **/TestWebSecurityConfiguration.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/packages/com.vmware.tap.accelerators.javaserversideui.html didn't match [**/OidcUserController.java, **/OidcUserControllerTest.java, **/WebSecurityConfiguration.java, **/TestWebSecurityConfiguration.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .grype.yaml didn't match [**/OidcUserController.java, **/OidcUserControllerTest.java, **/WebSecurityConfiguration.java, **/TestWebSecurityConfiguration.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/tmp/compileTestJava/previous-compilation-data.bin didn't match [**/OidcUserController.java, **/OidcUserControllerTest.java, **/WebSecurityConfiguration.java, **/TestWebSecurityConfiguration.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/application.yml didn't match [**/OidcUserController.java, **/OidcUserControllerTest.java, **/WebSecurityConfiguration.java, **/TestWebSecurityConfiguration.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/index.html didn't match [**/OidcUserController.java, **/OidcUserControllerTest.java, **/WebSecurityConfiguration.java, **/TestWebSecurityConfiguration.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/com/vmware/tap/accelerators/javaserversideui/Application.class didn't match [**/OidcUserController.java, **/OidcUserControllerTest.java, **/WebSecurityConfiguration.java, **/TestWebSecurityConfiguration.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/maven-status/maven-compiler-plugin/testCompile/default-testCompile/inputFiles.lst didn't match [**/OidcUserController.java, **/OidcUserControllerTest.java, **/WebSecurityConfiguration.java, **/TestWebSecurityConfiguration.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/tmp/compileJava/previous-compilation-data.bin didn't match [**/OidcUserController.java, **/OidcUserControllerTest.java, **/WebSecurityConfiguration.java, **/TestWebSecurityConfiguration.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileHashes/resourceHashesCache.bin didn't match [**/OidcUserController.java, **/OidcUserControllerTest.java, **/WebSecurityConfiguration.java, **/TestWebSecurityConfiguration.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/test-classes/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest.class didn't match [**/OidcUserController.java, **/OidcUserControllerTest.java, **/WebSecurityConfiguration.java, **/TestWebSecurityConfiguration.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/buildOutputCleanup/outputFiles.bin didn't match [**/OidcUserController.java, **/OidcUserControllerTest.java, **/WebSecurityConfiguration.java, **/TestWebSecurityConfiguration.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/classes/com.vmware.tap.accelerators.javaserversideui.web.IndexControllerTest$Get.html didn't match [**/OidcUserController.java, **/OidcUserControllerTest.java, **/WebSecurityConfiguration.java, **/TestWebSecurityConfiguration.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/executionHistory/executionHistory.bin didn't match [**/OidcUserController.java, **/OidcUserControllerTest.java, **/WebSecurityConfiguration.java, **/TestWebSecurityConfiguration.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/binary/output.bin didn't match [**/OidcUserController.java, **/OidcUserControllerTest.java, **/WebSecurityConfiguration.java, **/TestWebSecurityConfiguration.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileHashes/fileHashes.bin didn't match [**/OidcUserController.java, **/OidcUserControllerTest.java, **/WebSecurityConfiguration.java, **/TestWebSecurityConfiguration.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml didn't match [**/OidcUserController.java, **/OidcUserControllerTest.java, **/WebSecurityConfiguration.java, **/TestWebSecurityConfiguration.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/checksums/md5-checksums.bin didn't match [**/OidcUserController.java, **/OidcUserControllerTest.java, **/WebSecurityConfiguration.java, **/TestWebSecurityConfiguration.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/checksums/checksums.lock didn't match [**/OidcUserController.java, **/OidcUserControllerTest.java, **/WebSecurityConfiguration.java, **/TestWebSecurityConfiguration.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/classes/com.vmware.tap.accelerators.javaserversideui.ApplicationTest.html didn't match [**/OidcUserController.java, **/OidcUserControllerTest.java, **/WebSecurityConfiguration.java, **/TestWebSecurityConfiguration.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/gc.properties didn't match [**/OidcUserController.java, **/OidcUserControllerTest.java, **/WebSecurityConfiguration.java, **/TestWebSecurityConfiguration.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/application.yml didn't match [**/OidcUserController.java, **/OidcUserControllerTest.java, **/WebSecurityConfiguration.java, **/TestWebSecurityConfiguration.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resolvedMainClassName didn't match [**/OidcUserController.java, **/OidcUserControllerTest.java, **/WebSecurityConfiguration.java, **/TestWebSecurityConfiguration.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/index.html didn't match [**/OidcUserController.java, **/OidcUserControllerTest.java, **/WebSecurityConfiguration.java, **/TestWebSecurityConfiguration.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/dependencies-accessors/dependencies-accessors.lock didn't match [**/OidcUserController.java, **/OidcUserControllerTest.java, **/WebSecurityConfiguration.java, **/TestWebSecurityConfiguration.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vmware/tap/accelerators/javaserversideui/Application.java didn't match [**/OidcUserController.java, **/OidcUserControllerTest.java, **/WebSecurityConfiguration.java, **/TestWebSecurityConfiguration.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/application.yml didn't match [**/OidcUserController.java, **/OidcUserControllerTest.java, **/WebSecurityConfiguration.java, **/TestWebSecurityConfiguration.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [**/OidcUserController.java, **/OidcUserControllerTest.java, **/WebSecurityConfiguration.java, **/TestWebSecurityConfiguration.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug config/workload.yaml didn't match [**/OidcUserController.java, **/OidcUserControllerTest.java, **/WebSecurityConfiguration.java, **/TestWebSecurityConfiguration.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug FRAGMENT_README.md didn't match [**/OidcUserController.java, **/OidcUserControllerTest.java, **/WebSecurityConfiguration.java, **/TestWebSecurityConfiguration.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/vcs.xml didn't match [**/OidcUserController.java, **/OidcUserControllerTest.java, **/WebSecurityConfiguration.java, **/TestWebSecurityConfiguration.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/workspace.xml didn't match [**/OidcUserController.java, **/OidcUserControllerTest.java, **/WebSecurityConfiguration.java, **/TestWebSecurityConfiguration.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/com/vmware/tap/fragments/appssoauthcodeflow/TestWebSecurityConfiguration.java matched [**/OidcUserController.java, **/OidcUserControllerTest.java, **/WebSecurityConfiguration.java, **/TestWebSecurityConfiguration.java] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/com/vmware/tap/fragments/appssoauthcodeflow/web/OidcUserControllerTest.java matched [**/OidcUserController.java, **/OidcUserControllerTest.java, **/WebSecurityConfiguration.java, **/TestWebSecurityConfiguration.java] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/protected/profile.html didn't match [**/OidcUserController.java, **/OidcUserControllerTest.java, **/WebSecurityConfiguration.java, **/TestWebSecurityConfiguration.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/application-local.yml didn't match [**/OidcUserController.java, **/OidcUserControllerTest.java, **/WebSecurityConfiguration.java, **/TestWebSecurityConfiguration.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vmware/tap/fragments/appssoauthcodeflow/web/OidcUserController.java matched [**/OidcUserController.java, **/OidcUserControllerTest.java, **/WebSecurityConfiguration.java, **/TestWebSecurityConfiguration.java] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ Debug src/main/java/com/vmware/tap/fragments/appssoauthcodeflow/WebSecurityConfiguration.java matched [**/OidcUserController.java, **/OidcUserControllerTest.java, **/WebSecurityConfiguration.java, **/TestWebSecurityConfiguration.java] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ ╺ engine.transformations[0].validated.delegate.in.transformations[5].delegate.transformations[0].sources[0].validated.delegate.transformations[0].sources[1].delegate.transformations[1] (OpenRewriteRecipe)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[5].delegate.transformations[0].sources[0].validated.delegate.transformations[0].sources[2] (Combo)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Combo running as Chain
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.delegate.in.transformations[5].delegate.transformations[0].sources[0].validated.delegate.transformations[0].sources[2].delegate (Chain)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Running Chain(Include, ReplaceText)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[5].delegate.transformations[0].sources[0].validated.delegate.transformations[0].sources[2].delegate.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Will include [**/index.html]
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vmware/tap/accelerators/javaserversideui/web/IndexController.java didn't match [**/index.html] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/packages/com.vmware.tap.accelerators.javaserversideui.web.html didn't match [**/index.html] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/buildOutputCleanup/buildOutputCleanup.lock didn't match [**/index.html] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/css/base-style.css didn't match [**/index.html] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest.java didn't match [**/index.html] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/binary/output.bin.idx didn't match [**/index.html] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/tmp/bootJar/MANIFEST.MF didn't match [**/index.html] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/executionHistory/executionHistory.lock didn't match [**/index.html] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/js/report.js didn't match [**/index.html] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/misc.xml didn't match [**/index.html] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/templates/index.html matched [**/index.html] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/maven-status/maven-compiler-plugin/compile/default-compile/createdFiles.lst didn't match [**/index.html] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/workspace.xml didn't match [**/index.html] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/styles/bootstrap-custom.css didn't match [**/index.html] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/main/com/vmware/tap/accelerators/javaserversideui/web/IndexController.class didn't match [**/index.html] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/libs/java-server-side-ui-0.0.1-SNAPSHOT.jar didn't match [**/index.html] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/gradle.xml didn't match [**/index.html] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/buildOutputCleanup/cache.properties didn't match [**/index.html] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/TEST-com.vmware.tap.accelerators.javaserversideui.web.IndexControllerTest.xml didn't match [**/index.html] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug LICENSE didn't match [**/index.html] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/file-system.probe didn't match [**/index.html] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/maven-status/maven-compiler-plugin/compile/default-compile/inputFiles.lst didn't match [**/index.html] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradlew didn't match [**/index.html] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/binary/results.bin didn't match [**/index.html] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/jarRepositories.xml didn't match [**/index.html] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/templates/index.html matched [**/index.html] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/.gitignore didn't match [**/index.html] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/checksums/sha1-checksums.bin didn't match [**/index.html] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/TEST-com.vmware.tap.accelerators.javaserversideui.ApplicationTest.xml didn't match [**/index.html] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileHashes/fileHashes.lock didn't match [**/index.html] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/compiler.xml didn't match [**/index.html] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/test-classes/com/vmware/tap/accelerators/javaserversideui/ApplicationTest.class didn't match [**/index.html] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/com/vmware/tap/accelerators/javaserversideui/ApplicationTest.java didn't match [**/index.html] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/test/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest$Get.class didn't match [**/index.html] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gitignore didn't match [**/index.html] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/com/vmware/tap/accelerators/javaserversideui/web/IndexController.class didn't match [**/index.html] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/vcs-1/gc.properties didn't match [**/index.html] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradle/wrapper/gradle-wrapper.jar didn't match [**/index.html] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/main/com/vmware/tap/accelerators/javaserversideui/Application.class didn't match [**/index.html] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradle/wrapper/gradle-wrapper.properties didn't match [**/index.html] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileChanges/last-build.bin didn't match [**/index.html] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/TEST-com.vmware.tap.accelerators.javaserversideui.web.IndexControllerTest$Get.xml didn't match [**/index.html] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/css/style.css didn't match [**/index.html] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug pom.xml didn't match [**/index.html] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/classes/com.vmware.tap.accelerators.javaserversideui.web.IndexControllerTest.html didn't match [**/index.html] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/static/styles/bootstrap-custom.css didn't match [**/index.html] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/maven-status/maven-compiler-plugin/testCompile/default-testCompile/createdFiles.lst didn't match [**/index.html] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/vcs.xml didn't match [**/index.html] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/test-classes/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest$Get.class didn't match [**/index.html] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/test/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest.class didn't match [**/index.html] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/test/com/vmware/tap/accelerators/javaserversideui/ApplicationTest.class didn't match [**/index.html] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/dependencies-accessors/gc.properties didn't match [**/index.html] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .tanzuignore didn't match [**/index.html] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/static/styles/bootstrap-custom.css didn't match [**/index.html] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/packages/com.vmware.tap.accelerators.javaserversideui.html didn't match [**/index.html] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .grype.yaml didn't match [**/index.html] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/tmp/compileTestJava/previous-compilation-data.bin didn't match [**/index.html] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/application.yml didn't match [**/index.html] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/index.html matched [**/index.html] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/com/vmware/tap/accelerators/javaserversideui/Application.class didn't match [**/index.html] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/maven-status/maven-compiler-plugin/testCompile/default-testCompile/inputFiles.lst didn't match [**/index.html] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/tmp/compileJava/previous-compilation-data.bin didn't match [**/index.html] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileHashes/resourceHashesCache.bin didn't match [**/index.html] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/test-classes/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest.class didn't match [**/index.html] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/buildOutputCleanup/outputFiles.bin didn't match [**/index.html] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/classes/com.vmware.tap.accelerators.javaserversideui.web.IndexControllerTest$Get.html didn't match [**/index.html] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/executionHistory/executionHistory.bin didn't match [**/index.html] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/binary/output.bin didn't match [**/index.html] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileHashes/fileHashes.bin didn't match [**/index.html] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml didn't match [**/index.html] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/checksums/md5-checksums.bin didn't match [**/index.html] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/checksums/checksums.lock didn't match [**/index.html] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/classes/com.vmware.tap.accelerators.javaserversideui.ApplicationTest.html didn't match [**/index.html] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/gc.properties didn't match [**/index.html] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/application.yml didn't match [**/index.html] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resolvedMainClassName didn't match [**/index.html] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/index.html matched [**/index.html] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/dependencies-accessors/dependencies-accessors.lock didn't match [**/index.html] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vmware/tap/accelerators/javaserversideui/Application.java didn't match [**/index.html] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/application.yml didn't match [**/index.html] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [**/index.html] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug config/workload.yaml didn't match [**/index.html] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug FRAGMENT_README.md didn't match [**/index.html] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/vcs.xml didn't match [**/index.html] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/workspace.xml didn't match [**/index.html] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/com/vmware/tap/fragments/appssoauthcodeflow/TestWebSecurityConfiguration.java didn't match [**/index.html] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/com/vmware/tap/fragments/appssoauthcodeflow/web/OidcUserControllerTest.java didn't match [**/index.html] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/protected/profile.html didn't match [**/index.html] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/application-local.yml didn't match [**/index.html] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vmware/tap/fragments/appssoauthcodeflow/web/OidcUserController.java didn't match [**/index.html] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ Debug src/main/java/com/vmware/tap/fragments/appssoauthcodeflow/WebSecurityConfiguration.java didn't match [**/index.html] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[5].delegate.transformations[0].sources[0].validated.delegate.transformations[0].sources[2].delegate.transformations[1] (ReplaceText)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ ┗  Info Will replace regex '(?<existingContent>[\S\s]*)(?<closingTag></body>[\S\s]*)' with '${existingContent}<!...(truncated)'
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[5].delegate.transformations[0].sources[0].validated.delegate.transformations[0].sources[3] (Combo)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Combo running as Chain
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.delegate.in.transformations[5].delegate.transformations[0].sources[0].validated.delegate.transformations[0].sources[3].delegate (Chain)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Running Chain(Include, ReplaceText, ReplaceText, ReplaceText)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[5].delegate.transformations[0].sources[0].validated.delegate.transformations[0].sources[3].delegate.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Will include [pom.xml]
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vmware/tap/accelerators/javaserversideui/web/IndexController.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/packages/com.vmware.tap.accelerators.javaserversideui.web.html didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/buildOutputCleanup/buildOutputCleanup.lock didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/css/base-style.css didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/binary/output.bin.idx didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/tmp/bootJar/MANIFEST.MF didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/executionHistory/executionHistory.lock didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/js/report.js didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/misc.xml didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/templates/index.html didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/maven-status/maven-compiler-plugin/compile/default-compile/createdFiles.lst didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/workspace.xml didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/styles/bootstrap-custom.css didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/main/com/vmware/tap/accelerators/javaserversideui/web/IndexController.class didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/libs/java-server-side-ui-0.0.1-SNAPSHOT.jar didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/gradle.xml didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/buildOutputCleanup/cache.properties didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/TEST-com.vmware.tap.accelerators.javaserversideui.web.IndexControllerTest.xml didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug LICENSE didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/file-system.probe didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/maven-status/maven-compiler-plugin/compile/default-compile/inputFiles.lst didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradlew didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/binary/results.bin didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/jarRepositories.xml didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/templates/index.html didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/.gitignore didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/checksums/sha1-checksums.bin didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/TEST-com.vmware.tap.accelerators.javaserversideui.ApplicationTest.xml didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileHashes/fileHashes.lock didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/compiler.xml didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/test-classes/com/vmware/tap/accelerators/javaserversideui/ApplicationTest.class didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/com/vmware/tap/accelerators/javaserversideui/ApplicationTest.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/test/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest$Get.class didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gitignore didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/com/vmware/tap/accelerators/javaserversideui/web/IndexController.class didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/vcs-1/gc.properties didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradle/wrapper/gradle-wrapper.jar didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/main/com/vmware/tap/accelerators/javaserversideui/Application.class didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradle/wrapper/gradle-wrapper.properties didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileChanges/last-build.bin didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/TEST-com.vmware.tap.accelerators.javaserversideui.web.IndexControllerTest$Get.xml didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/css/style.css didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug pom.xml matched [pom.xml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/classes/com.vmware.tap.accelerators.javaserversideui.web.IndexControllerTest.html didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/static/styles/bootstrap-custom.css didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/maven-status/maven-compiler-plugin/testCompile/default-testCompile/createdFiles.lst didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/vcs.xml didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/test-classes/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest$Get.class didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/test/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest.class didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/test/com/vmware/tap/accelerators/javaserversideui/ApplicationTest.class didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/dependencies-accessors/gc.properties didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .tanzuignore didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/static/styles/bootstrap-custom.css didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/packages/com.vmware.tap.accelerators.javaserversideui.html didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .grype.yaml didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/tmp/compileTestJava/previous-compilation-data.bin didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/application.yml didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/index.html didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/com/vmware/tap/accelerators/javaserversideui/Application.class didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/maven-status/maven-compiler-plugin/testCompile/default-testCompile/inputFiles.lst didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/tmp/compileJava/previous-compilation-data.bin didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileHashes/resourceHashesCache.bin didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/test-classes/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest.class didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/buildOutputCleanup/outputFiles.bin didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/classes/com.vmware.tap.accelerators.javaserversideui.web.IndexControllerTest$Get.html didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/executionHistory/executionHistory.bin didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/binary/output.bin didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileHashes/fileHashes.bin didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/checksums/md5-checksums.bin didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/checksums/checksums.lock didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/classes/com.vmware.tap.accelerators.javaserversideui.ApplicationTest.html didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/gc.properties didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/application.yml didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resolvedMainClassName didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/index.html didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/dependencies-accessors/dependencies-accessors.lock didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vmware/tap/accelerators/javaserversideui/Application.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/application.yml didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug config/workload.yaml didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug FRAGMENT_README.md didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/vcs.xml didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/workspace.xml didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/com/vmware/tap/fragments/appssoauthcodeflow/TestWebSecurityConfiguration.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/com/vmware/tap/fragments/appssoauthcodeflow/web/OidcUserControllerTest.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/protected/profile.html didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/application-local.yml didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vmware/tap/fragments/appssoauthcodeflow/web/OidcUserController.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ Debug src/main/java/com/vmware/tap/fragments/appssoauthcodeflow/WebSecurityConfiguration.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[5].delegate.transformations[0].sources[0].validated.delegate.transformations[0].sources[3].delegate.transformations[1] (ReplaceText)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗  Info Will replace regex '(?<startOfDependencies><dependencies>)(?<existingDependencies>(?![\s\S]+<artifactId>spring-boot-starter-thymeleaf</artifactId>[\s\S]+</dependencies>))' with '${startOfDependencie...(truncated)'
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[5].delegate.transformations[0].sources[0].validated.delegate.transformations[0].sources[3].delegate.transformations[2] (ReplaceText)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗  Info Will replace regex '(?<startOfDependencies><dependencies>)(?<existingDependencies>(?![\s\S]+<artifactId>spring-boot-starter-oauth2-client</artifactId>[\s\S]+</dependencies>))' with '${startOfDependencie...(truncated)'
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[5].delegate.transformations[0].sources[0].validated.delegate.transformations[0].sources[3].delegate.transformations[3] (ReplaceText)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ ┗  Info Will replace regex '(?<startOfDependencies><dependencies>)(?<existingDependencies>(?![\s\S]+<artifactId>spring-security-test</artifactId>[\s\S]+</dependencies>))' with '${startOfDependencie...(truncated)'
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[5].delegate.transformations[0].sources[0].validated.delegate.transformations[0].sources[4] (Combo)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Combo running as Chain
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.delegate.in.transformations[5].delegate.transformations[0].sources[0].validated.delegate.transformations[0].sources[4].delegate (Chain)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Running Chain(Include, ReplaceText, ReplaceText, ReplaceText)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[5].delegate.transformations[0].sources[0].validated.delegate.transformations[0].sources[4].delegate.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Will include [build.gradle.kts]
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vmware/tap/accelerators/javaserversideui/web/IndexController.java didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/packages/com.vmware.tap.accelerators.javaserversideui.web.html didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/buildOutputCleanup/buildOutputCleanup.lock didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/css/base-style.css didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest.java didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/binary/output.bin.idx didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/tmp/bootJar/MANIFEST.MF didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/executionHistory/executionHistory.lock didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/js/report.js didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/misc.xml didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/templates/index.html didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/maven-status/maven-compiler-plugin/compile/default-compile/createdFiles.lst didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/workspace.xml didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/styles/bootstrap-custom.css didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/main/com/vmware/tap/accelerators/javaserversideui/web/IndexController.class didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/libs/java-server-side-ui-0.0.1-SNAPSHOT.jar didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/gradle.xml didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/buildOutputCleanup/cache.properties didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/TEST-com.vmware.tap.accelerators.javaserversideui.web.IndexControllerTest.xml didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug LICENSE didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/file-system.probe didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/maven-status/maven-compiler-plugin/compile/default-compile/inputFiles.lst didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradlew didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/binary/results.bin didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/jarRepositories.xml didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/templates/index.html didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/.gitignore didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/checksums/sha1-checksums.bin didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/TEST-com.vmware.tap.accelerators.javaserversideui.ApplicationTest.xml didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileHashes/fileHashes.lock didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/compiler.xml didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/test-classes/com/vmware/tap/accelerators/javaserversideui/ApplicationTest.class didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/com/vmware/tap/accelerators/javaserversideui/ApplicationTest.java didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/test/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest$Get.class didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gitignore didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/com/vmware/tap/accelerators/javaserversideui/web/IndexController.class didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/vcs-1/gc.properties didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradle/wrapper/gradle-wrapper.jar didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/main/com/vmware/tap/accelerators/javaserversideui/Application.class didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradle/wrapper/gradle-wrapper.properties didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileChanges/last-build.bin didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/TEST-com.vmware.tap.accelerators.javaserversideui.web.IndexControllerTest$Get.xml didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/css/style.css didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug pom.xml didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/classes/com.vmware.tap.accelerators.javaserversideui.web.IndexControllerTest.html didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/static/styles/bootstrap-custom.css didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/maven-status/maven-compiler-plugin/testCompile/default-testCompile/createdFiles.lst didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/vcs.xml didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/test-classes/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest$Get.class didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/test/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest.class didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/test/com/vmware/tap/accelerators/javaserversideui/ApplicationTest.class didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/dependencies-accessors/gc.properties didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .tanzuignore didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/static/styles/bootstrap-custom.css didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/packages/com.vmware.tap.accelerators.javaserversideui.html didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .grype.yaml didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/tmp/compileTestJava/previous-compilation-data.bin didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/application.yml didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/index.html didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/com/vmware/tap/accelerators/javaserversideui/Application.class didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/maven-status/maven-compiler-plugin/testCompile/default-testCompile/inputFiles.lst didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/tmp/compileJava/previous-compilation-data.bin didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileHashes/resourceHashesCache.bin didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/test-classes/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest.class didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/buildOutputCleanup/outputFiles.bin didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/classes/com.vmware.tap.accelerators.javaserversideui.web.IndexControllerTest$Get.html didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/executionHistory/executionHistory.bin didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/binary/output.bin didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileHashes/fileHashes.bin didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/checksums/md5-checksums.bin didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/checksums/checksums.lock didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/classes/com.vmware.tap.accelerators.javaserversideui.ApplicationTest.html didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/gc.properties didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/application.yml didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resolvedMainClassName didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/index.html didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/dependencies-accessors/dependencies-accessors.lock didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vmware/tap/accelerators/javaserversideui/Application.java didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/application.yml didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug config/workload.yaml didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug FRAGMENT_README.md didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/vcs.xml didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/workspace.xml didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/com/vmware/tap/fragments/appssoauthcodeflow/TestWebSecurityConfiguration.java didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/com/vmware/tap/fragments/appssoauthcodeflow/web/OidcUserControllerTest.java didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/protected/profile.html didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/application-local.yml didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vmware/tap/fragments/appssoauthcodeflow/web/OidcUserController.java didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ Debug src/main/java/com/vmware/tap/fragments/appssoauthcodeflow/WebSecurityConfiguration.java didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[5].delegate.transformations[0].sources[0].validated.delegate.transformations[0].sources[4].delegate.transformations[1] (ReplaceText)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗  Info Will replace regex '(?<startOfDependencies>dependencies \{)(?<existingDependencies>(?![\s\S]+implementation\("org.springframework.boot:spring-boot-starter-thymeleaf"\)[\s\S]+))' with '${startOfDependencie...(truncated)'
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[5].delegate.transformations[0].sources[0].validated.delegate.transformations[0].sources[4].delegate.transformations[2] (ReplaceText)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗  Info Will replace regex '(?<startOfDependencies>dependencies \{)(?<existingDependencies>(?![\s\S]+implementation("org.springframework.boot:spring-boot-starter-oauth2-client")[\s\S]+))' with '${startOfDependencie...(truncated)'
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[5].delegate.transformations[0].sources[0].validated.delegate.transformations[0].sources[4].delegate.transformations[3] (ReplaceText)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ ┗  Info Will replace regex '(?<startOfDependencies>dependencies \{)(?<existingDependencies>(?![\s\S]+implementation("org.springframework.security:spring-security-test")[\s\S]+))' with '${startOfDependencie...(truncated)'
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[5].delegate.transformations[0].sources[0].validated.delegate.transformations[0].sources[5] (Combo)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Combo running as Chain
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.delegate.in.transformations[5].delegate.transformations[0].sources[0].validated.delegate.transformations[0].sources[5].delegate (Chain)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Running Chain(Include, ReplaceText)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[5].delegate.transformations[0].sources[0].validated.delegate.transformations[0].sources[5].delegate.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Will include [README.md]
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vmware/tap/accelerators/javaserversideui/web/IndexController.java didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/packages/com.vmware.tap.accelerators.javaserversideui.web.html didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/buildOutputCleanup/buildOutputCleanup.lock didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/css/base-style.css didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest.java didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/binary/output.bin.idx didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/tmp/bootJar/MANIFEST.MF didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/executionHistory/executionHistory.lock didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/js/report.js didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/misc.xml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/templates/index.html didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/maven-status/maven-compiler-plugin/compile/default-compile/createdFiles.lst didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/workspace.xml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/styles/bootstrap-custom.css didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/main/com/vmware/tap/accelerators/javaserversideui/web/IndexController.class didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/libs/java-server-side-ui-0.0.1-SNAPSHOT.jar didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/gradle.xml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/buildOutputCleanup/cache.properties didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/TEST-com.vmware.tap.accelerators.javaserversideui.web.IndexControllerTest.xml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug LICENSE didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/file-system.probe didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/maven-status/maven-compiler-plugin/compile/default-compile/inputFiles.lst didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradlew didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/binary/results.bin didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/jarRepositories.xml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/templates/index.html didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/.gitignore didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/checksums/sha1-checksums.bin didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/TEST-com.vmware.tap.accelerators.javaserversideui.ApplicationTest.xml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileHashes/fileHashes.lock didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/compiler.xml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/test-classes/com/vmware/tap/accelerators/javaserversideui/ApplicationTest.class didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/com/vmware/tap/accelerators/javaserversideui/ApplicationTest.java didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/test/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest$Get.class didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gitignore didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/com/vmware/tap/accelerators/javaserversideui/web/IndexController.class didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/vcs-1/gc.properties didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradle/wrapper/gradle-wrapper.jar didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/main/com/vmware/tap/accelerators/javaserversideui/Application.class didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradle/wrapper/gradle-wrapper.properties didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileChanges/last-build.bin didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/TEST-com.vmware.tap.accelerators.javaserversideui.web.IndexControllerTest$Get.xml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/css/style.css didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug pom.xml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/classes/com.vmware.tap.accelerators.javaserversideui.web.IndexControllerTest.html didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/static/styles/bootstrap-custom.css didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/maven-status/maven-compiler-plugin/testCompile/default-testCompile/createdFiles.lst didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/vcs.xml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/test-classes/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest$Get.class didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/test/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest.class didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/test/com/vmware/tap/accelerators/javaserversideui/ApplicationTest.class didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/dependencies-accessors/gc.properties didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .tanzuignore didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/static/styles/bootstrap-custom.css didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/packages/com.vmware.tap.accelerators.javaserversideui.html didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .grype.yaml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/tmp/compileTestJava/previous-compilation-data.bin didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/application.yml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/index.html didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/com/vmware/tap/accelerators/javaserversideui/Application.class didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/maven-status/maven-compiler-plugin/testCompile/default-testCompile/inputFiles.lst didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/tmp/compileJava/previous-compilation-data.bin didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileHashes/resourceHashesCache.bin didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/test-classes/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest.class didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/buildOutputCleanup/outputFiles.bin didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/classes/com.vmware.tap.accelerators.javaserversideui.web.IndexControllerTest$Get.html didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/executionHistory/executionHistory.bin didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/binary/output.bin didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileHashes/fileHashes.bin didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/checksums/md5-checksums.bin didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/checksums/checksums.lock didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/classes/com.vmware.tap.accelerators.javaserversideui.ApplicationTest.html didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/gc.properties didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/application.yml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resolvedMainClassName didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/index.html didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/dependencies-accessors/dependencies-accessors.lock didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vmware/tap/accelerators/javaserversideui/Application.java didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/application.yml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug README.md matched [README.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug config/workload.yaml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug FRAGMENT_README.md didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/vcs.xml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/workspace.xml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/com/vmware/tap/fragments/appssoauthcodeflow/TestWebSecurityConfiguration.java didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/com/vmware/tap/fragments/appssoauthcodeflow/web/OidcUserControllerTest.java didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/protected/profile.html didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/application-local.yml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vmware/tap/fragments/appssoauthcodeflow/web/OidcUserController.java didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ Debug src/main/java/com/vmware/tap/fragments/appssoauthcodeflow/WebSecurityConfiguration.java didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[5].delegate.transformations[0].sources[0].validated.delegate.transformations[0].sources[5].delegate.transformations[1] (ReplaceText)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Will replace regex '(?<existingContent>[\s\S]*)(?<endOfFile>
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info )' with '${existingContent}
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info 
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ ┗ ┗  Info ...(truncated)'
┃ ┃ ┃ ┃ ┃ ┃ ┗ ┗ ╺ engine.transformations[0].validated.delegate.in.transformations[5].delegate.transformations[0].sources[0].validated.delegate.transformations[1] (UniquePath)
┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[5].delegate.transformations[0].sources[1] (Combo)
┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Combo running as Include
┃ ┃ ┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.delegate.in.transformations[5].delegate.transformations[0].sources[1].delegate (Include)
┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Will include [**]
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vmware/tap/accelerators/javaserversideui/web/IndexController.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/packages/com.vmware.tap.accelerators.javaserversideui.web.html matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/buildOutputCleanup/buildOutputCleanup.lock matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/css/base-style.css matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/binary/output.bin.idx matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/tmp/bootJar/MANIFEST.MF matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/executionHistory/executionHistory.lock matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/js/report.js matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/misc.xml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/templates/index.html matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/maven-status/maven-compiler-plugin/compile/default-compile/createdFiles.lst matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/workspace.xml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/styles/bootstrap-custom.css matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/main/com/vmware/tap/accelerators/javaserversideui/web/IndexController.class matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/libs/java-server-side-ui-0.0.1-SNAPSHOT.jar matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/gradle.xml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/buildOutputCleanup/cache.properties matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/TEST-com.vmware.tap.accelerators.javaserversideui.web.IndexControllerTest.xml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug LICENSE matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/file-system.probe matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/maven-status/maven-compiler-plugin/compile/default-compile/inputFiles.lst matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradlew matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/binary/results.bin matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/jarRepositories.xml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/templates/index.html matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/.gitignore matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/checksums/sha1-checksums.bin matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/TEST-com.vmware.tap.accelerators.javaserversideui.ApplicationTest.xml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileHashes/fileHashes.lock matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/compiler.xml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/test-classes/com/vmware/tap/accelerators/javaserversideui/ApplicationTest.class matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/com/vmware/tap/accelerators/javaserversideui/ApplicationTest.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/test/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest$Get.class matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gitignore matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/com/vmware/tap/accelerators/javaserversideui/web/IndexController.class matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/vcs-1/gc.properties matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradle/wrapper/gradle-wrapper.jar matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/main/com/vmware/tap/accelerators/javaserversideui/Application.class matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradle/wrapper/gradle-wrapper.properties matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileChanges/last-build.bin matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/TEST-com.vmware.tap.accelerators.javaserversideui.web.IndexControllerTest$Get.xml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/css/style.css matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug pom.xml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/classes/com.vmware.tap.accelerators.javaserversideui.web.IndexControllerTest.html matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/static/styles/bootstrap-custom.css matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/maven-status/maven-compiler-plugin/testCompile/default-testCompile/createdFiles.lst matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/vcs.xml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/test-classes/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest$Get.class matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/test/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest.class matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/test/com/vmware/tap/accelerators/javaserversideui/ApplicationTest.class matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/dependencies-accessors/gc.properties matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .tanzuignore matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/static/styles/bootstrap-custom.css matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/packages/com.vmware.tap.accelerators.javaserversideui.html matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .grype.yaml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/tmp/compileTestJava/previous-compilation-data.bin matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/application.yml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/index.html matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/com/vmware/tap/accelerators/javaserversideui/Application.class matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/maven-status/maven-compiler-plugin/testCompile/default-testCompile/inputFiles.lst matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/tmp/compileJava/previous-compilation-data.bin matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileHashes/resourceHashesCache.bin matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/test-classes/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest.class matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/buildOutputCleanup/outputFiles.bin matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/classes/com.vmware.tap.accelerators.javaserversideui.web.IndexControllerTest$Get.html matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/executionHistory/executionHistory.bin matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/binary/output.bin matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileHashes/fileHashes.bin matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/checksums/md5-checksums.bin matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/checksums/checksums.lock matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/classes/com.vmware.tap.accelerators.javaserversideui.ApplicationTest.html matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/gc.properties matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/application.yml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resolvedMainClassName matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/index.html matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/dependencies-accessors/dependencies-accessors.lock matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vmware/tap/accelerators/javaserversideui/Application.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/application.yml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug README.md matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┗ ┗ Debug config/workload.yaml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[5].delegate.transformations[1] (UniquePath)
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'target/classes/templates/index.html', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'build/resources/main/templates/index.html', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'README.md', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'pom.xml', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'src/main/resources/templates/index.html', will use the one appearing first 
┃ ┃ ┃ ┃ ┗ ┗ Debug Multiple representations for path 'build/reports/tests/test/index.html', will use the one appearing first 
┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[6] (Combo)
┃ ┃ ┃ ┃ ┃  Info Condition (#buildTool == 'maven') evaluated to true
┃ ┃ ┃ ┃ ┃  Info Combo running as Chain
┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.delegate.in.transformations[6].delegate (Chain)
┃ ┃ ┃ ┃ ┃  Info Running Chain(Merge, UniquePath)
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[6].delegate.transformations[0] (Merge)
┃ ┃ ┃ ┃ ┃ ┃  Info Running Merge(InvokeFragment, Combo)
┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[6].delegate.transformations[0].sources[0] (InvokeFragment)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[6].delegate.transformations[0].sources[0].validated (Combo)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Combo running as Chain
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.delegate.in.transformations[6].delegate.transformations[0].sources[0].validated.delegate (Chain)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Running Chain(Merge, UniquePath)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[6].delegate.transformations[0].sources[0].validated.delegate.transformations[0] (Merge)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Running Merge(Combo, Combo)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[6].delegate.transformations[0].sources[0].validated.delegate.transformations[0].sources[0] (Combo)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Condition (#liveUpdateIDESupport) evaluated to true
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Combo running as Chain
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.delegate.in.transformations[6].delegate.transformations[0].sources[0].validated.delegate.transformations[0].sources[0].delegate (Chain)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Running Chain(Include, ReplaceText)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[6].delegate.transformations[0].sources[0].validated.delegate.transformations[0].sources[0].delegate.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Will include [Tiltfile]
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/application-local.yml didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/com/example/serversideuistarter/TestWebSecurityConfiguration.java didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vmware/tap/accelerators/javaserversideui/web/IndexController.java didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/packages/com.vmware.tap.accelerators.javaserversideui.web.html didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest.java didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/css/base-style.css didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/buildOutputCleanup/buildOutputCleanup.lock didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/binary/output.bin.idx didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/tmp/bootJar/MANIFEST.MF didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/executionHistory/executionHistory.lock didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/misc.xml didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/js/report.js didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/maven-status/maven-compiler-plugin/compile/default-compile/createdFiles.lst didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/styles/bootstrap-custom.css didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/workspace.xml didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/gradle.xml didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/libs/java-server-side-ui-0.0.1-SNAPSHOT.jar didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/main/com/vmware/tap/accelerators/javaserversideui/web/IndexController.class didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/TEST-com.vmware.tap.accelerators.javaserversideui.web.IndexControllerTest.xml didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/buildOutputCleanup/cache.properties didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/com/example/serversideuistarter/web/OidcUserControllerTest.java didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug LICENSE didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/file-system.probe didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/maven-status/maven-compiler-plugin/compile/default-compile/inputFiles.lst didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradlew didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/jarRepositories.xml didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/binary/results.bin didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/.gitignore didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/checksums/sha1-checksums.bin didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/TEST-com.vmware.tap.accelerators.javaserversideui.ApplicationTest.xml didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/compiler.xml didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileHashes/fileHashes.lock didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/com/vmware/tap/accelerators/javaserversideui/ApplicationTest.java didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/test-classes/com/vmware/tap/accelerators/javaserversideui/ApplicationTest.class didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/test/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest$Get.class didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gitignore didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/protected/profile.html didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/vcs-1/gc.properties didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/com/vmware/tap/accelerators/javaserversideui/web/IndexController.class didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/serversideuistarter/WebSecurityConfiguration.java didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradle/wrapper/gradle-wrapper.jar didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/main/com/vmware/tap/accelerators/javaserversideui/Application.class didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/TEST-com.vmware.tap.accelerators.javaserversideui.web.IndexControllerTest$Get.xml didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileChanges/last-build.bin didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradle/wrapper/gradle-wrapper.properties didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/css/style.css didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/classes/com.vmware.tap.accelerators.javaserversideui.web.IndexControllerTest.html didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/vcs.xml didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/maven-status/maven-compiler-plugin/testCompile/default-testCompile/createdFiles.lst didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/static/styles/bootstrap-custom.css didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/test/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest.class didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/test-classes/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest$Get.class didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/test/com/vmware/tap/accelerators/javaserversideui/ApplicationTest.class didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/dependencies-accessors/gc.properties didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .tanzuignore didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/packages/com.vmware.tap.accelerators.javaserversideui.html didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/static/styles/bootstrap-custom.css didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .grype.yaml didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/tmp/compileTestJava/previous-compilation-data.bin didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/application.yml didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/maven-status/maven-compiler-plugin/testCompile/default-testCompile/inputFiles.lst didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/com/vmware/tap/accelerators/javaserversideui/Application.class didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/serversideuistarter/web/OidcUserController.java didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/tmp/compileJava/previous-compilation-data.bin didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileHashes/resourceHashesCache.bin didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/classes/com.vmware.tap.accelerators.javaserversideui.web.IndexControllerTest$Get.html didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/buildOutputCleanup/outputFiles.bin didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/test-classes/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest.class didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/binary/output.bin didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/executionHistory/executionHistory.bin didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileHashes/fileHashes.bin didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/checksums/md5-checksums.bin didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug config/workload.yaml didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/classes/com.vmware.tap.accelerators.javaserversideui.ApplicationTest.html didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/checksums/checksums.lock didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/gc.properties didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/application.yml didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resolvedMainClassName didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vmware/tap/accelerators/javaserversideui/Application.java didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/dependencies-accessors/dependencies-accessors.lock didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/application.yml didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/templates/index.html didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/templates/index.html didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug pom.xml didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/index.html didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/index.html didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug Tiltfile matched [Tiltfile] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug DEPLOYING.md didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ Debug README.md didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[6].delegate.transformations[0].sources[0].validated.delegate.transformations[0].sources[0].delegate.transformations[1] (ReplaceText)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ ┗  Info Will replace [my-project->server-side-ui-start...(truncated)]
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[6].delegate.transformations[0].sources[0].validated.delegate.transformations[0].sources[1] (Combo)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Condition (#liveUpdateIDESupport) evaluated to true
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Combo running as Chain
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.delegate.in.transformations[6].delegate.transformations[0].sources[0].validated.delegate.transformations[0].sources[1].delegate (Chain)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Running Chain(Include, ReplaceText)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[6].delegate.transformations[0].sources[0].validated.delegate.transformations[0].sources[1].delegate.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Will include [DEPLOYING.md]
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/application-local.yml didn't match [DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/com/example/serversideuistarter/TestWebSecurityConfiguration.java didn't match [DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vmware/tap/accelerators/javaserversideui/web/IndexController.java didn't match [DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/packages/com.vmware.tap.accelerators.javaserversideui.web.html didn't match [DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest.java didn't match [DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/css/base-style.css didn't match [DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/buildOutputCleanup/buildOutputCleanup.lock didn't match [DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/binary/output.bin.idx didn't match [DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/tmp/bootJar/MANIFEST.MF didn't match [DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/executionHistory/executionHistory.lock didn't match [DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/misc.xml didn't match [DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/js/report.js didn't match [DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/maven-status/maven-compiler-plugin/compile/default-compile/createdFiles.lst didn't match [DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/styles/bootstrap-custom.css didn't match [DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/workspace.xml didn't match [DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/gradle.xml didn't match [DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/libs/java-server-side-ui-0.0.1-SNAPSHOT.jar didn't match [DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/main/com/vmware/tap/accelerators/javaserversideui/web/IndexController.class didn't match [DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/TEST-com.vmware.tap.accelerators.javaserversideui.web.IndexControllerTest.xml didn't match [DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/buildOutputCleanup/cache.properties didn't match [DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/com/example/serversideuistarter/web/OidcUserControllerTest.java didn't match [DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug LICENSE didn't match [DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/file-system.probe didn't match [DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/maven-status/maven-compiler-plugin/compile/default-compile/inputFiles.lst didn't match [DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradlew didn't match [DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/jarRepositories.xml didn't match [DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/binary/results.bin didn't match [DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/.gitignore didn't match [DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/checksums/sha1-checksums.bin didn't match [DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/TEST-com.vmware.tap.accelerators.javaserversideui.ApplicationTest.xml didn't match [DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/compiler.xml didn't match [DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileHashes/fileHashes.lock didn't match [DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/com/vmware/tap/accelerators/javaserversideui/ApplicationTest.java didn't match [DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/test-classes/com/vmware/tap/accelerators/javaserversideui/ApplicationTest.class didn't match [DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/test/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest$Get.class didn't match [DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gitignore didn't match [DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/protected/profile.html didn't match [DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/vcs-1/gc.properties didn't match [DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/com/vmware/tap/accelerators/javaserversideui/web/IndexController.class didn't match [DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/serversideuistarter/WebSecurityConfiguration.java didn't match [DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradle/wrapper/gradle-wrapper.jar didn't match [DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/main/com/vmware/tap/accelerators/javaserversideui/Application.class didn't match [DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/TEST-com.vmware.tap.accelerators.javaserversideui.web.IndexControllerTest$Get.xml didn't match [DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileChanges/last-build.bin didn't match [DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradle/wrapper/gradle-wrapper.properties didn't match [DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/css/style.css didn't match [DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/classes/com.vmware.tap.accelerators.javaserversideui.web.IndexControllerTest.html didn't match [DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/vcs.xml didn't match [DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/maven-status/maven-compiler-plugin/testCompile/default-testCompile/createdFiles.lst didn't match [DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/static/styles/bootstrap-custom.css didn't match [DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/test/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest.class didn't match [DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/test-classes/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest$Get.class didn't match [DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/test/com/vmware/tap/accelerators/javaserversideui/ApplicationTest.class didn't match [DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/dependencies-accessors/gc.properties didn't match [DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .tanzuignore didn't match [DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/packages/com.vmware.tap.accelerators.javaserversideui.html didn't match [DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/static/styles/bootstrap-custom.css didn't match [DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .grype.yaml didn't match [DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/tmp/compileTestJava/previous-compilation-data.bin didn't match [DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/application.yml didn't match [DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/maven-status/maven-compiler-plugin/testCompile/default-testCompile/inputFiles.lst didn't match [DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/com/vmware/tap/accelerators/javaserversideui/Application.class didn't match [DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/serversideuistarter/web/OidcUserController.java didn't match [DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/tmp/compileJava/previous-compilation-data.bin didn't match [DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileHashes/resourceHashesCache.bin didn't match [DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/classes/com.vmware.tap.accelerators.javaserversideui.web.IndexControllerTest$Get.html didn't match [DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/buildOutputCleanup/outputFiles.bin didn't match [DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/test-classes/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest.class didn't match [DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/binary/output.bin didn't match [DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/executionHistory/executionHistory.bin didn't match [DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileHashes/fileHashes.bin didn't match [DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/checksums/md5-checksums.bin didn't match [DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml didn't match [DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug config/workload.yaml didn't match [DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/classes/com.vmware.tap.accelerators.javaserversideui.ApplicationTest.html didn't match [DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/checksums/checksums.lock didn't match [DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/gc.properties didn't match [DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/application.yml didn't match [DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resolvedMainClassName didn't match [DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vmware/tap/accelerators/javaserversideui/Application.java didn't match [DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/dependencies-accessors/dependencies-accessors.lock didn't match [DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/application.yml didn't match [DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/templates/index.html didn't match [DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/templates/index.html didn't match [DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug pom.xml didn't match [DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/index.html didn't match [DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/index.html didn't match [DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug Tiltfile didn't match [DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug DEPLOYING.md matched [DEPLOYING.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ Debug README.md didn't match [DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[6].delegate.transformations[0].sources[0].validated.delegate.transformations[0].sources[1].delegate.transformations[1] (ReplaceText)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ ┗ ┗  Info Will replace [my-project->server-side-ui-start...(truncated)]
┃ ┃ ┃ ┃ ┃ ┃ ┗ ┗ ╺ engine.transformations[0].validated.delegate.in.transformations[6].delegate.transformations[0].sources[0].validated.delegate.transformations[1] (UniquePath)
┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[6].delegate.transformations[0].sources[1] (Combo)
┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Combo running as Include
┃ ┃ ┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.delegate.in.transformations[6].delegate.transformations[0].sources[1].delegate (Include)
┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Will include [**]
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/application-local.yml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/com/example/serversideuistarter/TestWebSecurityConfiguration.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vmware/tap/accelerators/javaserversideui/web/IndexController.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/packages/com.vmware.tap.accelerators.javaserversideui.web.html matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/css/base-style.css matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/buildOutputCleanup/buildOutputCleanup.lock matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/binary/output.bin.idx matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/tmp/bootJar/MANIFEST.MF matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/executionHistory/executionHistory.lock matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/misc.xml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/js/report.js matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/maven-status/maven-compiler-plugin/compile/default-compile/createdFiles.lst matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/styles/bootstrap-custom.css matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/workspace.xml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/gradle.xml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/libs/java-server-side-ui-0.0.1-SNAPSHOT.jar matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/main/com/vmware/tap/accelerators/javaserversideui/web/IndexController.class matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/TEST-com.vmware.tap.accelerators.javaserversideui.web.IndexControllerTest.xml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/buildOutputCleanup/cache.properties matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/com/example/serversideuistarter/web/OidcUserControllerTest.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug LICENSE matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/file-system.probe matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/maven-status/maven-compiler-plugin/compile/default-compile/inputFiles.lst matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradlew matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/jarRepositories.xml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/binary/results.bin matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/.gitignore matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/checksums/sha1-checksums.bin matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/TEST-com.vmware.tap.accelerators.javaserversideui.ApplicationTest.xml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/compiler.xml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileHashes/fileHashes.lock matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/com/vmware/tap/accelerators/javaserversideui/ApplicationTest.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/test-classes/com/vmware/tap/accelerators/javaserversideui/ApplicationTest.class matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/test/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest$Get.class matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gitignore matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/protected/profile.html matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/vcs-1/gc.properties matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/com/vmware/tap/accelerators/javaserversideui/web/IndexController.class matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/serversideuistarter/WebSecurityConfiguration.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradle/wrapper/gradle-wrapper.jar matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/main/com/vmware/tap/accelerators/javaserversideui/Application.class matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/TEST-com.vmware.tap.accelerators.javaserversideui.web.IndexControllerTest$Get.xml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileChanges/last-build.bin matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradle/wrapper/gradle-wrapper.properties matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/css/style.css matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/classes/com.vmware.tap.accelerators.javaserversideui.web.IndexControllerTest.html matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/vcs.xml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/maven-status/maven-compiler-plugin/testCompile/default-testCompile/createdFiles.lst matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/static/styles/bootstrap-custom.css matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/test/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest.class matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/test-classes/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest$Get.class matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/test/com/vmware/tap/accelerators/javaserversideui/ApplicationTest.class matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/dependencies-accessors/gc.properties matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .tanzuignore matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/packages/com.vmware.tap.accelerators.javaserversideui.html matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/static/styles/bootstrap-custom.css matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .grype.yaml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/tmp/compileTestJava/previous-compilation-data.bin matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/application.yml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/maven-status/maven-compiler-plugin/testCompile/default-testCompile/inputFiles.lst matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/com/vmware/tap/accelerators/javaserversideui/Application.class matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/serversideuistarter/web/OidcUserController.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/tmp/compileJava/previous-compilation-data.bin matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileHashes/resourceHashesCache.bin matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/classes/com.vmware.tap.accelerators.javaserversideui.web.IndexControllerTest$Get.html matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/buildOutputCleanup/outputFiles.bin matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/test-classes/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest.class matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/binary/output.bin matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/executionHistory/executionHistory.bin matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileHashes/fileHashes.bin matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/checksums/md5-checksums.bin matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug config/workload.yaml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/classes/com.vmware.tap.accelerators.javaserversideui.ApplicationTest.html matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/checksums/checksums.lock matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/gc.properties matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/application.yml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resolvedMainClassName matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vmware/tap/accelerators/javaserversideui/Application.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/dependencies-accessors/dependencies-accessors.lock matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/application.yml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/templates/index.html matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/templates/index.html matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug README.md matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug pom.xml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/index.html matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┗ ┗ Debug build/reports/tests/test/index.html matched [**] -> included
┃ ┃ ┃ ┃ ┗ ╺ engine.transformations[0].validated.delegate.in.transformations[6].delegate.transformations[1] (UniquePath)
┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[7] (Combo)
┃ ┃ ┃ ┃ ┃  Info Combo running as Chain
┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.delegate.in.transformations[7].delegate (Chain)
┃ ┃ ┃ ┃ ┃  Info Running Chain(Merge, UniquePath)
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[7].delegate.transformations[0] (Merge)
┃ ┃ ┃ ┃ ┃ ┃  Info Running Merge(InvokeFragment, Combo)
┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[7].delegate.transformations[0].sources[0] (InvokeFragment)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[7].delegate.transformations[0].sources[0].validated (Include)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Will include [**]
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/com/example/serversideuistarter/TestWebSecurityConfiguration.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/application-local.yml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vmware/tap/accelerators/javaserversideui/web/IndexController.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/packages/com.vmware.tap.accelerators.javaserversideui.web.html matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/buildOutputCleanup/buildOutputCleanup.lock matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/css/base-style.css matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/binary/output.bin.idx matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/tmp/bootJar/MANIFEST.MF matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/executionHistory/executionHistory.lock matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/js/report.js matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/misc.xml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/templates/index.html matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/maven-status/maven-compiler-plugin/compile/default-compile/createdFiles.lst matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/workspace.xml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/styles/bootstrap-custom.css matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/main/com/vmware/tap/accelerators/javaserversideui/web/IndexController.class matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/libs/java-server-side-ui-0.0.1-SNAPSHOT.jar matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/gradle.xml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/buildOutputCleanup/cache.properties matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/TEST-com.vmware.tap.accelerators.javaserversideui.web.IndexControllerTest.xml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/com/example/serversideuistarter/web/OidcUserControllerTest.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug LICENSE matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/file-system.probe matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/maven-status/maven-compiler-plugin/compile/default-compile/inputFiles.lst matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradlew matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/binary/results.bin matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/jarRepositories.xml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/templates/index.html matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/.gitignore matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/checksums/sha1-checksums.bin matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug README.md matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/TEST-com.vmware.tap.accelerators.javaserversideui.ApplicationTest.xml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileHashes/fileHashes.lock matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/compiler.xml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/test-classes/com/vmware/tap/accelerators/javaserversideui/ApplicationTest.class matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/com/vmware/tap/accelerators/javaserversideui/ApplicationTest.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/test/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest$Get.class matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/protected/profile.html matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gitignore matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/com/vmware/tap/accelerators/javaserversideui/web/IndexController.class matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/vcs-1/gc.properties matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/serversideuistarter/WebSecurityConfiguration.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradle/wrapper/gradle-wrapper.jar matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/main/com/vmware/tap/accelerators/javaserversideui/Application.class matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradle/wrapper/gradle-wrapper.properties matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileChanges/last-build.bin matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/TEST-com.vmware.tap.accelerators.javaserversideui.web.IndexControllerTest$Get.xml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/css/style.css matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug pom.xml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/classes/com.vmware.tap.accelerators.javaserversideui.web.IndexControllerTest.html matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/static/styles/bootstrap-custom.css matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/maven-status/maven-compiler-plugin/testCompile/default-testCompile/createdFiles.lst matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/vcs.xml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/test-classes/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest$Get.class matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/test/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest.class matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/test/com/vmware/tap/accelerators/javaserversideui/ApplicationTest.class matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/dependencies-accessors/gc.properties matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .tanzuignore matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/static/styles/bootstrap-custom.css matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/packages/com.vmware.tap.accelerators.javaserversideui.html matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .grype.yaml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/tmp/compileTestJava/previous-compilation-data.bin matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/application.yml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/index.html matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/serversideuistarter/web/OidcUserController.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/com/vmware/tap/accelerators/javaserversideui/Application.class matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/maven-status/maven-compiler-plugin/testCompile/default-testCompile/inputFiles.lst matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/tmp/compileJava/previous-compilation-data.bin matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileHashes/resourceHashesCache.bin matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/test-classes/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest.class matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/buildOutputCleanup/outputFiles.bin matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/classes/com.vmware.tap.accelerators.javaserversideui.web.IndexControllerTest$Get.html matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/executionHistory/executionHistory.bin matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/binary/output.bin matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileHashes/fileHashes.bin matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/checksums/md5-checksums.bin matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/checksums/checksums.lock matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/classes/com.vmware.tap.accelerators.javaserversideui.ApplicationTest.html matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug config/workload.yaml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/gc.properties matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/application.yml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug Tiltfile matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug DEPLOYING.md matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resolvedMainClassName matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/index.html matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/dependencies-accessors/dependencies-accessors.lock matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vmware/tap/accelerators/javaserversideui/Application.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/application.yml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug accelerator.axl matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┗ ┗ Debug README.md matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[7].delegate.transformations[0].sources[1] (Combo)
┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Combo running as Include
┃ ┃ ┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.delegate.in.transformations[7].delegate.transformations[0].sources[1].delegate (Include)
┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Will include [**]
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/com/example/serversideuistarter/TestWebSecurityConfiguration.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/application-local.yml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vmware/tap/accelerators/javaserversideui/web/IndexController.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/packages/com.vmware.tap.accelerators.javaserversideui.web.html matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/buildOutputCleanup/buildOutputCleanup.lock matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/css/base-style.css matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/binary/output.bin.idx matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/tmp/bootJar/MANIFEST.MF matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/executionHistory/executionHistory.lock matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/js/report.js matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/misc.xml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/templates/index.html matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/maven-status/maven-compiler-plugin/compile/default-compile/createdFiles.lst matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/workspace.xml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/styles/bootstrap-custom.css matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/main/com/vmware/tap/accelerators/javaserversideui/web/IndexController.class matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/libs/java-server-side-ui-0.0.1-SNAPSHOT.jar matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/gradle.xml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/buildOutputCleanup/cache.properties matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/TEST-com.vmware.tap.accelerators.javaserversideui.web.IndexControllerTest.xml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/com/example/serversideuistarter/web/OidcUserControllerTest.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug LICENSE matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/file-system.probe matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/maven-status/maven-compiler-plugin/compile/default-compile/inputFiles.lst matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradlew matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/binary/results.bin matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/jarRepositories.xml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/templates/index.html matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/.gitignore matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/checksums/sha1-checksums.bin matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug README.md matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/TEST-com.vmware.tap.accelerators.javaserversideui.ApplicationTest.xml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileHashes/fileHashes.lock matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/compiler.xml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/test-classes/com/vmware/tap/accelerators/javaserversideui/ApplicationTest.class matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/com/vmware/tap/accelerators/javaserversideui/ApplicationTest.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/test/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest$Get.class matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/protected/profile.html matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gitignore matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/com/vmware/tap/accelerators/javaserversideui/web/IndexController.class matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/vcs-1/gc.properties matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/serversideuistarter/WebSecurityConfiguration.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradle/wrapper/gradle-wrapper.jar matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/main/com/vmware/tap/accelerators/javaserversideui/Application.class matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradle/wrapper/gradle-wrapper.properties matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileChanges/last-build.bin matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/TEST-com.vmware.tap.accelerators.javaserversideui.web.IndexControllerTest$Get.xml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/css/style.css matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug pom.xml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/classes/com.vmware.tap.accelerators.javaserversideui.web.IndexControllerTest.html matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/static/styles/bootstrap-custom.css matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/maven-status/maven-compiler-plugin/testCompile/default-testCompile/createdFiles.lst matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/vcs.xml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/test-classes/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest$Get.class matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/test/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest.class matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/test/com/vmware/tap/accelerators/javaserversideui/ApplicationTest.class matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/dependencies-accessors/gc.properties matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .tanzuignore matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/static/styles/bootstrap-custom.css matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/packages/com.vmware.tap.accelerators.javaserversideui.html matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .grype.yaml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/tmp/compileTestJava/previous-compilation-data.bin matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/application.yml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/index.html matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/serversideuistarter/web/OidcUserController.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/com/vmware/tap/accelerators/javaserversideui/Application.class matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/maven-status/maven-compiler-plugin/testCompile/default-testCompile/inputFiles.lst matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/tmp/compileJava/previous-compilation-data.bin matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileHashes/resourceHashesCache.bin matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/test-classes/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest.class matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/buildOutputCleanup/outputFiles.bin matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/classes/com.vmware.tap.accelerators.javaserversideui.web.IndexControllerTest$Get.html matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/executionHistory/executionHistory.bin matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/binary/output.bin matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileHashes/fileHashes.bin matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/checksums/md5-checksums.bin matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/checksums/checksums.lock matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/classes/com.vmware.tap.accelerators.javaserversideui.ApplicationTest.html matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug config/workload.yaml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/gc.properties matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/application.yml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug Tiltfile matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug DEPLOYING.md matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resolvedMainClassName matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/index.html matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/dependencies-accessors/dependencies-accessors.lock matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vmware/tap/accelerators/javaserversideui/Application.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┗ ┗ Debug src/main/resources/application.yml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[7].delegate.transformations[1] (UniquePath)
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'src/main/resources/application-local.yml', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'src/test/java/com/example/serversideuistarter/TestWebSecurityConfiguration.java', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/com/vmware/tap/accelerators/javaserversideui/web/IndexController.java', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'build/reports/tests/test/packages/com.vmware.tap.accelerators.javaserversideui.web.html', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'src/test/java/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest.java', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'build/reports/tests/test/css/base-style.css', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path '.gradle/buildOutputCleanup/buildOutputCleanup.lock', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'build/test-results/test/binary/output.bin.idx', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'build/tmp/bootJar/MANIFEST.MF', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path '.gradle/7.5.1/executionHistory/executionHistory.lock', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path '.idea/misc.xml', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'build/reports/tests/test/js/report.js', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'target/classes/templates/index.html', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'target/maven-status/maven-compiler-plugin/compile/default-compile/createdFiles.lst', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'src/main/resources/static/styles/bootstrap-custom.css', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path '.idea/workspace.xml', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path '.idea/gradle.xml', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'build/libs/java-server-side-ui-0.0.1-SNAPSHOT.jar', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'build/classes/java/main/com/vmware/tap/accelerators/javaserversideui/web/IndexController.class', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'build/test-results/test/TEST-com.vmware.tap.accelerators.javaserversideui.web.IndexControllerTest.xml', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path '.gradle/buildOutputCleanup/cache.properties', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'src/test/java/com/example/serversideuistarter/web/OidcUserControllerTest.java', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'LICENSE', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path '.gradle/file-system.probe', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'target/maven-status/maven-compiler-plugin/compile/default-compile/inputFiles.lst', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'gradlew', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path '.idea/jarRepositories.xml', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'build/test-results/test/binary/results.bin', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'build/resources/main/templates/index.html', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path '.idea/.gitignore', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path '.gradle/7.5.1/checksums/sha1-checksums.bin', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'README.md', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'build/test-results/test/TEST-com.vmware.tap.accelerators.javaserversideui.ApplicationTest.xml', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path '.idea/compiler.xml', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path '.gradle/7.5.1/fileHashes/fileHashes.lock', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'src/test/java/com/vmware/tap/accelerators/javaserversideui/ApplicationTest.java', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'target/test-classes/com/vmware/tap/accelerators/javaserversideui/ApplicationTest.class', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'build/classes/java/test/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest$Get.class', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path '.gitignore', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'src/main/resources/templates/protected/profile.html', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path '.gradle/vcs-1/gc.properties', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'target/classes/com/vmware/tap/accelerators/javaserversideui/web/IndexController.class', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/com/example/serversideuistarter/WebSecurityConfiguration.java', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'gradle/wrapper/gradle-wrapper.jar', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'build/classes/java/main/com/vmware/tap/accelerators/javaserversideui/Application.class', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'build/test-results/test/TEST-com.vmware.tap.accelerators.javaserversideui.web.IndexControllerTest$Get.xml', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path '.gradle/7.5.1/fileChanges/last-build.bin', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'gradle/wrapper/gradle-wrapper.properties', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'build/reports/tests/test/css/style.css', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'build/reports/tests/test/classes/com.vmware.tap.accelerators.javaserversideui.web.IndexControllerTest.html', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'pom.xml', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path '.idea/vcs.xml', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'target/maven-status/maven-compiler-plugin/testCompile/default-testCompile/createdFiles.lst', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'target/classes/static/styles/bootstrap-custom.css', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'build/classes/java/test/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest.class', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'target/test-classes/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest$Get.class', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'build/classes/java/test/com/vmware/tap/accelerators/javaserversideui/ApplicationTest.class', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path '.gradle/7.5.1/dependencies-accessors/gc.properties', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path '.tanzuignore', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'build/reports/tests/test/packages/com.vmware.tap.accelerators.javaserversideui.html', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'build/resources/main/static/styles/bootstrap-custom.css', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path '.grype.yaml', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'build/tmp/compileTestJava/previous-compilation-data.bin', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'build/resources/main/application.yml', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'src/main/resources/templates/index.html', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'target/maven-status/maven-compiler-plugin/testCompile/default-testCompile/inputFiles.lst', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'target/classes/com/vmware/tap/accelerators/javaserversideui/Application.class', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/com/example/serversideuistarter/web/OidcUserController.java', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'build/tmp/compileJava/previous-compilation-data.bin', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path '.gradle/7.5.1/fileHashes/resourceHashesCache.bin', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'build/reports/tests/test/classes/com.vmware.tap.accelerators.javaserversideui.web.IndexControllerTest$Get.html', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path '.gradle/buildOutputCleanup/outputFiles.bin', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'target/test-classes/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest.class', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'build/test-results/test/binary/output.bin', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path '.gradle/7.5.1/executionHistory/executionHistory.bin', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path '.gradle/7.5.1/fileHashes/fileHashes.bin', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path '.gradle/7.5.1/checksums/md5-checksums.bin', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'catalog/catalog-info.yaml', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'config/workload.yaml', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'build/reports/tests/test/classes/com.vmware.tap.accelerators.javaserversideui.ApplicationTest.html', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path '.gradle/7.5.1/checksums/checksums.lock', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path '.gradle/7.5.1/gc.properties', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'target/classes/application.yml', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'Tiltfile', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'DEPLOYING.md', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'build/resolvedMainClassName', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'build/reports/tests/test/index.html', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/com/vmware/tap/accelerators/javaserversideui/Application.java', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path '.gradle/7.5.1/dependencies-accessors/dependencies-accessors.lock', will use the one appearing first 
┃ ┃ ┃ ┃ ┗ ┗ Debug Multiple representations for path 'src/main/resources/application.yml', will use the one appearing first 
┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[8] (Combo)
┃ ┃ ┃ ┃ ┃  Info Combo running as Chain
┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.delegate.in.transformations[8].delegate (Chain)
┃ ┃ ┃ ┃ ┃  Info Running Chain(Merge, UniquePath)
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[8].delegate.transformations[0] (Merge)
┃ ┃ ┃ ┃ ┃ ┃  Info Running Merge(Combo, Combo)
┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[8].delegate.transformations[0].sources[0] (Combo)
┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Combo running as Chain
┃ ┃ ┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.delegate.in.transformations[8].delegate.transformations[0].sources[0].delegate (Chain)
┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Running Chain(Include, OpenRewriteRecipe)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[8].delegate.transformations[0].sources[0].delegate.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Will include [**/com/vmware/tap/accelerators/javaserversideui/**/*.java]
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug accelerator.axl didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/application-local.yml didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/com/example/serversideuistarter/TestWebSecurityConfiguration.java didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vmware/tap/accelerators/javaserversideui/web/IndexController.java matched [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/packages/com.vmware.tap.accelerators.javaserversideui.web.html didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest.java matched [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/css/base-style.css didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/buildOutputCleanup/buildOutputCleanup.lock didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/binary/output.bin.idx didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/tmp/bootJar/MANIFEST.MF didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/executionHistory/executionHistory.lock didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/misc.xml didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/js/report.js didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/templates/index.html didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/maven-status/maven-compiler-plugin/compile/default-compile/createdFiles.lst didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/styles/bootstrap-custom.css didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/workspace.xml didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/gradle.xml didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/libs/java-server-side-ui-0.0.1-SNAPSHOT.jar didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/main/com/vmware/tap/accelerators/javaserversideui/web/IndexController.class didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/TEST-com.vmware.tap.accelerators.javaserversideui.web.IndexControllerTest.xml didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/buildOutputCleanup/cache.properties didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/com/example/serversideuistarter/web/OidcUserControllerTest.java didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug LICENSE didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/file-system.probe didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/maven-status/maven-compiler-plugin/compile/default-compile/inputFiles.lst didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradlew didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/jarRepositories.xml didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/binary/results.bin didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/templates/index.html didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/.gitignore didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/checksums/sha1-checksums.bin didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/TEST-com.vmware.tap.accelerators.javaserversideui.ApplicationTest.xml didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/compiler.xml didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileHashes/fileHashes.lock didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/com/vmware/tap/accelerators/javaserversideui/ApplicationTest.java matched [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/test-classes/com/vmware/tap/accelerators/javaserversideui/ApplicationTest.class didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/test/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest$Get.class didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gitignore didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/protected/profile.html didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/vcs-1/gc.properties didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/com/vmware/tap/accelerators/javaserversideui/web/IndexController.class didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/serversideuistarter/WebSecurityConfiguration.java didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradle/wrapper/gradle-wrapper.jar didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/main/com/vmware/tap/accelerators/javaserversideui/Application.class didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/TEST-com.vmware.tap.accelerators.javaserversideui.web.IndexControllerTest$Get.xml didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileChanges/last-build.bin didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradle/wrapper/gradle-wrapper.properties didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/css/style.css didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/classes/com.vmware.tap.accelerators.javaserversideui.web.IndexControllerTest.html didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug pom.xml didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/vcs.xml didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/maven-status/maven-compiler-plugin/testCompile/default-testCompile/createdFiles.lst didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/static/styles/bootstrap-custom.css didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/test/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest.class didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/test-classes/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest$Get.class didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/test/com/vmware/tap/accelerators/javaserversideui/ApplicationTest.class didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/dependencies-accessors/gc.properties didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .tanzuignore didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/packages/com.vmware.tap.accelerators.javaserversideui.html didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/static/styles/bootstrap-custom.css didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .grype.yaml didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/tmp/compileTestJava/previous-compilation-data.bin didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/application.yml didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/index.html didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/maven-status/maven-compiler-plugin/testCompile/default-testCompile/inputFiles.lst didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/com/vmware/tap/accelerators/javaserversideui/Application.class didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/serversideuistarter/web/OidcUserController.java didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/tmp/compileJava/previous-compilation-data.bin didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileHashes/resourceHashesCache.bin didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/classes/com.vmware.tap.accelerators.javaserversideui.web.IndexControllerTest$Get.html didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/buildOutputCleanup/outputFiles.bin didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/test-classes/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest.class didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/binary/output.bin didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/executionHistory/executionHistory.bin didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileHashes/fileHashes.bin didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/checksums/md5-checksums.bin didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug config/workload.yaml didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/classes/com.vmware.tap.accelerators.javaserversideui.ApplicationTest.html didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/checksums/checksums.lock didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/gc.properties didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/application.yml didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug Tiltfile didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug DEPLOYING.md didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resolvedMainClassName didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/index.html didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vmware/tap/accelerators/javaserversideui/Application.java matched [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/dependencies-accessors/dependencies-accessors.lock didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ Debug src/main/resources/application.yml didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┗ ╺ engine.transformations[0].validated.delegate.in.transformations[8].delegate.transformations[0].sources[0].delegate.transformations[1] (OpenRewriteRecipe)
┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[8].delegate.transformations[0].sources[1] (Combo)
┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Combo running as Exclude
┃ ┃ ┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.delegate.in.transformations[8].delegate.transformations[0].sources[1].delegate (Exclude)
┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Will exclude [**/com/vmware/tap/accelerators/javaserversideui/**/*.java]
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug accelerator.axl didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/application-local.yml didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/com/example/serversideuistarter/TestWebSecurityConfiguration.java didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vmware/tap/accelerators/javaserversideui/web/IndexController.java matched [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/packages/com.vmware.tap.accelerators.javaserversideui.web.html didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest.java matched [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/css/base-style.css didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/buildOutputCleanup/buildOutputCleanup.lock didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/binary/output.bin.idx didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/tmp/bootJar/MANIFEST.MF didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/executionHistory/executionHistory.lock didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/misc.xml didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/js/report.js didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/templates/index.html didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/maven-status/maven-compiler-plugin/compile/default-compile/createdFiles.lst didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/styles/bootstrap-custom.css didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/workspace.xml didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/gradle.xml didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/libs/java-server-side-ui-0.0.1-SNAPSHOT.jar didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/main/com/vmware/tap/accelerators/javaserversideui/web/IndexController.class didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/TEST-com.vmware.tap.accelerators.javaserversideui.web.IndexControllerTest.xml didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/buildOutputCleanup/cache.properties didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/com/example/serversideuistarter/web/OidcUserControllerTest.java didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug LICENSE didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/file-system.probe didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/maven-status/maven-compiler-plugin/compile/default-compile/inputFiles.lst didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradlew didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/jarRepositories.xml didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/binary/results.bin didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/templates/index.html didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/.gitignore didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/checksums/sha1-checksums.bin didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/TEST-com.vmware.tap.accelerators.javaserversideui.ApplicationTest.xml didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/compiler.xml didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileHashes/fileHashes.lock didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/com/vmware/tap/accelerators/javaserversideui/ApplicationTest.java matched [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/test-classes/com/vmware/tap/accelerators/javaserversideui/ApplicationTest.class didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/test/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest$Get.class didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gitignore didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/protected/profile.html didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/vcs-1/gc.properties didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/com/vmware/tap/accelerators/javaserversideui/web/IndexController.class didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/serversideuistarter/WebSecurityConfiguration.java didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradle/wrapper/gradle-wrapper.jar didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/main/com/vmware/tap/accelerators/javaserversideui/Application.class didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/TEST-com.vmware.tap.accelerators.javaserversideui.web.IndexControllerTest$Get.xml didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileChanges/last-build.bin didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradle/wrapper/gradle-wrapper.properties didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/css/style.css didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/classes/com.vmware.tap.accelerators.javaserversideui.web.IndexControllerTest.html didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug pom.xml didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/vcs.xml didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/maven-status/maven-compiler-plugin/testCompile/default-testCompile/createdFiles.lst didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/static/styles/bootstrap-custom.css didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/test/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest.class didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/test-classes/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest$Get.class didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/test/com/vmware/tap/accelerators/javaserversideui/ApplicationTest.class didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/dependencies-accessors/gc.properties didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .tanzuignore didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/packages/com.vmware.tap.accelerators.javaserversideui.html didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/static/styles/bootstrap-custom.css didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .grype.yaml didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/tmp/compileTestJava/previous-compilation-data.bin didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/application.yml didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/index.html didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/maven-status/maven-compiler-plugin/testCompile/default-testCompile/inputFiles.lst didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/com/vmware/tap/accelerators/javaserversideui/Application.class didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/serversideuistarter/web/OidcUserController.java didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/tmp/compileJava/previous-compilation-data.bin didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileHashes/resourceHashesCache.bin didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/classes/com.vmware.tap.accelerators.javaserversideui.web.IndexControllerTest$Get.html didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/buildOutputCleanup/outputFiles.bin didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/test-classes/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest.class didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/binary/output.bin didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/executionHistory/executionHistory.bin didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileHashes/fileHashes.bin didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/checksums/md5-checksums.bin didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug config/workload.yaml didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/classes/com.vmware.tap.accelerators.javaserversideui.ApplicationTest.html didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/checksums/checksums.lock didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/gc.properties didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/application.yml didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug Tiltfile didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug DEPLOYING.md didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resolvedMainClassName didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/index.html didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vmware/tap/accelerators/javaserversideui/Application.java matched [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/dependencies-accessors/dependencies-accessors.lock didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> included
┃ ┃ ┃ ┃ ┃ ┗ ┗ Debug src/main/resources/application.yml didn't match [**/com/vmware/tap/accelerators/javaserversideui/**/*.java] -> included
┃ ┃ ┃ ┃ ┗ ╺ engine.transformations[0].validated.delegate.in.transformations[8].delegate.transformations[1] (UniquePath)
┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[9] (Combo)
┃ ┃ ┃ ┃ ┃  Info Combo running as Chain
┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.delegate.in.transformations[9].delegate (Chain)
┃ ┃ ┃ ┃ ┃  Info Running Chain(Merge, UniquePath)
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[9].delegate.transformations[0] (Merge)
┃ ┃ ┃ ┃ ┃ ┃  Info Running Merge(Combo, Combo)
┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[9].delegate.transformations[0].sources[0] (Combo)
┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Combo running as Include
┃ ┃ ┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.delegate.in.transformations[9].delegate.transformations[0].sources[0].delegate (Include)
┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Will include [**/*.jar]
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/com/example/serversideuistarter/TestWebSecurityConfiguration.java didn't match [**/*.jar] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/application-local.yml didn't match [**/*.jar] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/packages/com.vmware.tap.accelerators.javaserversideui.web.html didn't match [**/*.jar] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/serversideuistarter/Application.java didn't match [**/*.jar] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/buildOutputCleanup/buildOutputCleanup.lock didn't match [**/*.jar] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/css/base-style.css didn't match [**/*.jar] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/binary/output.bin.idx didn't match [**/*.jar] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/tmp/bootJar/MANIFEST.MF didn't match [**/*.jar] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/executionHistory/executionHistory.lock didn't match [**/*.jar] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/com/example/serversideuistarter/ApplicationTest.java didn't match [**/*.jar] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/js/report.js didn't match [**/*.jar] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/misc.xml didn't match [**/*.jar] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/templates/index.html didn't match [**/*.jar] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/maven-status/maven-compiler-plugin/compile/default-compile/createdFiles.lst didn't match [**/*.jar] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/workspace.xml didn't match [**/*.jar] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/styles/bootstrap-custom.css didn't match [**/*.jar] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug accelerator.axl didn't match [**/*.jar] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/main/com/vmware/tap/accelerators/javaserversideui/web/IndexController.class didn't match [**/*.jar] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/libs/java-server-side-ui-0.0.1-SNAPSHOT.jar matched [**/*.jar] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/gradle.xml didn't match [**/*.jar] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/buildOutputCleanup/cache.properties didn't match [**/*.jar] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/TEST-com.vmware.tap.accelerators.javaserversideui.web.IndexControllerTest.xml didn't match [**/*.jar] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/com/example/serversideuistarter/web/OidcUserControllerTest.java didn't match [**/*.jar] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug LICENSE didn't match [**/*.jar] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/file-system.probe didn't match [**/*.jar] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/maven-status/maven-compiler-plugin/compile/default-compile/inputFiles.lst didn't match [**/*.jar] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradlew didn't match [**/*.jar] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/binary/results.bin didn't match [**/*.jar] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/jarRepositories.xml didn't match [**/*.jar] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/templates/index.html didn't match [**/*.jar] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/.gitignore didn't match [**/*.jar] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/checksums/sha1-checksums.bin didn't match [**/*.jar] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/com/example/serversideuistarter/web/IndexControllerTest.java didn't match [**/*.jar] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [**/*.jar] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/TEST-com.vmware.tap.accelerators.javaserversideui.ApplicationTest.xml didn't match [**/*.jar] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileHashes/fileHashes.lock didn't match [**/*.jar] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/compiler.xml didn't match [**/*.jar] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/test-classes/com/vmware/tap/accelerators/javaserversideui/ApplicationTest.class didn't match [**/*.jar] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/test/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest$Get.class didn't match [**/*.jar] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/protected/profile.html didn't match [**/*.jar] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gitignore didn't match [**/*.jar] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/com/vmware/tap/accelerators/javaserversideui/web/IndexController.class didn't match [**/*.jar] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/vcs-1/gc.properties didn't match [**/*.jar] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/serversideuistarter/WebSecurityConfiguration.java didn't match [**/*.jar] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradle/wrapper/gradle-wrapper.jar matched [**/*.jar] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/main/com/vmware/tap/accelerators/javaserversideui/Application.class didn't match [**/*.jar] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradle/wrapper/gradle-wrapper.properties didn't match [**/*.jar] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileChanges/last-build.bin didn't match [**/*.jar] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/TEST-com.vmware.tap.accelerators.javaserversideui.web.IndexControllerTest$Get.xml didn't match [**/*.jar] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/css/style.css didn't match [**/*.jar] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug pom.xml didn't match [**/*.jar] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/classes/com.vmware.tap.accelerators.javaserversideui.web.IndexControllerTest.html didn't match [**/*.jar] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/static/styles/bootstrap-custom.css didn't match [**/*.jar] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/maven-status/maven-compiler-plugin/testCompile/default-testCompile/createdFiles.lst didn't match [**/*.jar] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/vcs.xml didn't match [**/*.jar] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/test-classes/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest$Get.class didn't match [**/*.jar] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/test/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest.class didn't match [**/*.jar] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/test/com/vmware/tap/accelerators/javaserversideui/ApplicationTest.class didn't match [**/*.jar] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/dependencies-accessors/gc.properties didn't match [**/*.jar] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .tanzuignore didn't match [**/*.jar] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/static/styles/bootstrap-custom.css didn't match [**/*.jar] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/packages/com.vmware.tap.accelerators.javaserversideui.html didn't match [**/*.jar] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .grype.yaml didn't match [**/*.jar] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/tmp/compileTestJava/previous-compilation-data.bin didn't match [**/*.jar] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/application.yml didn't match [**/*.jar] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/index.html didn't match [**/*.jar] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/serversideuistarter/web/OidcUserController.java didn't match [**/*.jar] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/com/vmware/tap/accelerators/javaserversideui/Application.class didn't match [**/*.jar] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/maven-status/maven-compiler-plugin/testCompile/default-testCompile/inputFiles.lst didn't match [**/*.jar] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/tmp/compileJava/previous-compilation-data.bin didn't match [**/*.jar] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileHashes/resourceHashesCache.bin didn't match [**/*.jar] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/test-classes/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest.class didn't match [**/*.jar] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/buildOutputCleanup/outputFiles.bin didn't match [**/*.jar] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/classes/com.vmware.tap.accelerators.javaserversideui.web.IndexControllerTest$Get.html didn't match [**/*.jar] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/executionHistory/executionHistory.bin didn't match [**/*.jar] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/binary/output.bin didn't match [**/*.jar] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileHashes/fileHashes.bin didn't match [**/*.jar] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml didn't match [**/*.jar] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/checksums/md5-checksums.bin didn't match [**/*.jar] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/serversideuistarter/web/IndexController.java didn't match [**/*.jar] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/checksums/checksums.lock didn't match [**/*.jar] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/classes/com.vmware.tap.accelerators.javaserversideui.ApplicationTest.html didn't match [**/*.jar] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug config/workload.yaml didn't match [**/*.jar] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/gc.properties didn't match [**/*.jar] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/application.yml didn't match [**/*.jar] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug Tiltfile didn't match [**/*.jar] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug DEPLOYING.md didn't match [**/*.jar] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resolvedMainClassName didn't match [**/*.jar] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/index.html didn't match [**/*.jar] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/dependencies-accessors/dependencies-accessors.lock didn't match [**/*.jar] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┗ Debug src/main/resources/application.yml didn't match [**/*.jar] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[9].delegate.transformations[0].sources[1] (Combo)
┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Combo running as Chain
┃ ┃ ┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.delegate.in.transformations[9].delegate.transformations[0].sources[1].delegate (Chain)
┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Running Chain(Exclude, ReplaceText)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[9].delegate.transformations[0].sources[1].delegate.transformations[0] (Exclude)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Will exclude [**/*.jar]
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/com/example/serversideuistarter/TestWebSecurityConfiguration.java didn't match [**/*.jar] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/application-local.yml didn't match [**/*.jar] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/packages/com.vmware.tap.accelerators.javaserversideui.web.html didn't match [**/*.jar] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/serversideuistarter/Application.java didn't match [**/*.jar] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/buildOutputCleanup/buildOutputCleanup.lock didn't match [**/*.jar] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/css/base-style.css didn't match [**/*.jar] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/binary/output.bin.idx didn't match [**/*.jar] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/tmp/bootJar/MANIFEST.MF didn't match [**/*.jar] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/executionHistory/executionHistory.lock didn't match [**/*.jar] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/com/example/serversideuistarter/ApplicationTest.java didn't match [**/*.jar] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/js/report.js didn't match [**/*.jar] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/misc.xml didn't match [**/*.jar] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/templates/index.html didn't match [**/*.jar] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/maven-status/maven-compiler-plugin/compile/default-compile/createdFiles.lst didn't match [**/*.jar] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/workspace.xml didn't match [**/*.jar] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/styles/bootstrap-custom.css didn't match [**/*.jar] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug accelerator.axl didn't match [**/*.jar] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/main/com/vmware/tap/accelerators/javaserversideui/web/IndexController.class didn't match [**/*.jar] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/libs/java-server-side-ui-0.0.1-SNAPSHOT.jar matched [**/*.jar] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/gradle.xml didn't match [**/*.jar] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/buildOutputCleanup/cache.properties didn't match [**/*.jar] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/TEST-com.vmware.tap.accelerators.javaserversideui.web.IndexControllerTest.xml didn't match [**/*.jar] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/com/example/serversideuistarter/web/OidcUserControllerTest.java didn't match [**/*.jar] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug LICENSE didn't match [**/*.jar] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/file-system.probe didn't match [**/*.jar] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/maven-status/maven-compiler-plugin/compile/default-compile/inputFiles.lst didn't match [**/*.jar] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradlew didn't match [**/*.jar] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/binary/results.bin didn't match [**/*.jar] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/jarRepositories.xml didn't match [**/*.jar] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/templates/index.html didn't match [**/*.jar] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/.gitignore didn't match [**/*.jar] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/checksums/sha1-checksums.bin didn't match [**/*.jar] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/com/example/serversideuistarter/web/IndexControllerTest.java didn't match [**/*.jar] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [**/*.jar] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/TEST-com.vmware.tap.accelerators.javaserversideui.ApplicationTest.xml didn't match [**/*.jar] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileHashes/fileHashes.lock didn't match [**/*.jar] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/compiler.xml didn't match [**/*.jar] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/test-classes/com/vmware/tap/accelerators/javaserversideui/ApplicationTest.class didn't match [**/*.jar] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/test/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest$Get.class didn't match [**/*.jar] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/protected/profile.html didn't match [**/*.jar] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gitignore didn't match [**/*.jar] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/com/vmware/tap/accelerators/javaserversideui/web/IndexController.class didn't match [**/*.jar] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/vcs-1/gc.properties didn't match [**/*.jar] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/serversideuistarter/WebSecurityConfiguration.java didn't match [**/*.jar] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradle/wrapper/gradle-wrapper.jar matched [**/*.jar] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/main/com/vmware/tap/accelerators/javaserversideui/Application.class didn't match [**/*.jar] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradle/wrapper/gradle-wrapper.properties didn't match [**/*.jar] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileChanges/last-build.bin didn't match [**/*.jar] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/TEST-com.vmware.tap.accelerators.javaserversideui.web.IndexControllerTest$Get.xml didn't match [**/*.jar] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/css/style.css didn't match [**/*.jar] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug pom.xml didn't match [**/*.jar] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/classes/com.vmware.tap.accelerators.javaserversideui.web.IndexControllerTest.html didn't match [**/*.jar] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/static/styles/bootstrap-custom.css didn't match [**/*.jar] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/maven-status/maven-compiler-plugin/testCompile/default-testCompile/createdFiles.lst didn't match [**/*.jar] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/vcs.xml didn't match [**/*.jar] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/test-classes/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest$Get.class didn't match [**/*.jar] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/test/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest.class didn't match [**/*.jar] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/test/com/vmware/tap/accelerators/javaserversideui/ApplicationTest.class didn't match [**/*.jar] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/dependencies-accessors/gc.properties didn't match [**/*.jar] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .tanzuignore didn't match [**/*.jar] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/static/styles/bootstrap-custom.css didn't match [**/*.jar] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/packages/com.vmware.tap.accelerators.javaserversideui.html didn't match [**/*.jar] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .grype.yaml didn't match [**/*.jar] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/tmp/compileTestJava/previous-compilation-data.bin didn't match [**/*.jar] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/application.yml didn't match [**/*.jar] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/index.html didn't match [**/*.jar] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/serversideuistarter/web/OidcUserController.java didn't match [**/*.jar] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/com/vmware/tap/accelerators/javaserversideui/Application.class didn't match [**/*.jar] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/maven-status/maven-compiler-plugin/testCompile/default-testCompile/inputFiles.lst didn't match [**/*.jar] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/tmp/compileJava/previous-compilation-data.bin didn't match [**/*.jar] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileHashes/resourceHashesCache.bin didn't match [**/*.jar] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/test-classes/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest.class didn't match [**/*.jar] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/buildOutputCleanup/outputFiles.bin didn't match [**/*.jar] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/classes/com.vmware.tap.accelerators.javaserversideui.web.IndexControllerTest$Get.html didn't match [**/*.jar] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/executionHistory/executionHistory.bin didn't match [**/*.jar] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/binary/output.bin didn't match [**/*.jar] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileHashes/fileHashes.bin didn't match [**/*.jar] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml didn't match [**/*.jar] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/checksums/md5-checksums.bin didn't match [**/*.jar] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/serversideuistarter/web/IndexController.java didn't match [**/*.jar] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/checksums/checksums.lock didn't match [**/*.jar] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/classes/com.vmware.tap.accelerators.javaserversideui.ApplicationTest.html didn't match [**/*.jar] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug config/workload.yaml didn't match [**/*.jar] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/gc.properties didn't match [**/*.jar] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/application.yml didn't match [**/*.jar] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug Tiltfile didn't match [**/*.jar] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug DEPLOYING.md didn't match [**/*.jar] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resolvedMainClassName didn't match [**/*.jar] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/index.html didn't match [**/*.jar] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/dependencies-accessors/dependencies-accessors.lock didn't match [**/*.jar] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ Debug src/main/resources/application.yml didn't match [**/*.jar] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[9].delegate.transformations[0].sources[1].delegate.transformations[1] (ReplaceText)
┃ ┃ ┃ ┃ ┃ ┗ ┗ ┗  Info Will replace [java-server-side-ui->server-side-ui-start...(truncated)]
┃ ┃ ┃ ┃ ┗ ╺ engine.transformations[0].validated.delegate.in.transformations[9].delegate.transformations[1] (UniquePath)
┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[10] (Combo)
┃ ┃ ┃ ┃ ┃  Info Combo running as Chain
┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.delegate.in.transformations[10].delegate (Chain)
┃ ┃ ┃ ┃ ┃  Info Running Chain(Merge, UniquePath)
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[10].delegate.transformations[0] (Merge)
┃ ┃ ┃ ┃ ┃ ┃  Info Running Merge(Combo, InvokeFragment, InvokeFragment)
┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[10].delegate.transformations[0].sources[0] (Combo)
┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Combo running as Include
┃ ┃ ┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.delegate.in.transformations[10].delegate.transformations[0].sources[0].delegate (Include)
┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Will include [**]
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/application-local.yml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/com/example/serversideuistarter/TestWebSecurityConfiguration.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/serversideuistarter/Application.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/packages/com.vmware.tap.accelerators.javaserversideui.web.html matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/css/base-style.css matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/buildOutputCleanup/buildOutputCleanup.lock matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/binary/output.bin.idx matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/tmp/bootJar/MANIFEST.MF matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/com/example/serversideuistarter/ApplicationTest.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/executionHistory/executionHistory.lock matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/misc.xml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/js/report.js matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/templates/index.html matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/maven-status/maven-compiler-plugin/compile/default-compile/createdFiles.lst matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug accelerator.axl matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/styles/bootstrap-custom.css matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/workspace.xml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/gradle.xml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/main/com/vmware/tap/accelerators/javaserversideui/web/IndexController.class matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/libs/java-server-side-ui-0.0.1-SNAPSHOT.jar matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/TEST-com.vmware.tap.accelerators.javaserversideui.web.IndexControllerTest.xml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/buildOutputCleanup/cache.properties matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/com/example/serversideuistarter/web/OidcUserControllerTest.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug LICENSE matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/file-system.probe matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/maven-status/maven-compiler-plugin/compile/default-compile/inputFiles.lst matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradlew matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/jarRepositories.xml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/binary/results.bin matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/templates/index.html matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/.gitignore matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/com/example/serversideuistarter/web/IndexControllerTest.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/checksums/sha1-checksums.bin matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug README.md matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/TEST-com.vmware.tap.accelerators.javaserversideui.ApplicationTest.xml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/compiler.xml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileHashes/fileHashes.lock matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/test-classes/com/vmware/tap/accelerators/javaserversideui/ApplicationTest.class matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/test/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest$Get.class matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gitignore matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/protected/profile.html matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/vcs-1/gc.properties matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/com/vmware/tap/accelerators/javaserversideui/web/IndexController.class matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/serversideuistarter/WebSecurityConfiguration.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradle/wrapper/gradle-wrapper.jar matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/main/com/vmware/tap/accelerators/javaserversideui/Application.class matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/TEST-com.vmware.tap.accelerators.javaserversideui.web.IndexControllerTest$Get.xml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileChanges/last-build.bin matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradle/wrapper/gradle-wrapper.properties matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/css/style.css matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/classes/com.vmware.tap.accelerators.javaserversideui.web.IndexControllerTest.html matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug pom.xml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/vcs.xml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/maven-status/maven-compiler-plugin/testCompile/default-testCompile/createdFiles.lst matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/static/styles/bootstrap-custom.css matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/test/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest.class matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/test-classes/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest$Get.class matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/test/com/vmware/tap/accelerators/javaserversideui/ApplicationTest.class matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/dependencies-accessors/gc.properties matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .tanzuignore matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/packages/com.vmware.tap.accelerators.javaserversideui.html matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/static/styles/bootstrap-custom.css matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .grype.yaml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/tmp/compileTestJava/previous-compilation-data.bin matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/application.yml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/index.html matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/maven-status/maven-compiler-plugin/testCompile/default-testCompile/inputFiles.lst matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/com/vmware/tap/accelerators/javaserversideui/Application.class matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/serversideuistarter/web/OidcUserController.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/tmp/compileJava/previous-compilation-data.bin matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileHashes/resourceHashesCache.bin matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/classes/com.vmware.tap.accelerators.javaserversideui.web.IndexControllerTest$Get.html matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/buildOutputCleanup/outputFiles.bin matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/test-classes/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest.class matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/binary/output.bin matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/executionHistory/executionHistory.bin matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileHashes/fileHashes.bin matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/checksums/md5-checksums.bin matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/serversideuistarter/web/IndexController.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug config/workload.yaml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/classes/com.vmware.tap.accelerators.javaserversideui.ApplicationTest.html matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/checksums/checksums.lock matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/gc.properties matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/application.yml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug Tiltfile matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug DEPLOYING.md matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resolvedMainClassName matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/index.html matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/dependencies-accessors/dependencies-accessors.lock matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┗ Debug src/main/resources/application.yml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[10].delegate.transformations[0].sources[1] (InvokeFragment)
┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Condition (#buildTool == 'maven') evaluated to true
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[10].delegate.transformations[0].sources[1].validated (Combo)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Combo running as Chain
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.delegate.in.transformations[10].delegate.transformations[0].sources[1].validated.delegate (Chain)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Running Chain(Merge, UniquePath)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[10].delegate.transformations[0].sources[1].validated.delegate.transformations[0] (Merge)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Running Merge(Combo)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[10].delegate.transformations[0].sources[1].validated.delegate.transformations[0].sources[0] (Combo)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Condition (#includeBuildToolWrapper) evaluated to true
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Combo running as Include
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.delegate.in.transformations[10].delegate.transformations[0].sources[1].validated.delegate.transformations[0].sources[0].delegate (Include)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Will include [mvnw, mvnw.cmd, .mvn/**]
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/application-local.yml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/com/example/serversideuistarter/TestWebSecurityConfiguration.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/serversideuistarter/Application.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/packages/com.vmware.tap.accelerators.javaserversideui.web.html didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/css/base-style.css didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/buildOutputCleanup/buildOutputCleanup.lock didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/binary/output.bin.idx didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/tmp/bootJar/MANIFEST.MF didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/com/example/serversideuistarter/ApplicationTest.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/executionHistory/executionHistory.lock didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/misc.xml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/js/report.js didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/templates/index.html didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/maven-status/maven-compiler-plugin/compile/default-compile/createdFiles.lst didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug accelerator.axl didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/styles/bootstrap-custom.css didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/workspace.xml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/gradle.xml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/main/com/vmware/tap/accelerators/javaserversideui/web/IndexController.class didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/libs/java-server-side-ui-0.0.1-SNAPSHOT.jar didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/TEST-com.vmware.tap.accelerators.javaserversideui.web.IndexControllerTest.xml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/buildOutputCleanup/cache.properties didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/com/example/serversideuistarter/web/OidcUserControllerTest.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug LICENSE didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/file-system.probe didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/maven-status/maven-compiler-plugin/compile/default-compile/inputFiles.lst didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradlew didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/jarRepositories.xml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/binary/results.bin didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/templates/index.html didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/.gitignore didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/com/example/serversideuistarter/web/IndexControllerTest.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/checksums/sha1-checksums.bin didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/TEST-com.vmware.tap.accelerators.javaserversideui.ApplicationTest.xml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/compiler.xml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileHashes/fileHashes.lock didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/test-classes/com/vmware/tap/accelerators/javaserversideui/ApplicationTest.class didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/test/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest$Get.class didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gitignore didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/protected/profile.html didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/vcs-1/gc.properties didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/com/vmware/tap/accelerators/javaserversideui/web/IndexController.class didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/serversideuistarter/WebSecurityConfiguration.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradle/wrapper/gradle-wrapper.jar didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/main/com/vmware/tap/accelerators/javaserversideui/Application.class didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/TEST-com.vmware.tap.accelerators.javaserversideui.web.IndexControllerTest$Get.xml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileChanges/last-build.bin didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradle/wrapper/gradle-wrapper.properties didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/css/style.css didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/classes/com.vmware.tap.accelerators.javaserversideui.web.IndexControllerTest.html didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug pom.xml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/vcs.xml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/maven-status/maven-compiler-plugin/testCompile/default-testCompile/createdFiles.lst didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/static/styles/bootstrap-custom.css didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/test/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest.class didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/test-classes/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest$Get.class didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/classes/java/test/com/vmware/tap/accelerators/javaserversideui/ApplicationTest.class didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/dependencies-accessors/gc.properties didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .tanzuignore didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/packages/com.vmware.tap.accelerators.javaserversideui.html didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/static/styles/bootstrap-custom.css didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .grype.yaml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/tmp/compileTestJava/previous-compilation-data.bin didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resources/main/application.yml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/index.html didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/maven-status/maven-compiler-plugin/testCompile/default-testCompile/inputFiles.lst didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/com/vmware/tap/accelerators/javaserversideui/Application.class didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/serversideuistarter/web/OidcUserController.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/tmp/compileJava/previous-compilation-data.bin didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileHashes/resourceHashesCache.bin didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/classes/com.vmware.tap.accelerators.javaserversideui.web.IndexControllerTest$Get.html didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/buildOutputCleanup/outputFiles.bin didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/test-classes/com/vmware/tap/accelerators/javaserversideui/web/IndexControllerTest.class didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/test-results/test/binary/output.bin didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/executionHistory/executionHistory.bin didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/fileHashes/fileHashes.bin didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/checksums/md5-checksums.bin didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/serversideuistarter/web/IndexController.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug config/workload.yaml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/classes/com.vmware.tap.accelerators.javaserversideui.ApplicationTest.html didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/checksums/checksums.lock didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/gc.properties didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/application.yml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug Tiltfile didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug DEPLOYING.md didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/resolvedMainClassName didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build/reports/tests/test/index.html didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/7.5.1/dependencies-accessors/dependencies-accessors.lock didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/application.yml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug mvnw.cmd matched [mvnw, mvnw.cmd, .mvn/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .mvn/wrapper/maven-wrapper.properties matched [mvnw, mvnw.cmd, .mvn/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ ┗ Debug mvnw matched [mvnw, mvnw.cmd, .mvn/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┗ ┗ ╺ engine.transformations[0].validated.delegate.in.transformations[10].delegate.transformations[0].sources[1].validated.delegate.transformations[1] (UniquePath)
┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[10].delegate.transformations[0].sources[2] (InvokeFragment)
┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Condition (#buildTool == 'gradle') evaluated to false
┃ ┃ ┃ ┃ ┃ ┗ ┗ null ()
┃ ┃ ┃ ┃ ┗ ╺ engine.transformations[0].validated.delegate.in.transformations[10].delegate.transformations[1] (UniquePath)
┃ ┗ ┗ ┗ ╺ engine.transformations[0].validated.delegate.in.transformations[11] (Provenance)
┗ ╺ engine.transformations[1] (UniquePath)
```
