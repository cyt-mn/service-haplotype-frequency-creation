# service-haplotype-frequency-creation
Service used for creation of Haplotype Frequency

### Install swagger-codegen

```
brew install swagger-codegen
```

### Generate SpringBoot server

```
swagger-codegen generate -i creation-swagger-spec.yaml -l spring -o /tmp/hfcreate
```

### Build and Run the server

```
cd /tmp/hfcreate
mvn clean package
java -jar target/swagger-spring-1.0.0.jar
```

### Swagger UI
Swagger UI is available at http://localhost:8080
