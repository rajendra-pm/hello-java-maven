# Hello Java Maven – Jenkins Build

## 📌 Task Objective
This project demonstrates how to build a simple **Java Maven application** using **Jenkins**.  
It is part of **TASK 8: Run a Simple Java Maven Build Job in Jenkins**.

---

## 📂 Project Structure
hello-java-maven/
 ├── pom.xml
 └── src/
     └── main/
         └── java/
             └── HelloWorld.java
             
##⚙️ Steps Performed

1.Created a GitHub repository hello-java-maven.

2.Added HelloWorld.java and pom.xml.

3.Started Jenkins (docker run -p 8080:8080 jenkins/jenkins:lts).

4.Configured Maven under Manage Jenkins → Tools.

5.Created a Freestyle Job:

6.Source Code Management → Git repo URL.

Build → Invoke top-level Maven targets → Goals: clean package.

Ran the job and verified output.


## Jenkins Build Result


## 🎯 Outcome / Learnings

1. Understood what a Jenkins job is.

2. Learned how to trigger builds manually.

3. Saw how Jenkins integrates with Maven to compile and package Java code.

4. Learned to read Jenkins console output.
The job executed successfully, and Maven created a JAR file:

[INFO] Building jar: /var/jenkins_home/workspace/hello-java-maven-job/target/hello-1.0.jar
[INFO] ------------------------------------------------------------------------
[INFO] BUILD SUCCESS
[INFO] ------------------------------------------------------------------------
