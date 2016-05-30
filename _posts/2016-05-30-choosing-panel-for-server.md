---
layout: post
title: Diagram you should create with rails, lazy mode on
excerpt: "The Ideal Programmer vs Lazy Mode Programmers"
tags: [cli,diagram,rails,vim]
modified: 2016-04-04
comments: true
---

Try using PlantUml gem, as an ideal programmer(design it firstly). I dont really know how to use it in sublime text. But many times I used it in vim editor,
yeah there is plugin for it, just search it on [vimawesome.com](http://vimawesome.com). Why to use this plugin / gem ? just admit it, a lot time
developer confuse in design the diagram like uml or erd for business process for the first time building app, so they dont want to confuse about 
arrange line, box order / place. PlantUml especially in vim, is easy to create, you just type it and the diagram will create itself as image file.
<br>
<br> 
Try using Railroady, as lazy programmers ( design it later, most of us :p ). yes just simply just create database anytime, anywhere, using scaffold or maybe migration file, you name it :) . 
After it migrated to database, and schema also created automatically. Run the railroady in commandline. then the lovely image will created automatically.
Attention! when using great numbers of table it may suck up your memory usage and create monster-size of image file, please use Imagemagick / convert commmand-line to reduce size before previewing your image directly from your desktop.
