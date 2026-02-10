Day 4 – Overview of Java Platform and first Java class

Topics covered:
- Overview of the Java platform
- Introduction to java, javac, and bytecode
- Java Class and Object (first look)
- Creating methods inside a Java class
- Compiling and running a Java program
- JDK vs JRE vs JVM

Key concepts:
- Java source code is written in .java files
- javac compiles .java files into bytecode (.class)
- Bytecode is executed by the JVM
- A Java program starts execution from the main method
- A class is a blueprint, objects are instances of a class

Java tools:
- java → runs Java programs
- javac → compiles Java source code

Main method:
- Entry point of a Java application
- Signature:
  public static void main(String[] args)

JDK vs JRE vs JVM:
- JVM: executes Java bytecode
- JRE: JVM + libraries needed to run Java programs
- JDK: JRE + tools to develop Java programs (javac, etc.)

Hands-on practice:
- Created a Planet.java class
- Added methods to a class
- Compiled Planet.java using javac
- Ran the program using the java command
- Experimented by modifying the class and methods

Notes:
- Java is platform-independent because of bytecode + JVM
- Compilation and execution are two separate steps

Questions / To review:
- Difference between class and object in more detail
- Why main method must be static