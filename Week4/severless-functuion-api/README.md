# Serverless Function API

## Project Overview
In this project, I built a simple serverless API using AWS Lambda and API Gateway. The API returns different JSON responses through multiple endpoints.

## Tools Used
- AWS Lambda
- API Gateway
- Node.js

## What I Did
- Created a Lambda function
- Wrote Node.js code for the function
- Tested the function successfully inside AWS Lambda
- Added API Gateway as a trigger
- Created multiple routes
- Added an environment variable
- Tested the API endpoints successfully in the browser

## Environment Variable
- INTERN_NAME = Happiness Isaac

## Endpoints Created
- /hello
- /about
- /status

## Steps I Followed
1. Opened AWS Lambda
2. Created a function called `hello-api-function`
3. Chose Node.js runtime
4. Added the Lambda code
5. Deployed the code
6. Created and saved a test event
7. Tested the function successfully
8. Added API Gateway as a trigger
9. Opened API Gateway
10. Created additional routes: `/hello`, `/about`, `/status`
11. Attached the routes to the Lambda function
12. Added an environment variable called `INTERN_NAME`
13. Tested the base API response
14. Tested `/hello`, `/about`, and `/status` successfully

## Challenge I Faced
At first, the `/hello`, `/about`, and `/status` routes returned `Not Found` because the routes had not been attached to the Lambda integration in API Gateway.

## How I Fixed It
I opened API Gateway, created the routes properly, and attached each route to the `hello-api-function` Lambda integration. After that, the endpoints worked successfully.

## Outcome
The serverless API worked successfully, and I was able to test multiple endpoints in the browser.

## Screenshots
See the uploaded screenshots for proof of setup, testing, trigger configuration, and working API endpoints.
