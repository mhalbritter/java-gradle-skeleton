# Gradle & Java skeleton

This repository contains a starting point for Java projects.

It configures the compiler to use UTF-8, Java 17, and enables reflection on parameters. It also shows deprecated APIs
and fails on warnings. It contains the [Gradle wrapper](https://docs.gradle.org/current/userguide/gradle_wrapper.html).

It includes SLF4J as logging API, logback (with ISO8601 timestamps) as logging backend, JUnit 5 for testing, and AssertJ
for test assertions.

It applies the Gradle `application` plugin so that a runnable distribution is created.

## How to use

Download [the latest version here](https://github.com/mhalbritter/java-gradle-skeleton/archive/master.zip), unzip it,
change `group` and `rootProject.name` in `settings.gradle` and start hacking.

If you're changing the main class (rename the class or move the package), make sure to update `mainClass` property in
the
`application` block in the `build.gradle`.

## Building

Run `./gradlew build` and check the `build` folder.

## Distributing your project

Copy the ZIP or TAR file from the `build/distributions` folder.

## License

Licensed under [CC0](https://creativecommons.org/publicdomain/zero/1.0/) - do whatever you want with it.
