  - Java 8
  - Mojarra 2.3.9.SP10
  - PrimeFaces 6.1
  - RESTEasy 3.12.1.Final
  - Wildfly 20.0.0.Final
  - Apache Maven 3.6.3
  - PostgreSQL 42.2.11
  
  O projeto utiliza a implementação de referência do Java ServerFaces com RESTEasy para JAX-RS por serem as especificações implementadas no container Wildfly.
  
  Para executar em ambiente de desenvolvimento
  
```sh
$ mvn clean package wildfly:run
```
