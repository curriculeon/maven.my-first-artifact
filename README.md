# RandomUtils
The purpose of this repository is to generate random objects; Floats, Doubles, Longs, Integers, Strings, Dates

## Usage
* This dependency is hosted on [packagecloud.io](https://packagecloud.io/git-leon/utils/packages/java/com.github.git-leon/randomutils-1.0.jar)

### Step 1 - Add Maven Repository to `pom.xml`
* Because this dependency is hosted on a private server, not MavenCentral, the `pom.xml` must be configured to search in the proper repository.

```xml
<repositories>
  <repository>
    <id>git-leon-utils</id>
    <url>https://packagecloud.io/git-leon/utils/maven2</url>
    <releases>
      <enabled>true</enabled>
    </releases>
    <snapshots>
      <enabled>true</enabled>
    </snapshots>
  </repository>
</repositories>
```

### Step 2 - Add Maven Dependency to `pom.xml`
* To use this project, add the dependency to your `pom.xml`

```xml
<dependency>
  <groupId>com.github.git-leon</groupId>
  <artifactId>randomutils</artifactId>
  <version>1.0</version>
</dependency>
```
