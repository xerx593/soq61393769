# soq61394451
Answer code for https://stackoverflow.com/q/61393769/592355.

Demonstrates (default) static file locations and handling in spring-boot.

```mvn clean spring-boot:run```

, then navigate to:
- http://localhost:8080/
- http://localhost:8080/index.html
- http://localhost:8080/test.html
- http://localhost:8080/index2.html
- http://localhost:8080/test2.html

# See Also

- https://docs.spring.io/spring-boot/docs/current/reference/html/appendix-application-properties.html :
  -  `spring.resources.static-locations`
  -  `spring.mvc.static-path-pattern`
