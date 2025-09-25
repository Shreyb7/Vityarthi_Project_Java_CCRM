#  📘 Campus Course & Records Manager (CCRM)

##  🔹 Project Overview

The Campus Course & Records Manager (CCRM) is a Java SE console application that allows an institute to manage academic records through a structured, menu-driven interface.

Built with OpenJDK 21, the project covers a full academic workflow:

Creating and maintaining student profiles.

Managing courses across departments and semesters.

Enrolling students into courses with validation rules.

Recording grades, generating transcripts, and computing GPA.

Importing/exporting data files and creating timestamped backups.

This project was developed to demonstrate the breadth of the Java SE platform, showcasing both fundamentals and advanced features in a single, integrated system.

## ⚙️ Code Implementation Mapping :

| Syllabus/Project Feature | Code Implementation (File & Key Methods) |
| :--- | :--- |
| **Main Application Entry & Menu** | `cli/Main.java` and `main()` |
| **Application Configuration** (Singleton) | `config/AppConfig.java` and `getInstance()` |
| **Student Management (CRUD)** | `service/StudentService.java` and methods like `addStudent()`, `updateStudent()`, `deleteStudent()` |
| **Course Management (CRUD)** | `service/CourseService.java` and methods like `addCourse()`, `manageCourses()` |
| **Enrollment & Grading Logic** | `service/EnrollmentService.java` and methods like `manageEnrollments()`, `gradeStudent()` |
| **File Operations (I/O)** | `io/FileService.java` and methods like `importData()`, `exportData()` |
| **Object-Oriented Data Models** | `domain/Student.java`, `domain/Course.java`, `domain/Enrollment.java` |
| **Custom Error Handling** | `exceptions/StudentNotFoundException.java`, `exceptions/CourseNotFoundException.java` |


###  Steps to Run the  Java project :

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

##  📖 Evolution of Java :

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


##  🔍 Java Editions :

🔹Java ME (Micro Edition): A lightweight version of Java designed for resource-constrained devices like mobile phones, PDAs, and embedded systems.

🔹Java SE (Standard Edition): The core Java platform that provides fundamental libraries and APIs for developing desktop, CLI, and small-scale applications.

🔹Java EE (Enterprise Edition) / Jakarta EE: An extension of Java SE with additional APIs for building large-scale, distributed, web, and enterprise applications.


##  ⚙️ Java Architecture :

🔹JDK (Java Development Kit): A full development toolkit containing compiler (javac), debugger, libraries, and tools required to develop, compile, and run Java programs.

🔹JRE (Java Runtime Environment): A runtime package that provides the libraries, Java ClassLoader, and JVM needed to run Java applications but not to develop them.

🔹JVM (Java Virtual Machine): The abstract machine that converts compiled bytecode into machine-specific instructions and ensures Java’s platform independence.

STEPS TO INSTALL AND RUN JDK21 IN WINDOWS :

####   ⬇️1. Search and download suitable JDK file from Oracle site :
<img width="2560" height="1600" alt="installation step1" src="https://github.com/user-attachments/assets/2cf8709a-4fa0-4713-9c5f-7f55fab7d5a6" />
   
####   🛠️2. After downloading install the the kit :
  <img width="2560" height="1600" alt="installation step 2" src="https://github.com/user-attachments/assets/5357b971-0a66-4318-a878-9f99046d050c" />

 ####  ⚙️3. Check destination folder :
 <img width="2560" height="1600" alt="installation step 3" src="https://github.com/user-attachments/assets/e4787da1-2872-4ad1-a22f-d3a70a57af66" />

 ####  ⚙️4. Close installation Wizard :
<img width="2560" height="1600" alt="installation step 4" src="https://github.com/user-attachments/assets/72adb4fa-76e6-493f-ba84-8bb3630d7047" />

 ####  ⚙️5. Copy the path upto bin where you have saved the file :
<img width="2560" height="1600" alt="installation step 5" src="https://github.com/user-attachments/assets/9925d558-c911-4792-83a0-34d47eadc5a3" />

 ####  ⚙️6. Go to environment variables :
 <img width="2560" height="1600" alt="installation step  6" src="https://github.com/user-attachments/assets/92645d82-809c-4079-a953-8e76893edddd" />

 ####  ⚙️7. Create new variable and paste the copied path :
<img width="2560" height="1600" alt="installation step  7" src="https://github.com/user-attachments/assets/cbe9c317-919d-4586-ac7c-20685f1a8af6" />

 ####  ⚙️8. Save the environment variable :
 <img width="2560" height="1600" alt="installation step  8" src="https://github.com/user-attachments/assets/4528213e-9b3e-4ff1-a008-78740f3952fe" />

 ####  ⚙️9. edit the path in system variables :
 <img width="2560" height="1600" alt="installation step  9" src="https://github.com/user-attachments/assets/f2c150b6-36f7-4564-b106-6964b1d22bb3" />

 ####  ⚙️10. Save the  path variable :
 <img width="2560" height="1600" alt="installation step  10" src="https://github.com/user-attachments/assets/d41d4fc9-20e5-4ded-a1df-32703d2de61b" />

 ####  ✅11. Verify the  version installation :
 <img width="2560" height="1600" alt="installation step  11" src="https://github.com/user-attachments/assets/6902828f-940f-4f1e-ac1c-6794394a6ba6" />
            

   ######     These are all the steps for windows installation.
     

###  STEPS TO INSTALL AND SETUP Eclipse IDE :

 ####   1. Search and download the Eclipse IDE for Java developers :
