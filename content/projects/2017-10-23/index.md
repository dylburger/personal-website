---
client: "Wedding Website with GatsbyJS & CloudFormation"
title: "Wedding Website with GatsbyJS & CloudFormation"
cover: "./wedding.png"
date: "2017-10-23"
service: "Personal"
description: "Wedding Website with GatsbyJS & CloudFormation"
---

I used our [wedding website](https://dylbaum.com/) as an opportunity to play with [GatsbyJS](https://www.gatsbyjs.org/). I'm also a huge fan of using CloudFormation to manage all the resources tied to single page apps (ACM certificate, Route53 records, Cloudfront distribution and S3 buckets).

During the course of this project, I created 

* A [GatsbyJS repo](https://github.com/dylburger/dylbaum.com) anyone can use to create their own wedding website.
* A [CloudFormation template](https://github.com/dylburger/wedding-website-cloudformation-templates) for the AWS resources associated with the website.
* A [Python script to create a new ACM certificate for your domain](https://github.com/dylburger/create-and-validate-acm-certificate), automatically [validating the domain](https://docs.aws.amazon.com/acm/latest/userguide/gs-acm-validate-dns.html) with a DNS record using Route53.
