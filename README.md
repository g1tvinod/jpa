# jpa

# Add below properties in application.properties

spring.datasource.url=jdbc:postgresql://localhost:5432/bookapp
spring.datasource.driverClassName=org.postgresql.Driver
spring.datasource.username=postgres
spring.datasource.password=pg
spring.jpa.hibernate.ddl-auto=update
spring.jpa.properties.hibernate.dialect = org.hibernate.dialect.PostgreSQLDialect


