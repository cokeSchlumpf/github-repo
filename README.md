mvn-repo
========

Maven repositoty for my open source libraries and apps.

SBT
---

Add the following line to your build.sbt to use this repository:

```
resolvers += "wellnr" at "https://raw.github.com/cokeSchlumpf/mvn-repo/master"
```

Maven
-----

Add the following to your pom.xml to use this repository for your maven project:

```XML
<repositories>
    <!-- ... -->
    <repository>
      <id>wellnr</id>
      <url>https://raw.github.com/cokeSchlumpf/mvn-repo/master</url>
    </repository>
    <!-- ... -->
 </repositories>
</project>
```
