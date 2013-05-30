# Distributed File Systems and MapReduce

## 1-1: Google

* At the time, search engines ranked based on keyword frequency.
* Indexes of the web existed before search engines
* PageRank value indicates the importance of a particular page.
	* a hyperlink counts as a vote of support

## 2-3: Scale of Information

* today, Google operates at 16 significant data centers around the world

## 2-4: Google's Oregon Data Center

* pipes carry water in and out of data center
* blue pipes supply cold water
* red pipes return the warm water back

## 2-5: Powerful Software

* What challenges might the storage and processing systems face?
* Characteristics:
* Challenges:

## 3-1: Research at Google

* Google's published research papers give us clues into their approaches to Big Data

## 3-2: Google File System

* GFS has a relaxed consistency model to simplify the file system without imposing a burden on apps
* has atomic append operation so multiple clients can append concurrently to a file without extra synchronization
* optimized for large, not small files
* prioritizes high sustained bandwidth over low latency
* FS API co-designed with applications
* snapshot: eg branching
* append: eg producer-consumer

## 5-1: Big Data

* ViaWest, one of the largest privately-held data center, cloud and managed services provides in North America
* 2.5 quintillion B = 2.5 million TB
* velocity: how fast; variety: the kinds of data; volume: the quantity of data
* NASDAQ: 900 million transactions per week

## 5-2: Hadoop

* Common: utilities that support other Hadoop modules
* YARN job scheduling and cluster resource management

