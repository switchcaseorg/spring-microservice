# spring-microservice

This repository is used only to demonstrate switch-case concept. 

Feel free to reuse it for your project. 

The concept introduces :

* Spring Cloud 
* Spring Eureka
* Spring gateway
* Auth0
* Configuration repo
* Micro-services and composite
* Kubernetes


# What is it?

Spring boot (http://projects.spring.io/spring-boot) is an interesting projetc, that aims at simplifying Spring project setup. At this point, though (version 0.5.0.M5) the documentation is a bit lacking, so it's not that easy to use. 

So if you have no experience with XML-less Spring setup, this simple project is an example, to checkout out.  It is based on official https://spring.io/guides/gs/spring-boot but extended and configured to include a set of tool, that you are likely to use (Groovy, Spock, Spring Data, etc.).

# How to run it?

If you have gradle installed and under linux/mac:

    gradle runJar

If gradle is not installed, but still under linux/mac

    gradlew runJar

And for windows without gradle

    gradlew.bat runJar

After the server is running, go to
