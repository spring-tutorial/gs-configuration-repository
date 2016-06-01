* Spring tutorial https://spring.io/guides/gs/centralized-configuration/

Helpful: http://projects.spring.io/spring-cloud/#quick-start

Need:
 - gs-configuration-client
 - gs-configuration-service

Run both.

1. $ curl http://localhost:8080/message;
2. Update file 'a-bootiful-client.properties' and commit changes in this repo.
3. $ curl -X POST http://localhost:8080/refresh
4. $ curl http://localhost:8080/message;
