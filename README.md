# kstuff-maven

[![Build Status](https://github.com/pwall567/kstuff-maven/actions/workflows/deploy.yml/badge.svg)](https://github.com/pwall567/kstuff-maven/actions/workflows/deploy.yml)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Kotlin](https://img.shields.io/static/v1?label=Kotlin&message=v1.9.24&color=7f52ff&logo=kotlin&logoColor=7f52ff)](https://github.com/JetBrains/kotlin/releases/tag/v1.9.24)
[![Maven Central](https://img.shields.io/maven-central/v/io.kstuff/kstuff-maven?label=Maven%20Central)](https://search.maven.org/search?q=g:%22io.kstuff%22%20AND%20a:%22kstuff-maven%22)

Maven parent POM for `kstuff` projects

Includes plugin definitions for deployment to Sonatype Central.

The current version is 1.0 &ndash; this version uses Kotlin 1.9.24, and the default Java version is 1.8.

## Usage

```xml
  <parent>
    <groupId>io.kstuff</groupId>
    <artifactId>kstuff-maven</artifactId>
    <version>1.0</version>
  </parent>
```

Peter Wall

2024-11-27
