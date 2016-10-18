---
layout: post
title: Build Tensorflow on amazon EC2 (TBD)
---

This post is based on a helpful post on https://groups.google.com/a/tensorflow.org/forum/#!topic/discuss/jRkkvsB1iWA
I would assume that you know how to launch a instance on AWS.

1. Launch a instance
Get following AMI on a GPU instance. 
https://aws.amazon.com/marketplace/pp/B00FYCDDTE

I have chosen g2.2xlarge, 16GB SSD for test. Choosing 8GB might be fine if build the stuff carefully.

2.
