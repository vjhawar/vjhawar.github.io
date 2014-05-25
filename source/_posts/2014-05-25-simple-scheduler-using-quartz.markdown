---
layout: post
title: "Simple scheduler using Quartz"
date: 2014-05-25 03:49:11 +0530
comments: true
categories: 
published: false
---

There are lot of use cases which require running jobs ata regular intervals and you want to avoid crons beyond point.
They are not easy to manage and suddenly you can have them spread all over your cluster not realizing that they are soon competing against each other for resources.

A simple solution is to build a scheduler server using the Quartz in Java. It provides a pretty neat api to run jobs and manage them with little code.

