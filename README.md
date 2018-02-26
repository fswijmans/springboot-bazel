# Springboot-bazel

An simple example of a Application that uses springboot and bazel to build.

## Requirements

Have `bazel` installed. For example, version `0.10.0-homebrew`.

## How to run:
Build the sources with Bazel:
```
bazel build :all
```

And run the jar:
 
``` 
java -jar bazel-genfiles/application_springboot.jar
```

## How to use:

This api exposes [/hello on localhost:8080](http://localhost:8080/hello). You need to login with the username `user` and the password that is generated runtime, which is logged in the output of the jar.

```
Using default security password: 002eca88-78b4-4378-87ed-ef023995d18c
```

