# SOpom21
## A simple base POM file for Java 21 projects.

This doesn't include any jar dependencies but this can be used as a parent POM in your Java 21 projects.  
It defines a set of properties that can be directly inherited into your POM file.  

Just use this as the parent POM like:
```xml
  <parent>
    <groupId>com.storedobject</groupId>
    <artifactId>so-pom21</artifactId>
    <version>1.1.3</version>
    <relativePath/>
  </parent>
```
Make sure that you have included this in your POM:
```xml
  <pluginRepositories>
    <pluginRepository>
        <id>so-maven</id>
        <url>https://storedobject.com/maven</url>
    </pluginRepository>
</pluginRepositories>
```
