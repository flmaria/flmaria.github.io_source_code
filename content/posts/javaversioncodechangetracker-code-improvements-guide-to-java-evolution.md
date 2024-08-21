+++
title = 'JavaVersionCodeChangeTracker: Code improvements Guide to Java evolution'
+++

## Introduction

[JavaVersionCodeChangeTracker](https://github.com/flmaria/JavaVersionCodeChangeTracker) project is designed to showcase the most significant code changes, improvements, and new features introduced in each Java release. For developers aiming to enhance their programming skills and stay up-to-date with the latest Java advancements, this project provides a hands-on approach to learning by implementing these enhancements directly.

## Project Structure

The structure of [JavaVersionCodeChangeTracker](https://github.com/flmaria/JavaVersionCodeChangeTracker) is meticulously organized under the `io.github.flmaria` package. Each version of Java has its dedicated sub-package, which is structured as follows:

- **Dedicated Sub-Packages for Each Version**: Every major Java release has its own sub-package within the project. These sub-packages are named to reflect the version they represent.
  
- **Runnable Main Classes**: Each sub-package contains a `Main.java` class that is fully runnable. This class demonstrates the usage of the new features and improvements introduced in that specific Java version.
  
- **Simple and Illustrative Examples**: The examples provided are designed to be straightforward and easy to understand, allowing developers to run them and observe the output directly.

## Current Java Versions with Examples

The project currently includes examples from various Java versions, starting from Java 4 up to the latest Java 22. Here's a glimpse of what you can expect:

- **Java 4 (1.4)**
  - Assertions: `io.github.flmaria.java_004.assertions`
  - Regular Expressions: io.github.flmaria.java_004.regularexpressions`
- **Java 5**
  - Generics: `io.github.flmaria.java_005.generics`
  - Concurrency Utilities: `io.github.flmaria.java_005.concurrencyutilities`
  - Scanner: `io.github.flmaria.java_005.scanner`
- **Java 7**
  - Fork/Join Framework: `io.github.flmaria.java_007.forjjoinframework`
  - NIO.2 (New I/O 2): `io.github.flmaria.java_007.nio2`
- **Java 8**
  - Lambda Expressions: `io.github.flmaria.java_008.lambdaexpressions`
  - Functional Interfaces: `io.github.flmaria.java_008.functionalinterfaces`
  - Stream API: `io.github.flmaria.java_008.streamapi`
  - Default Methods: `io.github.flmaria.java_008.defaultmethods`
  - Optional Class: `io.github.flmaria.java_008.optionalclass`
  - New Date and Time API (java.time package): `io.github.flmaria.java_008.newdateandtimeapi`
  - Parallel Array SortingL `io.github.flmaria.java_008.parallelarraysorting`
  - CompletableFuture and the Concurrency API Enhancements: `io.github.flmaria.java_008.completablefutureandtheconcurrencyapienhancements`
  - Collectors Class: `io.github.flmaria.java_008.collectorsclass`
  - Method References: `io.github.flmaria.java_008.methodreferences`
- **Java 9**
  - Factory Methods for Immutable List, Set, Map and Map.Entry: `io.github.flmaria.java_009.factorymethodforImmutablelistsetandmap`
  - Private methods in Interfaces: `io.github.flmaria.java_009.interfaceprivatemethod`
  - Process API Improvements: `io.github.flmaria.java_009.processhandle`
  - Try with resources Improvements: `io.github.flmaria.java_009.trywithresources`
  - CompletableFuture API Improvements: `io.github.flmaria.java_009.completablefutureapiimprovements`
  - Reactive Streams: `io.github.flmaria.java_009.reactivestreams` 
  - Optional Class Improvements: `io.github.flmaria.java_009.optionalclassimprovements`
  - Stream API Improvements: `io.github.flmaria.java_009.streamapiimprovements`
- **Java 10**
  - Local-Variable Type Inference: `io.github.flmaria.java_010.localvariabletype`
- **Java 11**
  - String Methods: `io.github.flmaria.java_011.stringmethods`
  - Local-Variable Syntax For Lambda Parameters: `io.github.flmaria.java_011.varkeywordinlambdaexpression`
  - Reading/Writing Strings from Files class: `io.github.flmaria.java_011.readwritestringfromfiles`
- **Java 12**
  - Reimplement the Legacy Socket API: `io.github.flmaria.java_012.reimplementthelegacysocketapi`
  - Switch Expressions `io.github.flmaria.java_012.switchexpressions`
- **Java 13**
  - Text Blocks `io.github.flmaria.java_013.textblocks`
  - FileSystems.newFileSystem() Method: `io.github.flmaria.java_013.filesystemsnewfilesystemmethod`
- **Java 14**
  - Pattern Matching for instanceof: `io.github.flmaria.java_014.patternmatchingforinstanceof`
  - Records: `io.github.flmaria.java_014.records`
- **Java 15**
  - Sealed Classes: `io.github.flmaria.java_015.sealedclasses`
- **Java 16**
  - Vector API: `io.github.flmaria.java_016.vectorapi`
- **Java 17**
  - Pattern Matching for switch: `io.github.flmaria.java_017.patternmatchingforswitch`
  - Context-Specific Deserialization Filters: `io.github.flmaria.java_017.contextspecificdeserializationfilters`
  - Enhanced Pseudo-Random Number Generators: `io.github.flmaria.java_017.enhancedpseudorandomnumbergenerators`
- **Java 18**
  - Simple Web Server: `io.github.flmaria.java_018.simplewebserver`
- **Java 19**
  - Virtual Threads: `io.github.flmaria.java_019.virtualthreads`
- **Java 21**
  - Sequenced Collections: `io.github.flmaria.java_021.sequencedcollections`
- **Java 22**
  - Unmodifiable Collection Factory Methods: `io.github.flmaria.java_022.unmodifiablecollectionfactorymethods`
  - New APIs for Daylight Saving Time and Leap Seconds: `io.github.flmaria.java_022.newapisfordaylightsavingtimeandleapseconds`

Each version’s sub-package provides runnable examples in `Main.java` to illustrate these features.

## Requirements

To run this project, you need the following:

- **Java 22**: The project utilizes the latest language features and improvements introduced in Java 22.
- **Maven**: Dependency management is handled via Maven, particularly for managing the SLF4J logger dependency.

## How to Use

Follow these steps to get started:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/flmaria/JavaVersionCodeChangeTracker.git
2. **Navigate to the Project Directory:**:
   ```bash
   cd JavaVersionCodeChangeTracker
3. **Build the Project::**:
   ```bash
   mvn clean install
4. **Run the Examples:**
- Explore the `io.github.flmaria` package to find sub-packages for each Java version.
- Each sub-package contains a `Main.java` class. You can run this class directly in your preferred IDE or through the command line to see the examples in action.

## Observation
[JavaVersionCodeChangeTracker](https://github.com/flmaria/JavaVersionCodeChangeTracker) is solely focused on code-level changes and improvements in the Java language. It does not cover enhancements in other areas such as the JVM, tools, libraries, or the broader Java ecosystem. The examples and documentation are specifically tailored to illustrate changes in Java syntax, APIs, and other code-level features across different versions.

Stay ahead of the curve by exploring the features that have shaped Java over the years with [JavaVersionCodeChangeTracker](https://github.com/flmaria/JavaVersionCodeChangeTracker). Happy coding!

