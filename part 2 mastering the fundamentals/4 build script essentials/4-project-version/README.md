## Key files

- build.gradle

## Demo

The file gradle.properties needs to be copied to the directory <USER_HOME>/.gradle

```bash
gradle wrapper

./gradlew printVersionDoFirst
Version: 0.1-SNAPSHOT

./gradlew printVersionDoLast
Version: 0.1-SNAPSHOT

./gradlew printVersion
First action
Before reading the project version
Version: 0.1-SNAPSHOT
Last action

```
