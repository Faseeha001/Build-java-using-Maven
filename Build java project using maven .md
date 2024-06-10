# Build-java-using-Maven
This repo  walks you through using Maven to build a simple Java project.

# PreRequisites 

Step1 : Install Maven on Linux machine ubuntu
![image](https://github.com/Faseeha001/Build-java-using-Maven/assets/169563689/9cc88579-1c54-4de3-ad18-b1843d681ac5)

Step2 : Create Directory 
create the following subdirectory structure with **mkdir -p src/main/java/hello**

└── src
    └── main
        └── java
            └── hello
![image](https://github.com/Faseeha001/Build-java-using-Maven/assets/169563689/30c1d891-5b1e-4e18-8e06-cc3b25b6381d)

Step 3 : Within the src/main/java/hello directory, you can create any Java classes you want.
To maintain consistency with the rest of this guide, create these two classes: HelloWorld.java and Greeter.java.
![image](https://github.com/Faseeha001/Build-java-using-Maven/assets/169563689/951222ac-4060-43ab-be4a-edd25cf3d3f5)

![image](https://github.com/Faseeha001/Build-java-using-Maven/assets/169563689/476077e1-cfa2-4dea-b281-1fe875d596d5)

![image](https://github.com/Faseeha001/Build-java-using-Maven/assets/169563689/ce35cedd-99ec-42d5-bdc9-6c5215e38c89)

Step 4 : Now that you have a project that is ready to be built with Maven, the next step is to install Maven.

Create pom.xml file in the directory next to src folder 
![image](https://github.com/Faseeha001/Build-java-using-Maven/assets/169563689/37e02dd5-4103-40e1-a785-06d465733fb2)

Step 5 : Run mvn package to build the project 
This command will compile your code and package it into a JAR file.
![image](https://github.com/Faseeha001/Build-java-using-Maven/assets/169563689/c8ae4a10-5319-4115-b542-5531d27b039e)

Step 6 : Once the build is successful . Target folder is displayed in the home directory
![image](https://github.com/Faseeha001/Build-java-using-Maven/assets/169563689/162995d8-19ce-422d-bef7-02d26c00bcb2)
![image](https://github.com/Faseeha001/Build-java-using-Maven/assets/169563689/01fa90ce-7e18-473a-adef-736926e07471)

Step 7 : Run Your Application: Once the build is successful, you can run your application using the generated JAR file

![image](https://github.com/Faseeha001/Build-java-using-Maven/assets/169563689/dc16421e-f890-4c95-8ceb-bec5e1494fb6)














