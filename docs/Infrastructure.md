# Infrastructure

## AWS Architecture

Full Stack app hosted on the AWS Cloud.

![Screenshot 2021-12-29 at 20 47 55](https://user-images.githubusercontent.com/11598255/147698283-e1ff7732-611f-445b-bb99-54099950504a.png)


## AWS RDS 

The Postgres Database is on an RDS instance. The RDS instance is configured to automatically scale up and down based on the number of requests.

![Screenshot 2021-12-29 at 21 07 30](https://user-images.githubusercontent.com/11598255/147699732-cdc643b5-b8b0-4ec9-a257-47a522991688.png)


## AWS Elastic Beanstalk

The Node.js application is deployed to AWS Elastic Beanstalk. The application is configured to automatically scale up and down based on the number of requests.

![Screenshot 2021-12-29 at 21 12 04](https://user-images.githubusercontent.com/11598255/147699865-33f71ecc-553f-4b37-8d30-8e2a7aea0da1.png)



## AWS Media Bucket

The Frontend application is deployed to AWS S3. The application is configured to automatically scale up and down based on the number of requests.

![Screenshot 2021-12-29 at 21 14 31](https://user-images.githubusercontent.com/11598255/147699983-bd6ff5b5-96bc-4dac-9e86-3dbb3ce948ef.png)
