springboot with vuejs (SPA)

sprignboot랑 연동하기

## Build Step
#### gradle
```
gralde build bootJar
```

#### maven
```
mvn clean install
```

## Run
#### gradle
```
java -jar backend/build/libs/spring-boot-vuejs-spa-1.0-SNAPSHOT.jar
```

#### maven
```
java -jar backend/target/backend-1.0-SNAPSHOT.jar
```

Now go to http://localhost:8080/ and have a look at your first Vue.js Spring Boot App.

