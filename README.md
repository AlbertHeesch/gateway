## About
Welcome!  
The project you are looking at is a gateway server.

##Microservices & Front End
In order to run my application properly please use these projects:
- Configuration server - https://github.com/AlbertHeesch/cloud,
- Discovery - https://github.com/AlbertHeesch/discovery,
- Main Back End - https://github.com/AlbertHeesch/DentClinicApp,
- Rates Back End - https://github.com/AlbertHeesch/DentClinicAppRates,
- Front End - https://github.com/AlbertHeesch/DentClinicAppView,
- Integration Test Suite - https://github.com/AlbertHeesch/DentClinicAppTesting.

## Requirements:

Java 11

Gradle

## How to run

Build your gradle with `gradlew build` in terminal.

Run the projects in order:
- Configuration server,
- Discovery,
- Gateway,
- DentAppClinic & DentAppClinicRates,
- DentAppClinicView.

Enter the http://localhost:8085/home page in your browser.