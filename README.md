# Spring Boot Security JWT Auth Example App with Spring Security & Spring Data JPA


```
- For MySQL
```
spring.datasource.url= jdbc:mysql://localhost:3306/spring-boot-tutorials-db?useSSL=false
spring.datasource.username= root
spring.datasource.password= MyNewPass

spring.jpa.properties.hibernate.dialect= org.hibernate.dialect.MySQL5InnoDBDialect
spring.jpa.hibernate.ddl-auto= update

# App Properties
security.app.jwt.secret= spring-boot-security-jwt-secretKey
security.app.jwt.expiration= 86400000
```
## Run Spring Boot application
```
mvn spring-boot:run
```

## Run following SQL insert statements
```
INSERT INTO roles(name) VALUES('ROLE_USER');
INSERT INTO roles(name) VALUES('ROLE_ADMIN');
INSERT INTO roles(name) VALUES('ROLE_SUPER_ADMIN');
```
