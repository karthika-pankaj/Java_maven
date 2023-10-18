Project: Create and Build a Sample Java Project using Maven
Problem Statement:

This project aims to create and build a simple Java project using Maven. You'll need a code editor (preferably Microsoft Visual Studio Code), JDK8 (or later), and Maven installed. The project will focus on a basic task, like computing the length of an entered word.
Objectives:

    Provide hands-on experience in building projects using Maven.
    Successfully execute the project, ensuring input leads to the expected output.
    Gain practical knowledge on executing any Java project using Maven.

Tasks/Activities List:
Task 1: Maven Installation

    Install Maven:
        Download and install Maven from the official website: https://maven.apache.org/download.cgi.

Task 2: Java Project Creation

    Create a Project Directory:
        Open your favorite code editor and create a directory for your Java project.

    Set Up Directory Structure:
        Inside the project directory, create the following directories:
            src/main/java/hello
            Inside the hello directory, create a Java file (e.g., Hello.java) for your code.

    Write Java Code:
        In the Hello.java file, write code that computes the length of an entered word and outputs the result.

Task 3: pom.xml Creation

    Create pom.xml File:
        Inside the project directory, create a file named pom.xml. This file will contain project configuration details for Maven.

    Edit pom.xml:
        Open pom.xml in your code editor and add the necessary Maven configurations, including project details, dependencies (if any), and build settings.

    ask 4: Building Java Project using Maven

    Open Terminal/Command Prompt:
        Navigate to your project directory using the terminal or command prompt.

    Run Maven Build:

        Execute the following command to build your Java project using Maven:
mvn clean package
Task 5: Test Your Build

    Run Java Program:

        Use the following command to run your Java program:
java -cp target/<artifactId>-<version>.jar hello.Hello

Success Metrics:

    Maven installed correctly.
    Java project executes well independent of Maven.
    Java project built well with Maven.
    Built Java project executed well.
