# A collection of Maven archetypes

This repository contains a collection of Maven archetype projects:

* java8: A simple and minimal Java  8 + JUnit 5.x project
* java8: A simple and minimal Java 11 + JUnit 5.x project
* mule3: A minimal MuleSoft Anypoint Platform 3.x project
* mule4: A minimal MuleSoft Anypoint Platform 4.x project

The above archetypes will be (are) deployed to the main SonaType Maven repository so you should be able to use them by simply typing `mvn archetype:generate` and filtering on the `tech.raaf` group id.

You can also clone this repository and `mvn clean install` within one of the above listed project directories which you'll find in this repository. After you do that, you can run `mvn archetype:generate` and the last item on the list will be your locally installed archetype.
