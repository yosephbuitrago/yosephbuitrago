---
layout: post
title: The Pi Cloud
date: 2017-10-23 13:32:20 +0300
description: You’ll find this post in your `_posts` directory. Go ahead and edit it and re-build the site to see your changes. # Add post description (optional)
img: cluster_cartoon.png # Add image post (optional)
tags: [Raspberry pi, Docker, DevOps, Kubernetes]
---
Cloud computing and DevOps technologies like containers have experienced widespread for
the last couple of years. Nowadays, the field of software development is demanding specific
skills such as DevOps, cloud computing, big data analysis, etc. However, academia is being
challenged in providing courses and material to embrace this new paradigm of software development creating a gap between them. Therefore, this paper proposes the idea of implementing
a small-scale cluster using single board computers, in this case, raspberries pi. The aim of
this project is to allow students to experiment with these new concepts and technologies by
providing a low-cost test environment, the PI Cloud.

## Problem/Solution

The complexity of distributed systems and the new emerging technologies in the field of software development is continually increasing. Thus, education in this area faces a need of keeping up with these technologies. In order to deliver these new concepts, there is a need for
hardware infrastructure that leads to investment that in the majority of cases is not a viable
option for educational institutions. This project proposal attempts to build a low-cost solution for teaching and self-training with a small-scale model of a cloud, the PI Cloud.
The PI Cloud would consist of five raspberries PI interconnected through Ethernet ports to
create a cluster. Running Hypriot as an operating system which is a Debian-base distribution
for ARM processors that is optimised to run Docker and, Kubernetes as container scheduler. We believe that PI cloud would provide the perfect environment where students can gain experience in the leading technologies on the cloud.

## Goals of the project

* The implementation of the PI cloud as small cloud environment for educational propose
* Learn new demanding technologies; we aim with this project deepen learning related
to new technologies not used during the College term. Integrating this tools can be
challenging but also an eye-opening experience for students and considering it as a
future unexploited career path
* Knowledge, Educational achievement can make students, professionals and future em-
ployees more valuable for employers
* Implement it as a teaching tool, after completing the project and the tangible experience
of a cloud computing system; we hope to prove that building a small-scale model of a
cloud infrastructure can be an amazing educational experience for IT students. This will
help students to understand the underlying and intangible concepts of Cloud Computing
in into a real tangible learning environment

## Resource Requirements

This project is implementing a cluster with five nodes

Description                     | Quantity
:---                             | :---:
USB power hub 5 ports           |     1
Stocking plate for Raspberry Pi |     5
Brass Hex Head screw Kitbox     |     1
USB male to Micro USB           |     5
Ethernet Switch                 |     1
Raspberry PI 3 model B          |     5
Internet Cable 5 metre          |     1
Micro SD card                   |     5


![I and My friends]({{site.baseurl}}/assets/img/cluster_cartoon.png)
