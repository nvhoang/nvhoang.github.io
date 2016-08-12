---
layout: post
section-type: post
title: More resources on golang
category: Category
tags: [ 'golang', 'resources' ]
---

I have a chance to use golang for a serious project. Here's a couple of resources that I came across and found very useful.

* [mgo for mongodb](https://github.com/go-mgo/mgo): This one is perhaps one of the best mongodb driver out there.
* A small [example](http://goinbigdata.com/how-to-build-microservice-with-mongodb-in-golang/) on how to build microservice using golang.
* Another one on [how to use mgo with concurrency](http://blog.mongodb.org/post/80579086742/running-mongodb-queries-concurrently-with-go) effectively.

Some gotchas:
* I stumbled upon receiver and pointer receiver. The conclusion is that it works like C++ (if you know it). Use pass-by-value until performance becomes a concern.

