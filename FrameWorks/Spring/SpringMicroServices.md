# Microservices Using Spring or Java

## Synchronous Communication

* Must have a communication address

- RestTemplate + application properties
- Aspect Oriented Communication
- Feign Client
- RestTemplate + ConfigServer

* Methods for Rest template

```
DELETE: delete(String, String...)
GET:    getForObject(String, Class, String...)
POST:   postForLocation(String, Object, String...)
PUT:    put(String, Object, String...)
```

* exchange() method is used to consume the web services for all the HTTP methods

