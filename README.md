# Java IZ0-829 Exam Preparation

This repository contains practical Java applications designed to help prepare for the Oracle Certified Professional: Java SE 17 Developer (IZ0-829) exam. Each objective from the official exam guide is addressed with a dedicated modular Java application, showcasing the concepts in action.

## Table of Contents

* [Objective 1: Handling date, time, text, numeric and boolean values](#objective-1-handling-date-time-text-numeric-and-boolean-values)
* [Objective 2: Controlling Program Flow](#objective-2-controlling-program-flow)
* [Objective 3: Utilizing Java Object-Oriented Approach](#objective-3-utilizing-java-object-oriented-approach)
* [Objective 4: Handling Exceptions](#objective-4-handling-exceptions)
* [Objective 5: Working with Arrays and Collections](#objective-5-working-with-arrays-and-collections)
* [Objective 6: Working with Streams and Lambda expressions](#objective-6-working-with-streams-and-lambda-expressions)
* [Objective 7: Packaging and deploying Java code and use the Java Platform Module System](#objective-7-packaging-and-deploying-java-code-and-use-the-java-platform-module-system)
* [Objective 8: Managing concurrent code execution](#objective-8-managing-concurrent-code-execution)
* [Objective 9: Using Java I/O API](#objective-9-using-java-io-api)
* [Objective 10: Accessing databases using JDBC](#objective-10-accessing-databases-using-jdbc)
* [Objective 11: Implementing Localization](#objective-11-implementing-localization)
* [Objective 12: Other important topics](#objective-12-other-important-topics)

---

## Exam Objectives and Practice Applications

### Objective 1: Handling date, time, text, numeric and boolean values

* **Description:** This section focuses on fundamental Java data types and their manipulation. We'll explore primitive types, their corresponding wrapper classes, the `Math` API for mathematical operations, the `String` and `StringBuilder` classes for text manipulation (including text blocks), and the modern `java.time` (Date-Time) API for handling dates, times, durations, periods, instants, and time zones.
* **Practice Application:** `DataTypeShowcaseApp`
    * **Modules:**
        * `com.example.datatypes`: Demonstrates primitive types, wrapper classes, `String`, `StringBuilder`, and `Math` API.
        * `com.example.datetime`: Showcases the usage of the `java.time` package.
        * `com.example.mainapp`: The main application orchestrating the demonstrations from the other modules.

### Objective 2: Controlling Program Flow

* **Description:** This section covers essential control flow constructs in Java, including `if/else` statements, `switch` statements and expressions, various loop types (`for`, `while`, `do-while`), and the `break` and `continue` statements for altering loop execution.
* **Practice Application:** `ControlFlowExamplesApp`
    * **Modules:**
        * `com.example.controlflow`: Contains examples of `if/else`, `switch`, loops, `break`, and `continue`.
        * `com.example.mainapp`: The main application to run the control flow examples.

### Objective 3: Utilizing Java Object-Oriented Approach

* **Description:** This comprehensive objective delves into the core principles of Object-Oriented Programming (OOP) in Java. Topics include object creation and lifecycle, class and record definition, instance and static members, constructors, initializers, method overloading (including var-args), variable scopes, local variable type inference, encapsulation, immutability, inheritance (including abstract and sealed classes), method overriding, polymorphism, type casting, `instanceof` and pattern matching, interfaces (functional, private, static, default methods), and enumerations.
* **Practice Application:** `OOPConceptsApp`
    * **Modules:**
        * `com.example.oopbasics`: Covers basic class/object creation, fields, methods, constructors, scope, encapsulation, and immutability.
        * `com.example.inheritance`: Demonstrates inheritance, method overriding, polymorphism, and casting.
        * `com.example.interfacesenums`: Explores interfaces (including functional, private, static, default) and enums.
        * `com.example.mainapp`: Orchestrates the demonstrations.

### Objective 4: Handling Exceptions

* **Description:** This objective focuses on robust error handling in Java using exceptions. It covers `try/catch/finally` blocks, the `try-with-resources` statement for automatic resource management, multi-catch blocks, and the creation and use of custom exceptions.
* **Practice Application:** `ExceptionHandlingApp`
    * **Modules:**
        * `com.example.exceptions`: Contains examples of different exception handling mechanisms and custom exceptions.
        * `com.example.mainapp`: The main application to trigger and handle exceptions.

### Objective 5: Working with Arrays and Collections

* **Description:** This section explores fundamental data structures in Java. It covers the creation and manipulation of arrays, as well as common collection types from the Java Collections Framework: `List`, `Set`, `Map`, and `Deque`. Operations like adding, removing, updating, retrieving, and sorting elements will be demonstrated.
* **Practice Application:** `CollectionsShowcaseApp`
    * **Modules:**
        * `com.example.collections`: Provides examples of array and various collection (`List`, `Set`, `Map`, `Deque`) operations.
        * `com.example.mainapp`: The main application to run the collection examples.

### Objective 6: Working with Streams and Lambda expressions

* **Description:** This objective delves into the powerful Stream API and Lambda expressions introduced in Java 8. It covers using object and primitive streams, implementing functional interfaces with lambdas to filter, map, consume, and sort data. Advanced stream operations like decomposition, concatenation, reduction, grouping, and partitioning on both sequential and parallel streams will also be explored.
* **Practice Application:** `StreamLambdaApp`
    * **Modules:**
        * `com.example.streamslambdas`: Demonstrates various stream operations with lambda expressions.
        * `com.example.mainapp`: The main application to execute stream examples.

### Objective 7: Packaging and deploying Java code and use the Java Platform Module System

* **Description:** This crucial objective focuses on the Java Platform Module System (JPMS). It covers defining modules and their dependencies, exposing module content (including for reflection), defining services (producers and consumers), compiling modular code, creating modular and non-modular JARs, building runtime images (`jlink`), and migrating legacy code using unnamed and automatic modules.
* **Practice Application:** `ModularAppDeployment`
    * **Modules:** Multiple modules demonstrating inter-module communication, service loading, and various deployment scenarios.

### Objective 8: Managing concurrent code execution

* **Description:** This section covers concurrency in Java. It includes creating worker threads using `Runnable` and `Callable`, managing thread lifecycles, utilizing `Executor` services and the `java.util.concurrent` API, developing thread-safe code with different locking mechanisms, and processing Java collections concurrently (including parallel streams).
* **Practice Application:** `ConcurrencyExamplesApp`
    * **Modules:**
        * `com.example.concurrency`: Contains examples of thread creation, executors, locks, and concurrent collections.
        * `com.example.mainapp`: The main application to run concurrent code.

### Objective 9: Using Java I/O API

* **Description:** This objective focuses on input/output operations in Java. It covers reading and writing console and file data using I/O Streams, serializing and deserializing Java objects, and manipulating `Path` objects and their properties using the `java.nio.file` API (NIO.2).
* **Practice Application:** `IOOperationsApp`
    * **Modules:**
        * `com.example.io`: Demonstrates file I/O, object serialization, and NIO.2 `Path` operations.
        * `com.example.mainapp`: The main application to run I/O examples.

### Objective 10: Accessing databases using JDBC

* **Description:** This section covers database connectivity using the Java Database Connectivity (JDBC) API. Topics include establishing connections, creating and executing various statement types (basic, prepared, callable), processing query results (`ResultSet`), and controlling transactions.
* **Practice Application:** `JdbcIntegrationApp`
    * **Modules:**
        * `com.example.database`: Contains JDBC examples for connecting to a database and performing CRUD operations.
        * `com.example.mainapp`: The main application to run database interactions. (Note: This will require a local database setup, e.g., SQLite, H2).

### Objective 11: Implementing Localization

* **Description:** This objective focuses on internationalization and localization in Java. It covers using `Locale` objects, `ResourceBundle` for externalizing text, and parsing and formatting messages, dates, times, and numbers (including currency and percentage values) for different locales.
* **Practice Application:** `LocalizationApp`
    * **Modules:**
        * `com.example.localization`: Demonstrates `Locale`, `ResourceBundle`, and formatting.
        * `com.example.mainapp`: The main application to showcase localization.

### Objective 12: Other important topics

* **Description:** This section covers additional important topics that might appear on the exam or are generally considered good practice for a Java developer. This includes the basics of the Java Logging API, the use of standard annotations (`@Override`, `@FunctionalInterface`, `@Deprecated`, `@SuppressWarnings`, `@SafeVarargs`), and the application of generics, including wildcards.
* **Practice Application:** `AdvancedFeaturesApp`
    * **Modules:**
        * `com.example.miscfeatures`: Contains examples for logging, annotations, and generics.
        * `com.example.mainapp`: The main application to demonstrate these features.

---
