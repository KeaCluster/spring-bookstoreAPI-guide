# Part 0 - Introduction

<!--toc:start-->

- [Part 0 - Introduction](#part-0-introduction)
  - [API](#api)
    - [Definition](#definition)
  - [REST](#rest)
    - [RESTful](#restful)
  - [Design Patterns](#design-patterns)
    - [MVC](#mvc)
  - [Persistence](#persistence)
    - [Persistence API](#persistence-api)
    - [Why JPA](#why-jpa)

<!--toc:end-->

We'll look at some basic theory and concepts there. Remember that this isn't a professional guide, so don't take it as the absolute truth. Always look and search for more information and question the basics.

## API

### Definition

An API (Application Programming Interface) is a set of rules and procedures that enable different applications to communicate and interact with each other.
The basic example is the connection between a web-application that the final user interacts with, and a database with stored data.

## REST

REST (Representational State Transfer) is and architectural style for designing networked aplications. It uses HTTP requests to perform CRUD operations.

### RESTful

A `RESTful API` adheres to _REST_ principles, enabling scalable, flexible, and indepndent interfacing between two systems for secure and efficient data exchange.

## Design Patterns

Design Patterns are general _reusable_ solutions to common problems encountered in software design. They aren't considered blueprints or templates, but rather guidelines for how to structure code to solve certain problems. They apply and encapsulate best practices to promote maintainability, scalability, and robustness in complex software projects.

### MVC

MVC _(Model-View-Controller)_ is a design pattern that segregates an application into three interconnected components to separate internal representations of information from the way it's presented and accepted by the end user.

This separation into `Model`, `View` and `Controller` components facilitates organized coding, easier maintenance, and effective data management and representation.

## Persistence

The term _Persistence_ refers to the capability of a system to store data in a permanent state that can be retrieved and used even after the system has been rebooted.
This is helpful when unintended and/or intended off-on situations happen.

### Persistence API

The Java Persistence API _(JPA)_ provides a framework for mapping Java `Objects` directly to database tables and vice versa. Allowing for data persistence management.

### Why JPA

This dependency greatly simplifies data access within Java applications providing an _Object-Relational-Mapping_ (ORM) framework. Abstracting and handling database operations, making code **database-agnostic** and easier to maintain.
