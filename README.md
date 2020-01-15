# Spring Boot 2 Web Starter template

### Download with Giter8

#### Install g8(Giter8) if not exists

[Giter 8 - Setup](http://www.foundweekends.org/giter8/setup.html). For example, on Mac OS X

```
brew install giter8
```

#### Create project based on this template

```
g8 yabqiu/spring-boot8-web-archetype.g8
```

Answer questions, next, next.

### Run this application

```
mvn spring-boot:run
```

### Run this with debug port open

```
mvn spring-boot:run -Drun.jvmArguments="-Xdebug \
-Xrunjdwp:transport=dt_socket,server=y,suspend=y,address=5005"
```

Then any IDE with remote debug support can attach the port 5005
