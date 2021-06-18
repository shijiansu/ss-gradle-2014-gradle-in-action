## Key files

- settings.gradle
- InMemoryToDoRepositoryTest.java
- repository/build.gradle

## Demo

```bash
gradle wrapper7

# refer to repository/build.gradle for configuration
# only test one of the module
./gradlew :repository:test
> Task :repository:test
com.manning.gia.todo.repository.InMemoryToDoRepositoryTest > testInsertToDoItems STANDARD_OUT
    Creating 20 To Do items.
```
