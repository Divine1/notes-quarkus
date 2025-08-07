
```
https://github.com/xstefank

https://quarkus.io/guides/getting-started-reactive
https://quarkus.io/guides/mutiny-primer
https://quarkus.io/guides/
https://smallrye.io/smallrye-mutiny/latest/#navigable

https://quarkus.io/guides/#q=authentication
```

```
https://quarkus.io/guides/cli-tooling
```

```
iex "& { $(iwr https://ps.jbang.dev) } trust add https://repo1.maven.org/maven2/io/quarkus/quarkus-cli/"
iex "& { $(iwr https://ps.jbang.dev) } app install --fresh --force quarkus@quarkusio"
```

```

quarkus create -P io.quarkus.platform:quarkus-bom:3.25.1
quarkus create app --gradle --java=21 --output-directory=firstquarkus --wrapper --code --dockerfiles --name=firstquarkus -P io.quarkus.platform:quarkus-bom:3.25.1 --package-name=com.firstquarkus com:firstquarkus:1.0.0 --dry-run

quarkus create app --gradle --java=21 --wrapper --code --dockerfiles --name=firstquarkus -P io.quarkus.platform:quarkus-bom:3.25.1 --package-name=com.firstquarkus com:firstquarkus:1.0.0 --dry-run
```
