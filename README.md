# gradle-simple-publish-gitlab

Example Gradle project producing a single jar. Uses the `maven` plugin to publish the jar to the local repository.

[https://jitpack.io/#jitpack/gradle-simple](https://jitpack.io/#jitpack/gradle-simple)

To install the library add: 
 
   ```gradle
   repositories { 
        jcenter()
        maven { url "https://jitpack.io" }
   }
   dependencies {
         implementation 'com.github.jitpack:gradle-simple:1.1'
   }
   ```  

## Code generation
In the case of a web architecture, the following must be executed:
```
gradle build
```

## Testing execution

For the execution of `unitary` tests, the following must be executed:

```
gradle test
```

## publish artifacts

For the publication of artifacts, the following must be executed:

```
gradle publish
```