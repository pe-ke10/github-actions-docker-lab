# GitHub Actions Docker Lab

Proyecto sencillo con Spring Boot para practicar CI/CD con GitHub Actions y Docker.

## Requisitos locales

- Java 17
- Maven
- Docker

## Ejecutar localmente

```bash
mvn clean spring-boot:run
```

Abrir:

```text
http://localhost:8080/hello
```

## Ejecutar pruebas

```bash
mvn clean test
```

## Construir JAR

```bash
mvn clean package
```

## Construir imagen Docker

```bash
docker build -t github-actions-docker-lab:latest .
```

## Ejecutar contenedor

```bash
docker run -p 8080:8080 github-actions-docker-lab:latest
```

Abrir:

```text
http://localhost:8080/hello
```
