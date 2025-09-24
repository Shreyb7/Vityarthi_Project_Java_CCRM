📘Campus Course & Records Manager (CCRM)

🔹 Project Overview

The Campus Course & Records Manager (CCRM) is a Java SE console application that allows an institute to manage academic records through a structured, menu-driven interface.

Built with OpenJDK 21, the project covers a full academic workflow:

Creating and maintaining student profiles.

Managing courses across departments and semesters.

Enrolling students into courses with validation rules.

Recording grades, generating transcripts, and computing GPA.

Importing/exporting data files and creating timestamped backups.

This project was developed to demonstrate the breadth of the Java SE platform, showcasing both fundamentals and advanced features in a single, integrated system.

Steps to Run the  Java project :

     1. git clone https://github.com/Shreyb7/Vityarthi_Project_Java_CCRM.git
     cd Vityarthi_Project_Java_CCRM
     2. java -version
        javac -version
     3. javac -d out -sourcepath src src/edu/ccrm/cli/Main.java
     4. java -cp out edu.ccrm.cli.Main
     5. java -ea -cp out edu.ccrm.cli.Main (Optional)
     6.Import/Export test files
       Place sample CSV files inside a test-data/ folder (e.g., students.csv, courses.csv)
       Use the menu option in the CLI to import/export.

📖 Evolution of Java :

🔹1995 – Java 1.0 released by Sun Microsystems (WORA: Write Once, Run Anywhere)

🔹1998 – Java 2 (J2SE, J2EE, J2ME) introduced

🔹2004 – Java 5 (Generics, Annotations, Enhanced for-loop)

🔹2006 – Java became open-source (OpenJDK)

🔹2011 – Java 7 (NIO.2, try-with-resources, diamond operator)

🔹2014 – Java 8 (Streams, Lambdas, Date/Time API)

🔹2017 – Java 9 (Modules system, JShell REPL)

🔹2018 – Java 10+ (local variable var, new release cadence: every 6 months)

🔹2021 – Java 17 (LTS, sealed classes, pattern matching)

🔹2023 – Java 21 (latest LTS, virtual threads, pattern matching enhancements)


🔍 Java Editions :

🔹Java ME (Micro Edition): A lightweight version of Java designed for resource-constrained devices like mobile phones, PDAs, and embedded systems.

🔹Java SE (Standard Edition): The core Java platform that provides fundamental libraries and APIs for developing desktop, CLI, and small-scale applications.

🔹Java EE (Enterprise Edition) / Jakarta EE: An extension of Java SE with additional APIs for building large-scale, distributed, web, and enterprise applications.


⚙️ Java Architecture :

🔹JDK (Java Development Kit): A full development toolkit containing compiler (javac), debugger, libraries, and tools required to develop, compile, and run Java programs.

🔹JRE (Java Runtime Environment): A runtime package that provides the libraries, Java ClassLoader, and JVM needed to run Java applications but not to develop them.

🔹JVM (Java Virtual Machine): The abstract machine that converts compiled bytecode into machine-specific instructions and ensures Java’s platform independence.
