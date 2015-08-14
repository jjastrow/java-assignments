## General

* Use industry-standard tools
  * JDK 8
  * IntelliJ + [JREPL](https://plugins.jetbrains.com/plugin/7892)
* Focus on data structures
  * Emphasize the distinction between code and data
  * Think about the data first, and the code will follow
  * Design projects specifically around use of various data structures
* Start with a Java REPL instead of overwhelming students with a full project structure
  * Starting off with a typical "Hello world" project is problematic, as it assumes the following:
    * Knowing what a class is
    * Knowing what `public static void` is
    * Knowing what `String[] args` is
  * With a REPL, we can introduce these concepts one at a time and jump into a real project later

## Week 1 - Data first, code second

* Data
  * Create scalar and compound variables in a REPL
  * Scalar (int, char, String)
  * Compound (Array, Class, ArrayList, HashMap)
    * Sequential vs key-value data
      * Array (sequential)
      * Class (key-value)
    * Static vs dynamic data
      * ArrayList (dynamic sequential)
      * HashMap (dynamic key-value)
* Code
  * Class is not just a data structure; it can contain code (methods)
  * Create a blank project in the IDE
  * Create methods that initialize data the same way we did in the REPL
  * Static vs non-static, public vs private
  * Console I/O
  * Flow control

## Week 2 - Writing real programs

* The main method
* Packages
* Imports
* Inheritance
  * @Overload
  * Casting
  * Interfaces and abstract classes
* Standard library
  * java.math
  * java.io
  * java.time
  * java.swing

## Week 3 - Catching errors

* Debugging
* Testing (JUnit)

## Week 4 - Creating web apps with third-party libraries

* Maven
* [Jodd](http://jodd.org/)
* [Spark](http://sparkjava.com/)

## Week 5 - Databases

* Database I/O
* [H2](http://www.h2database.com/html/main.html)

## Week 6-7 - Spring + Hibernate

* [Spring Boot](http://projects.spring.io/spring-boot/)

## Week 8-9 - Clojure

* See the [Clojure curriculum](https://github.com/oakes/clojure-assignments)
