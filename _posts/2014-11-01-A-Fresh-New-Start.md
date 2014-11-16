---
layout: post
title: Hello, My Name is Sean
description: My Journey to Github
headline: "Hello, My Name is Sean"
categories: personal
tags:
  - blogging
  - jekyll
image:
  feature: "disneyland.jpg"
  credit: spreadeffect.com
  creditlink: "http://www.spreadeffect.com/blog/improve-website-speed/"
comments: false
mathjax: null
featured: true
published: true
---

##My Journey to Github

I wouldn't call myself a developer, nor a web designer, but I enjoy doing such activities. I have been dabbling with computers, web design, python, wordpress, php / mysql, django and the likes. This is my first step into the world of Git and also the use of Markdown / Kramdown syntax. 

> Learning new things is amazing!

Learning new things can be painful too. But rewarding nonetheless. I switched over to Github for a few reasons. Free stuff is always appreciated and Github offers great response / connection across anywhere in the world. Better than the usual web host in fact and I figured it would be a fantastic place to host my website. Next up, Github has always been about a code repository and I have seen so many past work / websites disappear in dust and I didn't want that to happen again. I recently had the same problem with Wordpress as it was a pain to migrate them due to the MySQL databases. However, I have since learned an easier way to do it.

This is not the foolproof way to backup a Wordpress site, but rather it is a quick step to convert a WordPress site to static HTML and CSS. Perhaps more for archiving purposes. This needs a Linux / Unix terminal, and through using a command, called wget. 

Type or copy the following command into the terminal. You would need to replace yoursite.com.

    wget -p -P ~/Desktop/staticwp --convert-links -m -nH http://yoursite.com/

This will backup the site to a folder on your desktop called staticwp. 

Here's what's happening: 

    -p
  
> Tells wget to get all the necessary files to display the page (images, CSS, etc)

    -P ~/Desktop/websitebackup
    
> Sets the path on your local machine for the output (the new static version of your site)

    --convert-links

> After the download is complete, convert the links in the document to make them suitable for local viewing

    -m
    
> Turn on options suitable for mirroring. This option turns on recursion and time-stamping, sets infinite recursion depth and keeps ftp directory listings.

So that's that for backing up Wordpress sites to a static copy, immensely useful but too bad I learnt it at a late stage before I could actually backup share-our-joy.com - I will re-create it in due course.

## Shifting to Jekyll

Why? Github host static websites and the closest to a dynamic CMS is Jekyll. Well there were definite advantages to the use of Jekyll - it is fast, bloat-free. But perhaps, I just wanted to learn something new. It is not that Wordpress is bad. In fact, tons of websites are based off Wordpress today and speed is easily fixed by caching and generating static files with WP-plugins and also using CDN to deliver media. 

So off to Jekyll it is. 

It is pretty simple setting up Jekyll on Github. Fork someone's repository, name it yourname.github.io and it get's published at the same link. Just be sure to update the posts and images before you go live. 





