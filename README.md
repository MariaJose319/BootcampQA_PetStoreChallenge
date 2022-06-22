# Pet Store Challenge
In this repository, you can find a group of API tests, that were run by Newman from Postman.
The API tested was https://petstore.swagger.io/v2.

## Prerequisites
You need to have Node.js installed previously.

## Installation
You have to run these commands in the Command Prompt:
1.  To install Newman
```
npm install -g Newman
```
2. To install an extension to get an HTML report
```
npm install -g newman-reporter-htmlextra
```
## Running Tests
1. Clone this repository in a folder of your preference.
2. Open the Command Prompt and run:
```
newman run BootcampQA_PetStoreChallenge.postman_collection.json -e SwaggerPetstore.postman_environment.json -r htmlextra
```
3. Open the HTML generated file.