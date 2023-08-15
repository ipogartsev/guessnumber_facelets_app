# guess a number game - simple Java Facelets application

Jakarta EE9
GlassFish 6.0
Maven 3.8.7 

Clone app, enter the app folder and run maven: "mvn clean install" (for Windows using command line). 
Copy .war file from "target" application folder and put it into the "autodeploy" folder on glassfish6/glassfish/domain/domain1/autodeploy.
Run GlassFish server from glassfish6/bin folder: "asadmin start-domain" - the application will be autodeployed.
Open in browser "http://localhost:8080/guessnumber-0.0.1-SNAPSHOT" - and try to guess a number!
** You can find the generated random number in "log" folder of glassfish
