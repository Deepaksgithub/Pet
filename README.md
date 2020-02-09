### Serenity Rest Assured acceptance testing

Pre-requistes:

##Installation:
1)Java 1.8
2)Maven
3)Eclipse

##Setup:
1)one should have strong core java knowledge.
2)one should understand how the http methods work and the client server communication model.
3)Basic knowledge on the server protocols.
 
 About Project setup:
1)The project is a combination of cucumber and serenity rest assured framework which uses java language.
2)All the supporting library library are managed using Maven.
3)srenity.properties file contains the configuration related code lines
4)Also the core environment setup is placed in the EnvironmentSetup.java file
5)This project uses proxy and it should be used for querying the request and responses.
6)You can run the project using cucumber tags.Below is the command to run the regression.

    mvn verify -Dcucumber.options="--tags @managepet"
    
7)Since this a open source project, You can fecth information on Serenity Rest Assured official documentations.
8)The step definition file contains the implementation of the features and model contains the information to be posted and queried.
8)API files contains the actual implementation of querying process.
9)you can find the result in the Target folder generated after run Target->Serenit->Site->index.html
