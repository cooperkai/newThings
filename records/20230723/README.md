- windows 10 cmd checksum. default hash-function is sha1
```cmd
certutil -hashfile filename hash-function
```

- mvn package jar exclude file
```xml
<build>
  <plugins>
    <plugin>
      <groupId>org.apache.maven.plugins</groupId>
      <artifactId>maven-jar-plugin</artifactId>
      <version>3.2.0</version>
      <configuration>
        <excludes>
          <!-- your path-->
          <exclude>image/**</exclude>
        </excludes>
      </configuration>
    </plugin>
  </plugins>
</build>
```
