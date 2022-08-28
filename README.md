
m2 folder location in linux(where jar resides after publishing) : /home/.m2

build command : gradle build 
publishing command :  gradle build -x test publishToMavenLocal 

jar name will be decided based on the value in settings.gradle => rootProject.name   
 
