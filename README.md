Ant Java Demo
==============

Compile, Run, and Jar

```
brew install ant
```

Run:

```
ant
```

or

```
ant run
```

You will see:

```
compile:
    [javac] /Users/freewind/workspace/ant-javac/build.xml:9: warning: 'includeantruntime' was not set, defaulting to build.sysclasspath=last; set to false for repeatable builds
    [javac] Compiling 1 source file to /Users/freewind/workspace/ant-javac/build/classes

run:
     [java] Hello, java

BUILD SUCCESSFUL
Total time: 0 seconds
```

Package a `jar` file and run it:

```
java jar
```

Then:

```
java -jar build/hello.jar
```
