# OpenID 2.0 Java Client Library

This project was copied from https://code.google.com/archive/p/jopenid/

JOpenID is an OpenID 2.0 Java 5 implementation for OpenID sign on.

JOpenID is a very lightweight implementation for OpenID 2.0, about 50KB including source & binary.

JOpenID only needs JDK 1.8 (or above) and Servlet 2.3 (or above).

JOpenID is free, with [Apache License](https://www.apache.org/licenses/LICENSE-2.0).

JOpenID is very simple to use. See [Wiki](https://code.google.com/archive/p/jopenid/wikis) for more details.

JOpenID is now in the list of Java libraries on openid.net. You can download or use it in Maven.

It's still open for pull requests and other improvements.

# How to use it

Add this to your `pom.xml`:

```xml
<repository>
    <id>pawelniewie-jopenid-mvn-repo</id>
    <url>https://raw.github.com/pawelniewie/jopenid/mvn-repo/</url>
    <snapshots>
        <enabled>true</enabled>
        <updatePolicy>always</updatePolicy>
    </snapshots>
</repository>
```

```xml
<dependency>
    <groupId>com.pawelniewiadomski</groupId>
    <artifactId>jopenid</artifactId>
    <version>1.11</version>
</dependency>
```

Check the current version in [mvn-repo branch](https://github.com/pawelniewie/jopenid/tree/mvn-repo/com/pawelniewiadomski/jopenid)