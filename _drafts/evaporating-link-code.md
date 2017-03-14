---
layout: post
title: "Evaporating.Link"
excerpt: "Upload and share temporary files for free."
image: "images/alexandru-stavrica-151941.jpg"
imageattribution: "Alexandru Stavrica"
imageattributionlink: https://unsplash.com/@alexandru_stavrica
tags:
  - project
  - blog
---

# Evaporating.Link

[Evaporating.Link](http://evaporating.link) is a simple file sharing service hosted in the cloud.

Share your file in 3 easy steps, and you don't even have to worry about it hanging around.

1. Sign in to Google
2. Select a file to upload
3. Click upload

The link is then shown on the screen to be copied!

The file will be deleted after 1 day, so there is no need to worry about your files floating around forever.
Indexing uploaded files have been blocked so they won't appear in search engines.

## Architecture

This project utilises some key features of AWS in order to provide a cheap and scalable fully managed service.

Diagram here

S3, lifecycle policy, bucket policy, IAM role, Cognito, Cloudfront (why not)?

## CSS Tricks

Maybe make a seperate post for this?

Flex box, scale fonts using vmin (compare vw/vh/vmin/vmax)

## Javascript Play by Play

Step by step guide through the Javascript. This really needs it's own post...

Mention bucket policy requires ACL policy in IAM