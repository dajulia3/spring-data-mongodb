Use the following command, substituting your github personal access token in for <TOKEN>:
```./mvnw -s ~/.m2/settings.xml -DskipTests=true -Dregistry=https://maven.pkg.github.com/dajulia3 -Dtoken=<TOKEN> deploy```

Note that the command skips tests so make sure tests pass before running this
