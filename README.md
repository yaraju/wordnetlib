# WordNetLib

WordNetLib is a simple utility wrapper around the MIT WordNet interface.

It is based on [the work by Dmitriy Dligach](https://svn.apache.org/repos/asf/ctakes/trunk/ctakes-relation-extractor/src/main/java/org/apache/ctakes/relationextractor/ae/features/WordNetUtils.java) on behalf of the Apache Software Foundation (ASF) for [Apache cTAKES](http://ctakes.apache.org/).

[Wordnet](http://wordnet.princeton.edu/) is a lexical database developed by Princeton.

# License
The software stands under Apache 2 License and comes with NO WARRANTY

# Usage

First, install the WordNet software on your *nix machine:

```
sudo apt-get install wordnet
```

Then, include the repo.
In Gradle:
```
repositories { 
    maven { url "https://jitpack.io" }
}
dependencies {
     compile 'com.github.jitpack:gradle-simple:1.0'
}
```

In Maven:

First add the repo at "https://jitpack.io"
Then, in your .pom file:
 
 ```xml
 <dependency>
    <groupId>de.jetwick</groupId>
    <artifactId>snacktory</artifactId>
    <version>1.1</version>
    <!-- or if you prefer the latest build <version>1.2-SNAPSHOT</version> -->
 </dependency>
 ```
