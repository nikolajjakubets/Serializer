Serializer
==========
Simple serialization library.
Based on [L2io](https://github.com/acmi/L2io).

Usage
-----
See [example](src/test/java/acmi/l2/clientmod/io/SerializerTests.java).

Build
-----
```
gradlew build
```
Append `-x test` to skip tests.

Install to local maven repository
---------------------------------
```
gradlew install
```

Maven
-----
```maven
<repository>
    <id>l2io-github</id>
    <url>https://raw.githubusercontent.com/acmi/L2io/mvn-repo</url>
</repository>
<repository>
    <id>serializer-github</id>
    <url>https://raw.githubusercontent.com/acmi/Serializer/mvn-repo</url>
</repository>

<dependency>
    <groupId>acmi.l2.clientmod</groupId>
    <artifactId>serializer</artifactId>
    <version>1.0</version>
</dependency>
```

Gradle
------
```gradle
repositories {
    maven { url "https://raw.githubusercontent.com/acmi/L2io/mvn-repo" }
    maven { url "https://raw.githubusercontent.com/acmi/Serializer/mvn-repo" }
}

dependencies {
    compile group:'acmi.l2.clientmod', name:'serializer', version: '1.0'
}
```