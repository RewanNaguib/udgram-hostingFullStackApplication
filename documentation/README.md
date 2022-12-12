# Steps to Deploy Fullstack application:

## Make sure project works fine locally:

### api project:

* Create .env file on the root of udagram-api directory
* Add all required environmental variables in the .env
* Run "cd udagram/udagram-api" then run,
* npm install
* npm run build
* npm run dev


### Frontend project:

* Run "cd udagram/udagram-frontend" the run
* npm install --legacy-peer-deps
* npm run build
* npm run start


### Deploy project on AWS:

* Setup AWS cli & eb cli
* Change .env with the AWS variables
* Create deploy.sh files with required scripts to deploy frontend and backend projects
* Create Configuring Continuous Integration Pipeline with Github "steps are in pipeline-README.md file"


### The Application is accessible via this link: 
http://udagram-bucket-2022.s3-website-us-east-1.amazonaws.com