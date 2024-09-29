## Accessing Data in Pivotal GemFire with REST

This guide walks us through the process of creating an application 
that accesses data stored in Apache Geode through a hypermedia-based REST-ful frontend.

### What we’ll build

We’ll build a Spring Web application that let us create and retrieve Person 
objects stored in the Apache Geode In-Memory Data Grid (IMDG) using Spring 
Data REST. Spring Data REST takes the features of Spring HATEOAS and Spring 
Data for Apache Geode and combines them together automatically.