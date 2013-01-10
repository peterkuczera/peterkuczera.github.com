---
layout: post
title: "Hosting your blog on GitHub using Octopress"
date: 2013-01-10 00:47
comments: true
categories: [octopress]
---

[Jekyll](https://github.com/mojombo/jekyll) is a static site generator.  It allows you to write your pages in Textile or Markdown which then gets compiled into HTML.  Because no server side scripting or databases are involved, page load times are lightning fast.  You can host these static HTML files on your own web server, [Amazon S3](http://aws.typepad.com/aws/2011/02/host-your-static-website-on-amazon-s3.html), or even use [GitHub Pages](http://pages.github.com).  I decided to go with GitHub Pages for this blog.

[Octopress](http://octopress.org/) is a static blogging framework that builds on top of Jekyll.  In addition to all the benefits Jekyll provides, Octopress also gives you a default theme and some handy rake scripts for common tasks.  For example, to generate a new post you can run:

``` bash
rake new_post["Title of your new post"]
```

Deploying your changes is as simple as running:

``` bash
rake deploy
```

If you're interested in setting this up yourself, everything you need can be found in the Octopress [documentation](http://octopress.org/docs/), including how to [deploy](http://octopress.org/docs/deploying/github/) to GitHub.
