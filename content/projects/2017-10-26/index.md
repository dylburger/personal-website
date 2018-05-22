---
client: "MailCoach Email Service"
title: "MailCoach Email Service"
cover: "./mailcoach.png"
date: "2017-10-26"
service: "MailCoach"
description: "Data-driven, programmatic Gmail filters to help you spend less time in email"
---

I developed [MailCoach](https://www.mailcoachapp.com/) to help people spend less time in email. We used data on your habits in email (e.g. what emails you read, what senders you responded to) to programmatically suggest filters so emails you didn't need to read would skip your inbox.

**Tech**

* React / ES6 frontend
* API Gateway / Lambda / DynamoDB to manage core APIs
* Kinesis / Lambda to process push notifications from Gmail (as you read, archived or deleted email, Gmail would send events in real-time that we processed to enable productivity suggestions).
* Gmail API
