# Mule 4.x Example Project

1. Get adoptopenjdk-8: https://adoptopenjdk.net/
2. Get maven 3.6.x: https://maven.apache.org/
3. Add above to your path if neccessary.
4. `git clone git@github.com:rubin55/mule-four.git`
5. `mvn eclipse:eclipse`
6. `mvn clean package`

Step 5 in the list above sets up the .project and .classpath settings. After that you can open the project in Anypoint Studio 7.x.`mvn clean package` results in a deployable artifact which can be run in a Mule 4.x CE or EE runtime.
