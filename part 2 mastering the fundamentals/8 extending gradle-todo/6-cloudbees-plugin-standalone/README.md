```bash
# cloudbees.properties
implementation-class=com.manning.gia.plugins.cloudbees.CloudBeesPlugin
# because of cloudbees.properties the properties name

apply plugin: 'cloudbees'

gradle uploadArchives
```
