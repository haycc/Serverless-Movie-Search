# Serverless-Movie-Search
This assignment uses existing Movie Search HTML code to build a serverless application by writing an AWS Lambda function in nodejs, API Gateway, and DynamoDB table. The movie search code uses AJAX to trigger the AWS Lambda function, which makes an API call to the OMDB API and returns the result in JSON. The event is logged in the DynamoDB table.

## Getting Started
To view the site and search the OMDB Movie Database, visit https://s3.amazonaws.com/movie120518/movie/index.html

## Prerequisites
- Node.js/AWS

## Technologies Used
- Node.js/NPM
- AWS
- Lambda
- DynamoDB
- S3