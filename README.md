Frege using Gradle
==================

The __Frege__ programming language is a __Haskell__ implementation on the __Java__/__JVM__ world.

This project aims at exploring the Frege integration with Java using __Gradle__ automation tool.

Command line
------------

To generate the source code, then include it to the __fat Jar__ along with the Frege jar file run the following command:
```
gradle clean generateJavaSrcFromFregeSrc fatJar
```
You will then get an executable Jar inside the `build/libs` folder.
To run the previously generated executable Jar type the following command:
```
java -jar build/libs/FregeGradleInvestigation-fatJar-1.0.jar
```

Acknowledgment
--------------
Thanks to Dierk for the [Hello Frege project](https://github.com/Dierk/HelloFrege.git).

