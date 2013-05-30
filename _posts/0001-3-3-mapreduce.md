---
layout: default
title: "MapReduce"
published: true
classes:
 - slide
data:
  x: 2000
  y: 1600

---

* a programming model for distirbuted computing
* inspired by the *map* and *reduce* primitives in Lisp and other functional languages
* **map** function: takes in a key/value pair, to generate a set of intermediate key/value pairs<br />(K1, V1) → list(K2, V2)
* **reduce** function: merges intermediate values sharing the same key<br />(K2, list(V2)) → list(K3, V3)
* many real world tasks are expressible in this model