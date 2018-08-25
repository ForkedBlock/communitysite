Welcome to the AWS CodeStar sample web application
==================================================

This sample code helps get you started with a simple Node.js web application
deployed by AWS CodeDeploy and AWS CloudFormation to an Amazon EC2 instance.

What's Here
-----------

This sample includes:

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

        $ npm install
        $ node app.js


3. Open http://127.0.0.1:3000/ in a web browser to view your application.

How Do I Add Template Resources to My Project?
------------------

To add AWS resources to your project, you'll need to edit the `template.yml`
file in your project's repository. You may also need to modify permissions for
your project's worker roles. After you push the template change, AWS CodeStar
and AWS CloudFormation provision the resources for you.

See the AWS CodeStar user guide for instructions to modify your template:
https://docs.aws.amazon.com/codestar/latest/userguide/how-to-change-project#customize-project-template.html

What Should I Do Before Running My Project in Production?
------------------
