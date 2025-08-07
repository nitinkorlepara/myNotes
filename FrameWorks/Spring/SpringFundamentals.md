# Spring Framework

## Coupling

- Loose Coupling
  - easy to test and debug
  - easy to replace
- Tight Coupling
  - difficult to replace
  - tight relation between components

## Spring container

- BeanFActory
- ApplicationContext

## Spring

- ![Spring](SpringCore.png)
  Running Application from Command Line

```
java -jar springdi-0.0.1-SNAPSHOT.jar
```

Common spring Properties

```
# To turn off the banner
spring.main.banner-mode=off


management.endpoints.web.exposure.include = *
management.info.env.enabled = true
#management.server.port=9001
info.app.name = SpringDI
info.app.description = Simple Spring project for DI
info.app.version = 1.0.0
```

Spring Logging

```
# setting logging level
#logging.level.root=WARN
```
