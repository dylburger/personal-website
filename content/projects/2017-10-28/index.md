---
client: "Rate That Meeting"
title: "Rate That Meeting"
cover: "./submit-feedback.png"
date: "2017-10-28"
service: "MailCoach"
description: "A platform to help you submit anonymous feedback for meetings you attend, receive feedback for meetings you organize, and get personalized suggestions for how to spend less time in meetings"
---

From September 2017 to May 2018, I built [Rate That Meeting](https://ratethatmeeting.com/).

The platform had two core components: an automated way to collect anonymous feedback from meeting participants, and a team dashboard to help managers and executives see how their team spends their time in meetings.

We shipped this to hundreds of users at over 50 companies.

**Tech**

* React / Redux / ES6 frontend served by S3 / Cloudfront
* API Gateway / Lambda / DynamoDB to manage user-facing APIs
* Kinesis / Lambda to process real-time updates to users' calendars
* All architecture orchestrated by CloudFormation templates (100+ stacks)
* Cloudwatch to manage alerts / logging
* Kinesis Firehose / S3 / Athena for analytics
* Extensive use of KMS to manage encryption. Fine-grained control of permissions using IAM
* [Strong focus on security throughout the platform](https://ratethatmeeting.com/security/)
* Google Calendar API
