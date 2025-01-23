# AbcFitnessProject

This document provides step-by-step instructions for setting up, building, and running the abcFitnessProject using Eclipse IDE, Spring MVC, Maven, JDK 8, and Tomcat 9. 

Follow these instructions to ensure a successful setup.

Prerequisites:
--------------
1.Java Development Kit (JDK)
2.Apache Maven
3.Apache Tomcat 9.0
4.Eclipse IDE
5.Spring Framework Libraries

Project Setup:
--------------

Please note that you may need to download additional JAR files for the Spring Framework. For Java class references, check the included build.zip, which contains the controller folder (with main controller classes) and the pojo folder (with backend POJO files). These are the primary files for backend functionality.

To work with the project, first import these into Eclipse. Once imported, ensure all dependencies are properly configured, including the pom.xml for Maven and web.xml for web configuration. If needed, run the command mvn clean install to download the required Maven dependencies. Ensure that the web.xml file is properly configured (this should happen automatically upon import) and resolve any issues in the Java Build Path. Finally, add Tomcat to the Eclipse Servers view and run the project as Run on Server.
 
I have developed the backend functionality. for the project, but the frontend screens have not been created yet. Please let me know if you would like me to work on the frontend development as well.
