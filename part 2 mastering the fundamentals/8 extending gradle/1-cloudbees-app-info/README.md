```bash
gradle -PappId=gradle-in-action/todo wrapper7 

# store the private keys in the local
cd $HOME/.gradle
vi gradle.properties

cloudbeesApiKey = Your-CloudBees-API-key
cloudbeesApiSecret = Your-CloudBees-API-secret
appId = dummy

gradle -PappId=gradle-in-action/todo cloudBeesAppInfo
```
