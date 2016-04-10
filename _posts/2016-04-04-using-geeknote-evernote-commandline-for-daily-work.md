---
layout: post
title: Using geeknote (evernote in command line) for daily work
excerpt: "evernote is extravagant but powerfull. how you deal with it"
tags: [cli]
modified: 2016-04-04
comments: true
---
Some people, are very moody, so do I :p . I usually note todo list, what i should do on that day. Evernote is very good because its multiplatform,
Usually I write on my iphone, but then edit it on my macbook, windows, android or linux.   
<br> 
Unfortunately evernote is very extravagant in using your RAM / memory, 
often after i launch my evernote then my operating system get laggy. Until i found geeknote, i always note my todo list with command line.

~~~bash
$geeknote login
You have already logged in.
$geeknote settings --editor vim
$geeknote create --title "Sample text" --notebook "work" --tags "todolist, project, idea"
$geeknote find
Search request: intitle:*
Total found: 2
  1 : 18.01.1970        Sample text
  2 : 18.01.1970        30 maret 2016
$geeknote edit 1
$geeknote show 1
################## TITLE ##################
EOI Oz form
=================== META ==================
Created: 18.01.1970
Updated: 18.01.1970
----------------- CONTENT -----------------
this is just a sample text
$geeknote notebook-list
Total found: 1
  1 : work
$geeknote logout
~~~

just ignore the 1970 year that showed above, I think it's bug in geeknote or maybe because i never filled the date :p (lazy, me) .
<br>
for geeknote installation you can check on their [github](https://github.com/VitaliyRodnenko/geeknote) or [website](http://geeknote.me)  
<br>
**TL;DR**
The most usable geeknote commands are: 

+  create --title "your title" --notebook "work" = create post named it _"you title"_ and stored it to _"work"_ notebook
+  find = show all post with id, if you dont include the other arguments
+  edit \<id\> = edit post number \<id\>

<br>
Hope it helps. Have a great day!
