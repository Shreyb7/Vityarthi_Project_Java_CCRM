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
      










