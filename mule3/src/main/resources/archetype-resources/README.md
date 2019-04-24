# ${projectDescription}

1. Get adoptopenjdk-8: https://adoptopenjdk.net/
2. Get maven 3.6.x: https://maven.apache.org/
3. Add above to your path if neccessary.
4. `git clone ${scmUrl}`
5. `mvn clean package`
6. `mvn eclipse:eclipse`

Step 6 in the list above sets up the .project and .classpath settings. After that you can open the project in Anypoint Studio 6.x.`mvn clean package` results in a deployable artifact which can be run in a Mule 3.x CE or EE runtime.
