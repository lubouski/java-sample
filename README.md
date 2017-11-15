# Java sample

This code is written on java, and retrieve just a simple output if you build this code to a jar file with gradle/maven tool.

## Getting Started

Repo consists of:
```
build-gradle
``` 
```
src - folder with java code
```
### Prerequisites

install java and gradle build tool. follow the instructions or visit (https://gradle.org/install/)
```
yum install -y java
```
```
java -version
```
```
wget https://services.gradle.org/distributions/gradle-4.3.1-bin.zip
```
```
mkdir /opt/gradle
```
```
unzip -d /opt/gradle gradle-4.3.1-bin.zip
```
```
expot PATH=$PATH:/opt/gradle/gradle-4.3.1/bin
```
```
gradle -v
```

### How to build ?

Just git clone repo to some folder, and then execute command
```
gradle build
```
```
cd build/libs
```
```
java -jar package.jar
```









