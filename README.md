This fork of robolectric-sqlite allows to run tests for project that are not Android applications.

In order to use this library from you Android project using maven your pom should look like this:

```xml
<?xml version="1.0" encoding="UTF-8"?>
<project ...>
    ...

    <dependencies>
        <dependency>
            <groupId>com.seventheye.android</groupId>
            <artifactId>v</artifactId>
            <version>1.0</version>
            <scope>test</scope>
        </dependency>
        ...
    </dependencies>

    <repositories>
        <repository>
            <id>codeslap</id>
            <url>http://casidiablo.github.com/codeslap-maven/repository/</url>
        </repository>
    </repositories>
</project>
```