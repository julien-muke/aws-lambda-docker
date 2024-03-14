# ![aws](https://github.com/julien-muke/Search-Engine-Website-using-AWS/assets/110755734/01cd6124-8014-4baa-a5fe-bd227844d263)     Run a Python Docker Image on AWS Lambda


## 🤖 Introduction

Learn how to run a Python Docker image on AWS Lambda using Lambda container images.

Using Docker containers for your Python app on AWS Lambda means you can create a special environment for your app with its own tools and settings, making sure it works everywhere, and also making it easy to include all the things (libraries and packages)your app needs to run correctly.


## 📐 Architecture Design


![Tiny Tales Mail -2](https://github.com/julien-muke/Tiny_Tales_Mail/assets/110755734/8ad7533e-5ae5-4858-a6fb-581562d07857)


## ⚙️ AWS Services Used

* Amazon Simple Email Service (SES)
* AWS Lambda
* Amazon Simple Storage Service (S3)
* Amazon EventBridge
* AWS Identity and Access Management (IAM)


## 🔋 Features


👉 A place to store email templates and list of contacts

👉 A way to send emails

👉 A way to “merge” email templates with contacts and send them to the email service

👉 A way to trigger sending of emails on a schedule



## ➡️ Step 1 - Creating an S3 bucket to store email templates and contacts