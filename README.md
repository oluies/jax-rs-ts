jax-rs-ts
=========

test jax-rs

A sample project of a Java web application.
This project is based on:

* [JAX-RS API](https://java.net/projects/jax-rs-spec) - Java API for RESTful services
  * [Jersey](https://jersey.java.net/) - JAX-RS implementation
* [Gradle](http://www.gradle.org/) - Build Automation tool

On this project, an application server used in a development cycle is:

* [Jetty](http://www.eclipse.org/jetty/) - Servlet engine and HTTP server

## Building and running

### Prerequisites

* [JDK](http://www.oracle.com/technetwork/java/javase/downloads/index.html)

### Running on Jetty for development

```
gradlew --daemon jettyRun


### Running tests

```
gradlew --daemon test

## generate idea files
[Using idea plugin](http://www.gradle.org/docs/current/userguide/idea_plugin.html)

```
gradlew idea


