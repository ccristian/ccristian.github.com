---
layout: post
title:  "Restricting specific media folders on Django"
date:   2021-08-12 10:03:49 +0700
categories: [python, django, security]
---

For example someone reported a crucial bug by using [`django-tellme`](https://github.com/ludrao/django-tellme),
then we don't want that screenshot to be accessable by any users except our staffs/superuser.

So, to handle that case I think we can use custom middleware;

