---
layout: post
title: Combine all asset files using command line
excerpt: "How to combine asset files using command line"
tags: [cli]
modified: 2016-04-04
comments: true
---
This simple bash command could save you if you doesnt have time to configure tool such as gulp, grunts or others, only works in *nix family OS (e.g linux, unix, mac osx)

~~~bash
cat jquery.min.js bootstrap.min.js custom.min.js > all.js
cat jquery.min.css bootstrap.min.css custom.min.css > all.css
~~~

now you can just load your asset files in html with

~~~html
<html>
<head>
<title>Your Title Page</title>
  <link rel="stylesheet" href="all.css">
</head>
<body>
  <!-- your body html -->
  <script src="all.js"></script>
<body>
</html>
~~~ 

Hope it helps. Have a great day!
