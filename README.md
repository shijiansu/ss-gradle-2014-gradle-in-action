![](https://img.shields.io/badge/development%20year-2021-orange)

## Outline

- Examples are too out-dated, need lots of fixing, just for a very basic learning only

## Source code

- <https://github.com/bmuschko/gradle-in-action-source>

The book publishes at 2014, the GitHub source codes does not update. Going to,

- Fix the code with the latest version of Gradle
- Reorganize the code examples
- Provide more instruction and guiding 

### To understand the Gradle build lifecycle phases

- **initialization phase**
    - create Project instance
- **configuration phase**
    - `incremental build` feature determines if any of tha Tasks in the model requires running
    - prefect for setting up the configuration
    - > any configuration code executes with every build of your proj- ect—even if you just execute gradle tasks
- **execution phase**
    - executed in the correct order

## Execute all tests in repo

`/bin/bash run-repo-test.sh`
