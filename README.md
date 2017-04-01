# CloudenabledWebApp
CloudenabledWebApp for maven web app

## By: Sushil

# Pre-reques:
---------------
-- Install Java
-- Install maven
  -- $sudo apt-get update
  -- $sudo apt-get install maven
  -- $mvn -version
--Install tomcat7 webserver
  -- $apt-get install tomcat7


To create a simple java project using maven, you need to open command prompt and run the archetype:generate command of mvn tool:
----------------------------------------------------------------------------------------------------------------------------------
 mvn archetype:generate -DgroupId=com.javatpoint -DartifactId=CloudenabledWebApp -DarchetypeArtifactId=maven-archetype-webapp -DinteractiveMode=false
 
 It will generate following code in the command prompt::
 ----------------------------------------------------------
 1) Automatically Generated pom.xml file
 2) Automatically Generated index.jsp file
 3) Automatically Generated web.xml file
 
  How to Build the maven project or how to package maven project ?:
 ===============================================================
 mvn package  
 
 Deploy and Run the Maven Web Project
 =======================================
 Deploy the project on the server and access it by the following url:
 http://<host-name>:<portnumber>/projectname, for example: http://localhost:8080/CloudenabledWebApp
 By copying the generated war file onto /var/lib/tomcat7/webapp and restart the tomcat7 service
 
