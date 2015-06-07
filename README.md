# WordNetLib

WordNetLib is a simple utility wrapper around the MIT WordNet interface.

It is based on [the work by Dmitriy Dligach](https://svn.apache.org/repos/asf/ctakes/trunk/ctakes-relation-extractor/src/main/java/org/apache/ctakes/relationextractor/ae/features/WordNetUtils.java) on behalf of the Apache Software Foundation (ASF) for [Apache cTAKES](http://ctakes.apache.org/).

[Wordnet](http://wordnet.princeton.edu/) is a lexical database developed by Princeton.

# License
The software stands under Apache 2 License and comes with NO WARRANTY

# Usage

First, install the WordNet software on your *nix machine:

On Ubuntu/Debian:
```
sudo apt-get install wordnet
```

NOTE: If you're using a different *nix flavor, the current code expects the Wordnet installation to be at /usr/share/wordnet.

Then, include the repo.
In Gradle:
```
repositories { 
    maven { url "https://jitpack.io" }
}
dependencies {
     compile 'com.github.yaraju:wordnetlib:1.0.0'
}
```

In Maven:

First add the repo at "https://jitpack.io"
Then, in your pom.xml file:
 
 ```xml
 <dependency>
    <groupId>com.github.yaraju</groupId>
    <artifactId>wordnetlib</artifactId>
    <version>1.0.0</version>
 </dependency>
 ```
