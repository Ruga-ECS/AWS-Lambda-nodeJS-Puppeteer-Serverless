<!--
title: 'AWS Lambda deploying template for Puppeteer'
description: 'This example shows you how to run Puppeteer on AWS Lambda'
framework: v1
platform: AWS
language: nodeJS
authorLink: 'https://github.com/Battiatus'
authorName: 'Ruga'

-->

Running Puppeteer on AWS Lambda Using Serverless Framework

Instruction to deploy on AWS through Serverless

Module and software needed

- IDE (Visual Studio, Notepad++, Sublime text...)
- NodeJS
- Administrator power on computer
- AWS CLI (You can download it on https://awscli.amazonaws.com/AWSCLIV2.msi)


### Instructions 
- Clone the project

```
$ git clone https://github.com/Battiatus/aws-node-puppeteer.git

```

- Open your terminal as "Administrator" if possible

- Install NodeJS
```
$ npm install 
```
- Install Serverless
```
$ npm install -g serverless
```

### To Deploy on AWS 

- Add your profile AWS

```
$ serverless config credentials --provider aws --k <put your aws client key> --s <Put your secret key>
```
Now you can deploy your project on AWS lambda

```
$ sls deploy
```
To be able to monitor your Serverless,you can create your account on Serverless 
```
$ serverless dashboard
```

___________
# About Project 

## Solution 

You can now update the project by a dding your script into hander.js

Good luck
