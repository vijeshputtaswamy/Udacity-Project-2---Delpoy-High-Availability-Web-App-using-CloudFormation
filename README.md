# Udacity-Project-2---Delpoy-High-Availability-Web-App-using-CloudFormation

In this project, you’ll deploy web servers for a highly available web app using CloudFormation. You will begin with deploying the networking components, followed by servers, security roles and software. You’ll do it exactly as it’s done on the job - following best practices and scripting as much as possible.

You  Will deploy an application (Apache Web Server) and you also pick up code (JavaScript and HTML) from S3 Storage and deploy it in the appropriate folder on the web server.
There will be two parts to this project:
1> You'll first develop a diagram that you can present as part of your portfolio and as a visual aid to understand the CloudFormation script.
2> The second part is to interpret the instructions as well as your own diagram and create a matching CloudFormation script.

Note: Once you have your script you can verify those scripts before you deploy with below command:
aws cloud-formation validate-template --template-body file://stack.yml
