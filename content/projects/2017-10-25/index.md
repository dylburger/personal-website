---
client: "MailCoach Chrome Extension"
title: "MailCoach Chrome Extension"
cover: "./mailcoach-v1.png"
date: "2017-10-25"
service: "MailCoach"
description: "Chrome extension to gamify email productivity"
---

The MailCoach Chrome Extension tracked the time you spent actively processing email in the Gmail web client, combining that with data from the Gmail API on the actions you took in email (e.g. archiving, deleting, sending) to calculate a productivity score. From that score, we ranked your productivity against everyone else in your company also using the app.

**Tech**

* React / ES6
* API Gateway to manage HTTP endpoints to AWS
* Lambda script to process productivity stats
* Redis ([ElasticCache](https://aws.amazon.com/elasticache/)) to store productivity stats
* Gmail API
