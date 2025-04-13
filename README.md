# SOpom21
## A simple base POM file for Java 21 projects.

This doesn't include any jar dependencies but this can be used as a parent POM in your Java 21 projects.  
It defines a set of properties that can be directly inherited into your POM file.  

Just use this as the parent POM like:
```xml
  <parent>
    <groupId>com.storedobject</groupId>
    <artifactId>so-pom</artifactId>
    <version>1.0.9</version>
    <relativePath/>
  </parent>
```
Available at jitpack, include it in your repositories' definition:
```xml
<repositories>
    <repository>
        <id>jitpack.io</id>
        <url>https://jitpack.io</url>
    </repository>
</repositories>
```