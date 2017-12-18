---
layout: post
title: Classifying Music Genres via Lyrics using a Hierarchical Attention Network
description: >
tags: []
author: author
---

As part of [CS224N](http://web.stanford.edu/class/cs224n/) here at [Stanford](https://www.stanford.edu/) I began learning about the various uses of deep learning in natural language processing. As part of this course, I decided to begin a project to try and classify music genre using lyrics only which has typically been a tough problem in the music information retrieval (MIR) field. 

To begin the project I took inspiration from [the paper by Yang et al.](http://www.aclweb.org/anthology/N16-1174) using a Hierachical Attention Network (HAN) to classify documents. Similarly to documents, lyrics contain a hierachical structure: words go into lines, lines into sections (verse/chorus/...), and sections then form the whole song. Further, from the attention mechanism we can then extract and visualise where the network is applying its weights.

The structure of the network can be seen for the example song of 'Happy Birthday' below.
![HAN Architecture](/assets/img/lyricsHAN/network_image.pdf)
<!--![HAN Architecture]({{"/assets/img/lyricsHAN/network_image.pdf"}})-->

All the code is avalable [here](https://github.com/alexTsaptsinos/lyricsHAN), although I apologise in advance for not being formatted very cleanly.

You can read the full paper [here](https://alextsaptsinos.github.io/papers/lyricspaper.pdf).
