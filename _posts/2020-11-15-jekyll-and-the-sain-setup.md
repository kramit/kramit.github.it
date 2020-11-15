---
layout: post
title: Jekell and the sane setup tools
date: 2020-11-15 19:50 +0100
category: 
author: Michael Whitehouse
tags: []
summary: 
---

## Things that pissed me off when trying to get a jekyll blog up




#### Make a new post with automatic front matter (the bits that catagorise the post)

https://marketplace.visualstudio.com/items?itemName=rohgarg.jekyll-post

![an image alt text] (kramit.github.io/images/newposttool.png "New post tool")

![an image alt text] (kramit.github.io/images/jekyll-logo.png "an image title")



#### UTC BST bullshit

if the date is like this in the front matter the post renders

date: 2020-11-15 19:50 +0100

if it is like this the jekyll decides it doesnt exist

date: 2020-11-15 19:50


#### Images in the /images dir


/images in the root of the repo relies on 

