---
layout: default
title: "Exercise (Hadoop on Mac)"
published: true
classes:
 - slide
data:
  x: 5000
  y: 1600

---

* create/customize and run one or more MapReduce programs with Hadoop, in the us-east-1 (N. Virginia) zone
	* Install hadoop using [Homebrew](http://mxcl.github.io/homebrew/)
	* See [INSTALLING HADOOP ON MAC OSX LION](http://ragrawal.wordpress.com/2012/04/28/installing-hadoop-on-mac-osx-lion/)
* [Writing An Hadoop MapReduce Program in Python](http://www.michael-noll.com/tutorials/writing-an-hadoop-mapreduce-program-in-python/) 
* sample input data available on [S3](http://aws.amazon.com/s3/), in the bucket “ad-bootcamp”
	* [Popular Tales](http://s3.amazonaws.com/ad-bootcamp/pg42839.txt) [src](http://www.gutenberg.org/ebooks/42839)
	* [Original Narratives of Early American History](http://s3.amazonaws.com/ad-bootcamp/pg42841.txt) [src](http://www.gutenberg.org/ebooks/42841)
	* [WCM 11 Access Log](http://s3.amazonaws.com/ad-bootcamp/wcm11_access_log)
* pre-created out buckets on S3 called “ad-emr-out”