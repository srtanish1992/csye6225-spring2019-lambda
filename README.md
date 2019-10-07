## CSYE 6225 - Spring 2019

## Team Information

| Name | NEU ID | Email Address |
| --- | --- | --- |
| Abhinn Ankit | 001837913 | ankit.a@husky.neu.edu |
| Anish Surti | 001814243 | surti.a@husky.neu.edu |
| Srikant Swamy | 001212307 | swamy.sr@husky.neu.edu |
| Nilank Sharma | 001279669 | sharma.nil@husky.neu.edu |

## Technology Stack
### 1. Operating System
* AWS Serverless
### 2. Programming Language
* NodeJS
### 3. Backend
* NodeJS


## Build Instructions
  
## CI/CD

### Technology
* CircleCI

### Requirements
Environment varibales
* AWS_REGION
* AWS_SECRET_KEY
* AWS_ACCESS_KEY

### Usage
* A git commit will automatically execute CircleCI JOB
* A job can also be initiated using the following command
`curl -u 'put_circleci_user_token' -d build_parameters[CIRCLE_JOB]=build-lambda-function https://circleci.com/api/v1.1/project/github/<username>/csye6225-spring2019-lambda/tree/<branch>`
