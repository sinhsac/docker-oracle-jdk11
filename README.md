Oracle Java on Docker
=====
Build a Docker image containing Oracle Java (Server JDK specifically).

The Oracle Java Server JDK provides the same features as Oracle Java JDK commonly required for Server-side Applications (i.e. Java EE application servers). For more information about Server JDK, visit the [Understanding the Server JDK](https://www.oracle.com/technetwork/java/javase/jdk-7-readme-429198.html) blog entry from the Java Product Management team.

## Java 11
[Download Server JDK 11](https://www.oracle.com/java/technologies/javase/jdk11-archive-downloads.html) `.tar.gz` file and drop it inside folder `java-oracle-jdk11`. 
Build it:

```
$ cd java-oracle-jdk11
$ docker build -t trinhbiendich/java-oracle-jdk11 .
```


## Usage from docker hub
`FROM trinhbiendich/java-oracle-jdk11`