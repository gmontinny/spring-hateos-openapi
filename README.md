# springdoc-openapi hateoas



### Opção 1: Construindo JAR Executável
```sh
 mvn clean package
```

### Opção 2: Criando imagens OCI não nativas
```sh
mvn clean spring-boot:build-image
```

## Executando o aplicativo nativo
```sh
docker pull springdocdemos/springdoc-openapi-hateoas-service:latest
docker run --rm -p 8080:8080 springdocdemos/springdoc-openapi-hateoas-service:latest
```
