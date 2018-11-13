# Apache-Camel-Demo

This repo was created for a demo of Apache Camel.

Every commit to the master branch on this repo (https://github.com/bchangip) should trigger Camel in order to publish a tweet on **@bchangip** account. Github was chosen as the data source since it's API doesn't have a request limit.

# Components used
- Github
- Twitter

# Notes
The following dependencies were added to fix a bug.
```
<dependency>
    <groupId>org.slf4j</groupId>
    <artifactId>slf4j-api</artifactId>
    <version>1.7.5</version>
</dependency>
<dependency>
    <groupId>org.slf4j</groupId>
    <artifactId>slf4j-simple</artifactId>
    <version>1.6.4</version>
</dependency>
```
