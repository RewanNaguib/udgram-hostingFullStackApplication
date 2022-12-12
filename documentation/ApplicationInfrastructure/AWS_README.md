# Steps to deploy fullstack app on AWS:

## Create database on AWS:

* Search for RDS service
* Create database
* configure database name, Engine type , user name and password
* Click on create database
* Use the created endpoint in the api project to check for database connectivity.

## Upload API on AWS By Creating Elastic Beanstalk:
* Search for Elastic Beanstalk service
* Click create new environment
* Configure Application name, Environment name and Platform
* Upload backend build files after zipping them
* Make sure health status is "ok"
* Use the URL created in the frontend project in the environments file

## Upload Frontend on AWS By Creating S3 Bucket:
* Search for S3 service
* Click on create bucket
* Configure bucket name and make it public and enable Static website hosting
* Then click create bucket
* Navigate to permissions tab then edit bucket policy and set up a policy
* Check to properties tab to get the accessible link

## The Application is accessible via this link:
 http://udagram-bucket-2022.s3-website-us-east-1.amazonaws.com