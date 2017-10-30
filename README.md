# seng560PgmAssign2
seng 560 fall 2017 basic calculator gui and functions

This is a class project for SENG 560 -Programming project assignment two(2). The requirements were to create an application reusing a classmates programming project from assignment one(1) code.  The original programming project #1, was a reusable library that implements basic arithmetic functions. It performs the following operations on integers and floating-point numbers as well as numbers provided in octal, binary, and hexadecimal. The operations to be supported are: 
•	Addition
•	Subtraction
•	Multiplication
•	Division
•	Square Root
•	Exponent
•	Conversion between the various types (octal, hexadecimal, integer, binary).

The source files are written in Java and were built in a Netbeans 8.2 JDK environment. To execute this library, you can download the source code and create a new project in your IDE and then perform a clean/build. OR if you do not have an IDE you can download the JAR file and run the on the command line. 

The SENG560_Basic_Calculator constructs a set of reusable libraries for basic arithmetic functions. The Abstraction package has the main interfaces which promote the reusability aspect of this project. The Implementation package consists of most of the ground work. The custom “white box” code for an updated GUI was in the implementation package. The original test program is being reused “black box” code with the updated GUI implementation. The GUI application will walk you through the basic calculator requests.

========================
BUILD OUTPUT DESCRIPTION
========================

When you build an Java application project that has a main class, the IDE
automatically copies all of the JAR
files on the projects classpath to your projects dist/lib folder. The IDE
also adds each of the JAR files to the Class-Path element in the application
JAR files manifest file (MANIFEST.MF).

To run the project from the command line, go to the dist folder and
type the following:

java -jar "SENG560Project2_Alonge.jar" 

To distribute this project, zip up the dist folder (including the lib folder)
and distribute the ZIP file.

Notes:

* If two JAR files on the project classpath have the same name, only the first
JAR file is copied to the lib folder.
* Only JAR files are copied to the lib folder.
If the classpath contains other types of files or folders, these files (folders)
are not copied.
* If a library on the projects classpath also has a Class-Path element
specified in the manifest,the content of the Class-Path element has to be on
the projects runtime path.
* To set a main class in a standard Java project, right-click the project node
in the Projects window and choose Properties. Then click Run and enter the
class name in the Main Class field. Alternatively, you can manually type the
class name in the manifest Main-Class element.
Building jar: JavaProject4\dist\SENG560Project2_Alonge.jar
To run this application from the command line without Ant, try:
java -jar “JavaProject4\dist\SENG560Project2_Alonge.jar"


