#First-jersey-service

Tested with the following configuration:

 * Eclipse Java EE IDE Version: Neon.1a Release (4.6.1)
 * Tomcat 8.5.8
 * Java JDK 1.8.0\_77

## Compiling

Do `mvn clean install` to create a first-jersey-service.war file in the target/ directory.

## Running

Either:
 1. Submit the generated war file to a server
 2. With a Tomcat server running,
   1. Right click the project name in the Package Explorer
   2. Run As -> Run on Server

## View results

 1. Navigate to <server url>:<port>/first-jersey-service/rest/hello
 2. Enjoy the greeting from the REST api ("Hello from Jersey")
