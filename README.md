# SOpom21
## A simple base POM file for Java 21 projects.

This doesn't include any jer dependencies but this can be used as a parent POM in your Java 21 projects.  
It defines a set of properties that can be directly inherited into your POM file.  

Just clone this project as your abstract POM base and then, use it as the parent POM like:
```xml
  <parent>
    <groupId>com.storedobject</groupId>
    <artifactId>so-pom</artifactId>
    <version>1.0.0</version>
    <relativePath/>
  </parent>
```

