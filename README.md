<a href="https://docs.skrape.it/docs/"><img width="150px" height="150px" align="right" src="skrape.png"/><a/>
<a href="https://docs.spring.io/spring/docs/current/spring-framework-reference/testing.html#spring-mvc-test-framework"><img width="150px" height="150px" align="right" src="spring.png"/><a/>

[![Documentation](https://img.shields.io/badge/skrape%7Bit%7D-docs-blue.svg)](https://docs.skrape.it)
[![maven central](https://img.shields.io/maven-central/v/it.skrape/skrapeit-mockmvc.svg?color=0)](https://search.maven.org/search?q=g:it.skrape%20AND%20a:skrapeit-mockmvc&skrapeit-mockmvc=gav)
[![License](https://img.shields.io/github/license/skrapeit/skrape.it.svg)](https://github.com/skrapeit/skrape.it/blob/master/LICENSE)
[![JDK](https://img.shields.io/badge/jdk-8-green.svg)](http://www.oracle.com/technetwork/java/javase/downloads/index.html)

[![master build status](https://img.shields.io/travis/skrapeit/skrapeit-mockmvc-extension.svg?label=master)](https://travis-ci.org/skrapeit/skrapeit-mockmvc-extension)
[![Known Vulnerabilities](https://snyk.io/test/github/skrapeit/skrapeit-mockmvc-extension/badge.svg?targetFile=pom.xml)](https://snyk.io/test/github/skrapeit/skrapeit-mockmvc-extension?targetFile=pom.xml)
[![Awesome Kotlin Badge](https://kotlin.link/awesome-kotlin.svg)](https://github.com/KotlinBy/awesome-kotlin)

[skrape{it} MockMvc Extension](https://docs.skrape.it)
======================================================

An Extension for [Spring MockMvc](https://docs.spring.io/spring/docs/current/spring-framework-reference/testing.html#spring-mvc-test-framework) tests to enable meaningful testing of controllers that produces HTML.

_**[skrape{it}](http://www.skrape.it)**_ is a Kotlin-based HTML testing and web scraping library
that can be used seamlessly in Spring-Boot, Android or other JVM projects.
It places particular emphasis on ease of use, a high level of readability, 
attention to performance through the use of non-blocking operations and is not 
bound to a specific test runner.

### Setup
> Gradle (Kotlin DSL):
>```
>testCompile("it.skrape:skrapeit-core:+")
>testCompile("it.skrape:skrapeit-mockmvc:+")
>```

> Gradle (Groovy DSL):
>```
>testCompile "it.skrape:skrapeit-core:+"
>testCompile "it.skrape:skrapeit-mockmvc:+"
>```

> Maven:
>```
><dependency>
>   <groupId>it.skrape</groupId>
>   <artifactId>skrapeit-core</artifactId>
>   <version>LATEST</version>
>   <scope>test</scope>
> </dependency>
><dependency>
>   <groupId>it.skrape</groupId>
>   <artifactId>skrapeit-mockmvc</artifactId>
>   <version>LATEST</version>
>   <scope>test</scope>
> </dependency>
>```

### Read the Docs

You'll always find documentation of the latest release at 
**[https://docs.skrape.it](https://docs.skrape.it)**
