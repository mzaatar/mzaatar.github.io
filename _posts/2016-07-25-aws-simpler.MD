---
layout: post
title:  "AWS simpler"
date:   2016-07-16 18:00:00 +0800
categories: AWS Amazon Cloud
---

I'm studying and exploring AWS (Amazon Web Service). My main source for these definitions is [ACloudGuru](https://acloud.guru/) course.

I found AWS services too much to memorize so I created a list and I called it _AWS Simpler_. Simply, I would like to define all AWS services and products definitions within groups with very simple words.
And I want to share it with the internet!

* **General**
    * Region: geographic place for AWS Services
    * Availability zone: simply a data centre
    * Edge location: CDN endpoint (for Content Delivery Network)

* **Network**
    * VPC: Virtual Private Cloud. Private data centre which is isolated set of resources
    * DirectConnect: a service to install on premises to connect you directly to your data centre
    * Route53: Amazon DNS (Why 53? because it is DNS port)

* **Compute**
    * EC2: Simply a virtual server
    * ECS: EC2 Container Service - for docker containers
    * Elastic beanstalk: web app hosting
    * Lambda: provisioning code without running a server. Most powerful service, pay for running computing time

* **Storage**
    * S3: object-based storage. Not block-based storage. Pay for the storage that you use.
    * Cloud Front: CDN endpoint to cache your files in edge locations
    * Glacier: archiving low cost storage and backups. Around 4 hours to access files
    * EFS: Elastic File System as NAS in the cloud. Block level storage
    * Snowball: Import/export. Send your own hard disk and import data into cloud. Enterprise level. It looks like a suitcase. Pay on daily basis
    * Storage Gateway: integration between on premiss and cloud. Virtual machine that run on your premises and replicate your data into the cloud

* **Database**
    * RDS: cloud db service, including Oracle, SQL Server, MySQL, Aurora, Maria db
    * Dynamo DB: NoSQL Amazon service
    * Elastic cache: caching your db service, 
    * Redshift: Amazon db warehouse. Great performance
    * DMS: Database Migration Service. migrating db into AWS and convert from Oracle to MySQL

* **Analytics**
    * EMR: Elastic Map Reduce, processing big data
    * Data pipeline: move data from service to into another service
    * Elastic Search: Open source search analytics service. Monitor data
    * Kinesis: Streaming data
    * Machine Learning: simply a machine learning service
    * Quick Sight: new service. BI service. Fast, power, cloud based ad-hoc analysis

* **Security and Identity**
    * IAM: control your users, groups, password, MFA
    * Directory Services: it has different types and think of it as Microsoft Active Directory
    * Amazon Inspector: install agent on VM and inspect security
    * WAF: Web Application Firewall
    * Cloud HSM: Hardware security Module
    * KMS: Key Management Service

* **Management Tools**
    * Cloud Watch: Monitor application and resources
    * Cloud Formation: best thing in AWS. JSON and UI based
    * Cloud Trail: provide Audit access on AWS
    * OpsWorks: configure application using Chef
    * AWS Config: fully resource inventory for governance
    * Service Catalogue:
    * Trusted Advisor: automated scan for your service and how to save money. Two tiers (free and enterprise)

* **Application Service**
    * API gateway: for developers to create and publish API
    * AppStream: stream your windows screen. For tablets, windows. AS XenApp
    * CloudSearch: Managed service to set up search solution for your website. Highlighting and search
    * Elastic Transcoder: High scalable to convert media formats from mobile etc
    * SES: Simple Email Service, Send and receive emails
    * SQS: Simple Queue Service. First service introduced by AWS
    * SWF: Simple WorkFlow, used by Amazon when buying something

* **Developer Tools**
    * CodeCommit: source control. As Github
    * CodeDeploy: Automate code deploy 
    * CodePipeLine: continuous delivery service

* **Mobile Service**
    * Mobile Hub: Monitor and test your mobile app usage
    * Cognito: Save your mobile data, app preference as settings
    * Device Farm: enable testing mobile app in AWS
    * Mobile Analytics.
    * SNS: Simple Notification Service

* **Enterprise Applications
    * Workplaces: virtual desktop in the cloud
    * WorkDocs: safe place to safe your files. As DropBox, OneDrive 
    * WorkMail: AWS exchange

* **IoT**
    * Internet of Things: IoT platform for IoT devices