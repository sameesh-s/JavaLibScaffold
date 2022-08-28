To create a utility lib using Gradle 
-------------------------------------   

1) clone the repo
2) give the Jar name inside settings.gradle => rootProject.name
3) give the version name inside the build.gradle file
4) to build the jar: using embedded gradle wrapper => ./gradlew build , to use the local gradle => gradle build, locally build jar will be inside build/lib folder in the same hierarchy
5) To publish the jar locally : using embedded gradle wrapper => ./gradle build publishToMavenLocal , to use local gradle => gradle build publishToMavenLocal
6) To change the publishing to nexeus or remote repository change the values in build.gradle
7) To locate locally build jar check m2 folder location (in linux where jar resides after publishing : /home/.m2)

Usefull shortcuts in intellij 
-----------------------------
ctrl + shift + T : create and navigate between test in intellij
 