<img width="2560" height="1600" alt="Eclipse installation and  setup 1" src="https://github.com/user-attachments/assets/23d91979-d463-4f59-9deb-afb7330f113c" />
       
  ####  2. Download zip file :
<img width="2560" height="1600" alt="Eclipse installation and  setup 2" src="https://github.com/user-attachments/assets/316018b7-c124-4c4f-9258-a0f7ae580c91" />

####  3. Check path of file , extract and run Eclipse.exe file :
<img width="2560" height="1600" alt="Eclipse installation and  setup 3" src="https://github.com/user-attachments/assets/03d99af8-4044-4be0-ad81-21afde2add25" />

<img width="2560" height="1600" alt="Eclipse installation and  setup 4" src="https://github.com/user-attachments/assets/15b4cffd-fb16-41e4-b80f-5d67439dafa2" />

 <img width="2560" height="1600" alt="Eclipse installation and  setup 5" src="https://github.com/user-attachments/assets/e4f91fb8-bb56-4ac3-9b14-b2719a15d9d9" />

 ####  4. Launch the IDE and carry out required instructions :
 <img width="2560" height="1600" alt="Eclipse installation and  setup 6" src="https://github.com/user-attachments/assets/b59c6a13-135a-4e0d-81e3-aa6cb5f9bb8c" />

 <img width="2560" height="1600" alt="Eclipse installation and  setup 7" src="https://github.com/user-attachments/assets/f72a989d-c458-48a1-aacf-e9f09f7fb554" />

 <img width="2560" height="1600" alt="Eclipse installation and  setup 8" src="https://github.com/user-attachments/assets/6982774e-d20d-4a93-be4f-4e91fb287e61" />

<img width="2560" height="1600" alt="Eclipse installation and  setup 10" src="https://github.com/user-attachments/assets/d694e79b-cd68-4790-aa1c-d8845d6b6a74" />


####  5. you can see the Eclipse IDE running :
<img width="2560" height="1600" alt="Eclipse installation and  setup 11" src="https://github.com/user-attachments/assets/c050abaa-7261-476c-92d8-a1b710de0ce1" />
      


 ###### These are all the steps for the  Installations and Setup for the Eclipse IDE you can see the program output  in the screenshot Section.


    

###  FOLLOWING ARE THE SCREENSHOTS OF  PROJECT CREATION FROM LOCAL DIRECTORY :

#### STEP 1 : First write your code in the Notepad or any text editor and to all the packages should be mentioned and should be written
<img width="2560" height="1600" alt="Screenshot (249)" src="https://github.com/user-attachments/assets/ea14fcf6-becd-48e6-b9cd-70bec21c810f" />

####  STEP 2 :  Then convert File into zip and extract all files in a required directory you can see the extracted file here as SHREYAS_JAVA.zip and its extracted file :
<img width="2560" height="1600" alt="Screenshot (250)" src="https://github.com/user-attachments/assets/a4bc4b68-0130-4924-854d-1c0082191731" />

####  STEP 3 :  Go to Eclipse IDE and import the file from  local directory or file system  after moving loacations of file (I MOVED TO DOWNLOADS):
<img width="2560" height="1600" alt="Screenshot (251)" src="https://github.com/user-attachments/assets/c34fda5b-7a9a-4c82-8f05-79fd4ab90a81" />

####  STEP 4 : Now you can see your project and its file mapping structure
<img width="2560" height="1600" alt="Screenshot (252)" src="https://github.com/user-attachments/assets/bb7d43b0-638c-44bf-a4b8-242968646171" />


####  STEP 5 : Now run the program as Java application :
 <img width="2560" height="1600" alt="Screenshot (253)" src="https://github.com/user-attachments/assets/7593ce34-58b0-4ef7-963d-60c9b9cabfdf" />

           
 ###### These are all steps for project creation in Eclipse.

    
    
 ### FOLLOWING ARE THE SCREENHOTS OF PROGRAM OPERATIONS OUTPUT :

####  Output for the initail UI interface and operations in Program :
<img width="2560" height="1600" alt="Screenshot (255)" src="https://github.com/user-attachments/assets/5562ccba-a390-494f-ba85-d8a1819e44cb" />

####  Output for Student management - add, list , update and deactivate :
<img width="2560" height="1600" alt="Screenshot (258)" src="https://github.com/user-attachments/assets/6db26cf0-4c85-49a9-8057-e0a429a996dc" />

####  Output for the Course management :
<img width="2560" height="1600" alt="Screenshot (259)" src="https://github.com/user-attachments/assets/8042db91-1495-4576-bff9-9356ac4bc5ef" />

####  Output for the enrolled Students :
 <img width="2560" height="1600" alt="Screenshot (260)" src="https://github.com/user-attachments/assets/9bb61546-1f03-43c6-a6dc-0ff60bcf6011" />

####  Output for the Student Grading management :
 <img width="2560" height="1600" alt="Screenshot (261)" src="https://github.com/user-attachments/assets/e17a4f83-6f04-4f9a-86e1-a79819a2bed1" />

 ####  Output for the Transcript of the student with Assigned Grade :
 <img width="2560" height="1600" alt="Screenshot (262)" src="https://github.com/user-attachments/assets/eea6665e-21dd-4021-ad72-94df38c1f521" />

 ####  Output for the File Operations and Utilities :
 <img width="2560" height="1600" alt="Screenshot (263)" src="https://github.com/user-attachments/assets/2eb14ecc-dd21-43ec-a5c2-808815b74e08" />


  ###### These are the Outputs of the Program.








  

    

       


     



   
     





     


















