# kiji-mvn-resolver

Maven Repository for kiji related artifacts which are long dead now. To view all the versions and artifacts that we expose via this repo, please visit https://ind9.github.io/kiji-mvn-resolver/index.

## SBT Settings
```sbt
resolvers += "Kiji Maven Repo" at "https://ind9.github.io/kiji-mvn-resolver/",
```

## Maven Settings
```xml
        <repository>
            <id>kiji-maven-repo</id>
            <name>Kiji Maven Repo</name>
            <url>https://ind9.github.io/kiji-mvn-resolver/</url>
        </repository>
```

## To Generate HTML for directory listing

```bash
tree -H baseHREF > index.html
```

