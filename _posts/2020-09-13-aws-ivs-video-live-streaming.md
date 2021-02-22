---
layout: post
title: "Setting up a streaming service with AWS IVS platform"
description: ""
date: 2020-09-13
tags: aws ivs streaming dev wip
comments: true
---


## What is AWS IVS?
[Amazon Interactive Video Service (Amazon IVS)](https://aws.amazon.com/ivs/) is a managed live streaming solution.

It's easy to stream nowadays via Youtube, Facebook, Instagram to your audience. How about on your own platform? Amazon IVS helps developers to build a system to stream low-latency live video to viewers around the world easily.


## Create a live stream
Create a live stream takes 3 steps:

Step 1, create an IVS channel
Step 2, start your stream
Step 3, view your live stream on client player


![Stream to different clients](https://ivs-streaming.workshop.aws/images/ivs-workshop-step2.png)

source: [https://ivs-streaming.workshop.aws/en/](https://ivs-streaming.workshop.aws/en/)


## OBS Stream

OBS is free and open source software for video recording and live streaming.


## Creating Stream from mobile

For those who are experienced from streaming may know about [OBS Studio](https://obsproject.com)

### Pre-built client
[Streamlabs](http://streamlabs.com/)

### Custom client





---

Draft

### Pricing Example
The total cost of a two-hour event with Standard input at 1080p and delivered to 200 viewers from the US (100 viewers in SD, 50 viewers in HD, and 50 viewers in Full HD) is $34.00.

Live Video Input:

Standard Channel = $2.00 per hour * 2 hours = $4.00

Live Video Output:
SD output from North America = $0.0375 per hour * 2 hours * 100 viewers = $7.50
HD output from North America = $0.0750 per hour * 2 hours * 50 viewers = $7.50
Full HD output from North America = $0.1500 per hour * 2 hours * 50 viewers = $15.00

$4.00 + $7.50 + $7.50 + $15.00 = $34.00

