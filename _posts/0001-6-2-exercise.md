---
layout: default
title: "Exercise (Hadoop on EC2)"
published: true
classes:
 - slide
data:
  x: 5000
  y: 800

---

* create/customize and run one or more MapReduce programs with Hadoop, in the us-east-1 (N. Virginia) zone
	* You'll need to have the [EC2 API tools](http://aws.amazon.com/developertools/351) installed
	* Then see [AmazonEC2 - Hadoop Wiki](http://wiki.apache.org/hadoop/AmazonEC2)
* sample input data available on [S3](http://aws.amazon.com/s3/), in the bucket “ad-bootcamp”
	* [Popular Tales](http://s3.amazonaws.com/ad-bootcamp/pg42839.txt) [src](http://www.gutenberg.org/ebooks/42839)
	* [Original Narratives of Early American History](http://s3.amazonaws.com/ad-bootcamp/pg42841.txt) [src](http://www.gutenberg.org/ebooks/42841)
	* [WCM 11 Access Log](http://s3.amazonaws.com/ad-bootcamp/wcm11_access_log)
* pre-created out buckets on S3 called “ad-emr-out”