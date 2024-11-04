# AppcompatError
about "androidx.appcompat:appcompat:1.7.0" error

## title1
```
the version cause error：
gradle plugin version: 7.4.1
gradle version: 7.5
Appcompat version: 1.7.0
```


## title2
```
if you want to run this app:
gradle plugin version: 8.0 +
OR
Appcompat version: 1.6.1
```


## error log of title1
```
AGPBI: {"kind":"error","text":"java.lang.NullPointerException: Cannot invoke \"String.length()\" because \"<parameter1>\" is null","sources":[{"file":"/Users/xxxxxx/.gradle/caches/transforms-3/2c82f2057dce263c323a4d1a858fe61f/transformed/appcompat-resources-1.7.0-runtime.jar"}],"tool":"D8"}
AGPBI: {"kind":"error","text":"java.lang.NullPointerException: Cannot invoke \"String.length()\" because \"<parameter1>\" is null","sources":[{"file":"/Users/xxxxxx/.gradle/caches/transforms-3/28e279e63b4647938608a3e93a1b7dde/transformed/appcompat-1.7.0-runtime.jar"}],"tool":"D8"}

Execution failed for task ':app:mergeExtDexDebug'.
> Could not resolve all files for configuration ':app:debugRuntimeClasspath'.
   > Failed to transform appcompat-resources-1.7.0.aar (androidx.appcompat:appcompat-resources:1.7.0) to match attributes {artifactType=android-dex, asm-transformed-variant=NONE, dexing-enable-desugaring=true, dexing-enable-jacoco-instrumentation=false, dexing-is-debuggable=true, dexing-min-sdk=24, org.gradle.category=library, org.gradle.dependency.bundling=external, org.gradle.libraryelements=aar, org.gradle.status=release, org.gradle.usage=java-runtime}.
      > Execution failed for DexingNoClasspathTransform: /Users/xxxxxx/.gradle/caches/transforms-3/2c82f2057dce263c323a4d1a858fe61f/transformed/appcompat-resources-1.7.0-runtime.jar.
         > Error while dexing.
   > Failed to transform appcompat-1.7.0.aar (androidx.appcompat:appcompat:1.7.0) to match attributes {artifactType=android-dex, asm-transformed-variant=NONE, dexing-enable-desugaring=true, dexing-enable-jacoco-instrumentation=false, dexing-is-debuggable=true, dexing-min-sdk=24, org.gradle.category=library, org.gradle.dependency.bundling=external, org.gradle.libraryelements=aar, org.gradle.status=release, org.gradle.usage=java-runtime}.
      > Execution failed for DexingNoClasspathTransform: /Users/xxxxxx/.gradle/caches/transforms-3/28e279e63b4647938608a3e93a1b7dde/transformed/appcompat-1.7.0-runtime.jar.
         > Error while dexing.

* Try:
> Run with --info or --debug option to get more log output.
> Run with --scan to get full insights.
```
