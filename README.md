# Minecraft Version Library

[![](https://jitpack.io/v/xyz.mlserver/MCVersion.svg)](https://jitpack.io/#xyz.mlserver/MCVersion)
[![Twitter](https://badgen.net/twitter/follow/monster_2408?icon=twitter)](https://twitter.com/monster_2408)
[![Discord](https://discord.com/api/guilds/556844677115150366/widget.png)](https://discord.mlserver.xyz)
[Website](https://monster2408.com)

[Java Docs](https://docs.mlserver.jp/MCVersion/)

## Using with Maven

```xml
<repository>
    <id>jitpack.io</id>
    <url>https://jitpack.io</url>
</repository>

<dependency>
    <groupId>xyz.mlserver</groupId>
    <artifactId>MinecraftUtil</artifactId>
    <version>VERSION</version>
</dependency>
```

## Using with Gradle

```gradle
// 
```

## Get MCVersion from ProtocolVersion

```java
MCVersion version = MCVersion.getByProtocolVersion(763);

System.out.println(version.getName()); // 1.20.1
```

### Developer
## JavaDoc Command
```shell
mvn javadoc:javadoc
```