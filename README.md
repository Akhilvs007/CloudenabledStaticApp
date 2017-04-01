# CloudenabledStaticApp
CloudenabledStaticApp maven java-junit project

## By: Sushil

# Pre-reques:
---------------
-- Install Java
-- Install maven
  -- $sudo apt-get update
  -- $sudo apt-get install maven
  -- $mvn -version


To create a simple java project using maven, you need to open command prompt and run the archetype:generate command of mvn tool:
----------------------------------------------------------------------------------------------------------------------------------
 mvn archetype:generate -DgroupId=com.javatpoint -DartifactId=CubeGenerator -DarchetypeArtifactId=maven-archetype-quickstart -DinteractiveMode=false
 
 It will generate following code in the command prompt::
 ----------------------------------------------------------
 1) Automatically Generated pom.xml file
 2) Automatically Generated App.java file
 3) Automatically Generated AppTest.java file
 
 Compile the Maven Java Project
 --------------------------------
 mvn clean compile  
 
 Run the Maven Java Project
 ----------------------------
 java com.javatpoint.App  
 
 How to Build the maven project or how to package maven project ?:
 ===============================================================
 mvn package  
 
 Run the maven project by the jar file
 ----------------------------------------
 java -classpath target/CloudenabledStaticApp-1.0-SNAPSHOT.jar:.: com.javatpoint.App
