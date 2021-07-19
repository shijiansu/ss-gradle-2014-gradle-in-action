```bash
# APPLYING A PLUGIN BY NAME
apply plugin: 'java'
# APPLYING A PLUGIN BY TYPE
apply plugin: org.gradle.api.plugins.JavaPlugin
# APPLYING AN EXTERNAL PLUGIN
## You can do this by using the buildscript method
buildscript {
   repositories {
      mavenCentral()
   }
dependencies {
  classpath 'org.gradle.api.plugins:gradle-tomcat-plugin:0.9.7'
} }
apply plugin: 'tomcat'
```
