# APITestingProject

API REST skeleton used for this project can be found on: https://github.com/davellanedam/node-express-mongodb-jwt-rest-api-skeleton

The project consists of a collection of requests (different HTTP requests such as GET, POST, PATCH, DELETE)
divided into categories: auth, city, profile, user and a series of test scripts for each category. Pre-request
scripts are used to ensure that tests will be run in the correct environment, etc. with the help of different 
dynamic and environment variables. 

For every request several test scripts were written to validate responses and to sets up checkpoints to verify
if response status is ok, retrieved data is as expected, proper authorization is needed (ex. bearer token) among others. 
In a couple of tests, JSON schema was tested to check whether the structure of JSON data from the response body
is as anticipated. Every test script implemented Chai Assertion Library. The whole project was run on the local
machine using MongoDB in conjunction with the Node.js to store and access data.


Link to Postman collection : https://documenter.getpostman.com/view/13472438/TVenf96G
