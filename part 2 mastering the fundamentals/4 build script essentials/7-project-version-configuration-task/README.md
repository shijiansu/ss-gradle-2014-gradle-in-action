## Key files

- build.gradle
- version.properties

## Demo

The file gradle.properties needs to be copied to the directory <USER_HOME>/.gradle

```bash
gradle wrapper7

./gradlew -q printVersion
Reading the version file.
Version: 0.1-SNAPSHOT

./gradlew printVersion 
> Configure project :
Reading the version file.
> Task :printVersion
Version: 0.1-SNAPSHOT

# make "version.properties" to "release=true"
./gradlew printVersion
> Configure project :
Reading the version file.
> Task :printVersion
Version: 0.1
```

## Declaring task inputs and outputs

Gradle determines if a task is up to date by com- paring a snapshot of a task’s inputs and outputs between two builds

- An input can be a directory, 1...n files, or an arbitrary property. 
- A output is defined through a directory or 1...n files.
- Inputs and outputs are defined as fields in class DefaultTask
