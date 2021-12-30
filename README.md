# Udagram

[![CircleCI](https://circleci.com/gh/ngozi-ekekwe/udagram/tree/main.svg?style=svg)](https://circleci.com/gh/ngozi-ekekwe/udagram/tree/main)


This project is part of the Udacity FullStack JavaScript nanodegree. The code was given as a starter project and the task was to deploy the application and get it hosted on AWS.

http://udagramfrontendng.s3-website.eu-central-1.amazonaws.com


## AWS Architecture

![Screenshot 2021-12-29 at 20 47 55](https://user-images.githubusercontent.com/11598255/147698283-e1ff7732-611f-445b-bb99-54099950504a.png)


## Pipeline

![Screenshot 2021-12-29 at 21 04 39](https://user-images.githubusercontent.com/11598255/147699415-77182c77-fbd4-420e-832f-3b82ffa33224.png)




## AWS RDS 

The Postgres Database is on an RDS instance. The RDS instance is configured to automatically scale up and down based on the number of requests.

![Screenshot 2021-12-29 at 21 07 30](https://user-images.githubusercontent.com/11598255/147699732-cdc643b5-b8b0-4ec9-a257-47a522991688.png)



## AWS Elastic Beanstalk

The Node.js application is deployed to AWS Elastic Beanstalk. The application is configured to automatically scale up and down based on the number of requests.

![Screenshot 2021-12-29 at 21 12 04](https://user-images.githubusercontent.com/11598255/147699865-33f71ecc-553f-4b37-8d30-8e2a7aea0da1.png)



## AWS Media Bucket

The Frontend application is deployed to AWS S3. The application is configured to automatically scale up and down based on the number of requests.

![Screenshot 2021-12-29 at 21 14 31](https://user-images.githubusercontent.com/11598255/147699983-bd6ff5b5-96bc-4dac-9e86-3dbb3ce948ef.png)



## Environment Variables on CircleCI 

![Screenshot 2021-12-30 at 02 21 17](https://user-images.githubusercontent.com/11598255/147715168-3553140a-7ade-4d2d-8276-fc9e792a5cf2.png)



## CircleCI Builds
![Screenshot 2021-12-30 at 02 43 28](https://user-images.githubusercontent.com/11598255/147715190-24811959-b0db-40c4-bea7-4a4e82de83eb.png)







