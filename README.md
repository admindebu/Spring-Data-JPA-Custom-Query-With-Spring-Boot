# Spring-Data-JPA-Custom-Query-With-Spring-Boot
 I have discussed how to write a custom Query in Spring Data JPA How to use JPQL (Java Persistence Query Language), How to execute SQL query in Spring Boot, and JPA Select query with WHERE condition example.

# Instruction 

Download and extract the files
Java 8
Spring Boot 2.1.1 (with Spring Data JPA)
H2 (embedded in Memory database)
Maven 3.8.1

# Youtube Video with Explanation : https://youtu.be/G9oOidw_oKA

– For MySQL:

spring.datasource.url= jdbc:mysql://localhost:3306/testdb?useSSL=false
spring.datasource.username= root
spring.datasource.password= 123456

spring.jpa.properties.hibernate.dialect= org.hibernate.dialect.MySQL5InnoDBDialect

# Hibernate ddl auto (create, create-drop, validate, update)
spring.jpa.hibernate.ddl-auto= update


– For PostgreSQL:

spring.datasource.url= jdbc:postgresql://localhost:5432/testdb
spring.datasource.username= postgres
spring.datasource.password= 123

spring.jpa.properties.hibernate.jdbc.lob.non_contextual_creation= true
spring.jpa.properties.hibernate.dialect= org.hibernate.dialect.PostgreSQLDialect

# Hibernate ddl auto (create, create-drop, validate, update)
spring.jpa.hibernate.ddl-auto= update
