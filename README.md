Welcome to the ForkedBlock Community Site
==================================================


* README.md - this file
* app.js - this file contains the code for your application
* appspec.yml - this file is used by AWS CodeDeploy when deploying the web
  application to EC2
* package.json - this file contains various metadata relevant to your Node.js
  application such as dependencies
* public/ - this directory contains static web assets used by your application
* scripts/ - this directory contains scripts used by AWS CodeDeploy when
  installing and deploying your application on the Amazon EC2 instance
* tests/ - this directory contains unit tests for your application
* template.yml - this file contains the description of AWS resources used by AWS
  CloudFormation to deploy your infrastructure

1. Install NPM dependencies:

        $ npm install

2. Start the development server:

        $ node app.js

3. Open http://127.0.0.1:3000/ 
