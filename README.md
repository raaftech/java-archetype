# A Maven archetype project for using Java 11 and JUnit 5.x

This is a Maven archetype project for using Java 8 and JUnit 5.x.

The above archetypes are deployed to the main SonaType Maven repository so you should be able to use them by simply typing `mvn archetype:generate` and filtering on the `tech.raaf` groupId (the syntax for filtering on groupId is `:tech.raaf`, notice the colon).

You can also clone this repository and `mvn clean install`. After you do that, you can `cd ../somewhere-else` and run `mvn archetype:generate` and the last item on the list will be your locally installed archetype which you can select by number.

The resulting Java project contains a minimal HelloWorld and accompanying test and uses the latest JUnit 5.x and latest versions of various Maven plugins. To package and run the resulting project, you'd typically:

 * `mvn clean package`
 * `java -jar target/${artifactId}-${version}.jar`
