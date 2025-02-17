# Spring Framework

Running Application from Command Line

```
java -jar springdi-0.0.1-SNAPSHOT.jar
```

Actuator End Points Config - EndPoints -> info,beans,health

```
management.endpoints.web.exposure.include = *
management.info.env.enabled = true
#management.server.port=9001
info.app.name = SpringDI
info.app.description = Simple Spring project for DI
info.app.version = 1.0.0
```
