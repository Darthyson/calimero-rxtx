# Calimero RXTX provider [![CI with Gradle](https://github.com/calimero-project/calimero-rxtx/actions/workflows/gradle.yml/badge.svg)](https://github.com/calimero-project/calimero-rxtx/actions/workflows/gradle.yml)

Adapter to provide serial access to KNX networks using the RXTX (or any compatible) library.

Simply put the provider on the classpath used by Calimero.

## Download
All Calimero build artifacts are directly downloadable from Maven repositories.

Using git

~~~ sh
git clone https://github.com/calimero-project/calimero-rxtx.git
~~~

Using hub

~~~ sh
hub clone calimero-project/calimero-rxtx
~~~

## Building from Source

With Gradle:

```
gradle build
```

With Maven:

```
mvn clean build
```

## Dependencies

- `calimero-core`
-  `slf4j`
- `com.neuronrobotics:nrjavaserial`
