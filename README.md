# ElasticBeanstalk_ECS

Getting Started With Cloud9
========================

1. Open Cloud9 Environment
2. Add Node.js to make it easier to open files from the Terminal
```
npm i c9 -9
```
3. Create a folder and then navigate to it in your terminal
4. Initialize an empty node project (This creates a .json package)
```
npm init -y
```
5. To run a web app you will need web framework. Install Express dependecy
```
npm i express --save
```
6. Navigate to your package.json file and add the following under the "scripts"
```
"start" : "node index.js"
```
This allows you to actually have a way of running your scripts in node.

Open Cloud9 Security Ports
===================================
1. Navigate to your EC2 Instance home page.
2. Select the Cloud9 Instance
3. Navigate to its security group
4. Select the inbound rules and add Custom TCP Protocol to port 8080

Starting the app through the Cloud9 CLI
======================================
1. Use the command below to get your public ipv4 address
```
curl -s http://169.254.169.254/latest/meta-data/public-ipv4
```
2. Add http:// to the front of your public ip address, and add the port number to the end.

Add Git 
=========
```
Git init
Git Add .
Git Commit -m"YOUR MESSAGE HERE"
```

Next Install the Elastic Benstalk Environment through this link: 
==============================
https://github.com/aws/aws-elastic-beanstalk-cli-setup

