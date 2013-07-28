---
layout: post
title: "Amazon EC2 instance comparison site"
date: 2013-06-17 12:28
comments: true
categories: [aws]
---

I’ve always found it difficult to compare Amazon EC2 instance type on amazon.com.  Instance specs are listed on one page and instance costs are found on another page.  You also need to worry about matching instances names to their description – e.g. an m1.medium instance is listed as a Standard On-Demand instance on the cost page.

[EC2Instances.info](http://www.ec2instances.info/) is a handy page that organizes Amazon EC2 instance types, specs and costs into a sortable table.  You can display costs by hour, day, month, etc. and also configure which columns to show.  The project is open source and hosted on [GitHub](https://github.com/powdahound/ec2instances.info).  If you create or resize EC2 instances on a regular basis, I’d recommend bookmarking this page.
