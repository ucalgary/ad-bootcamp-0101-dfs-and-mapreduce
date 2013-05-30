---
layout: default
title: "Exercise (using EMR)"
published: true
classes:
 - slide
data:
  x: 5000
  y: 0

---

* create/customize and run one or more MapReduce programs with Hadoop, via [Amazon Elastic MapReduce](http://aws.amazon.com/elasticmapreduce/). Use the us-east-1 (N. Virginia) zone
* [Amazon Elastic MapReduce Ruby](http://aws.amazon.com/developertools/2264) Client might be useful. You will need your Access Key ID & Secret Access Key
* sample input data on [S3](http://aws.amazon.com/s3/), in the bucket “ad-bootcamp”
	* [Popular Tales](http://s3.amazonaws.com/ad-bootcamp/pg42839.txt) [src](http://www.gutenberg.org/ebooks/42839)
	* [Original Narratives of Early American History](http://s3.amazonaws.com/ad-bootcamp/pg42841.txt) [src](http://www.gutenberg.org/ebooks/42841)
	* [WCM 11 Access Log](http://s3.amazonaws.com/ad-bootcamp/wcm11_access_log)
* pre-created out buckets on S3 called “ad-emr-out”