---
client: "awsbudget"
title: "awsbudget"
cover: "./awsbudget-png.png"
date: "2017-10-23"
service: "Personal"
description: "Python command line utility for creating AWS Budgets"
---

I'm fascinated with the idea of [CloudFormation](https://aws.amazon.com/cloudformation/) and infrastructure as code. Every change you make to your architecture should be managed as a state change that can be rolled back, version-controlled, and repeated. There are a variety of tools to facilitate the use of CloudFormation, but I wanted to experiment with my own tool to learn a few things:

* How can we abstract interaction with CloudFormation from the user?
* How do you build modern command-line Python apps?
* How do you package and deploy apps on [PyPi](https://pypi.org/)?

I built a tool called [`awsbudget`](https://pypi.org/project/awsbudget/), that gives users a command-line tool to create a budget in AWS. Behind the scenes, the tool creates a CloudFormation stack to manage this budget.
