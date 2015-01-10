---
layout: post
title: "t2-css-design"
date: 2015-01-09 16:50:48 -0600
comments: true
categories:
---

This was a very tough week for me, technically.  CSS positioning gave me a ton of trouble and I definitely experienced my first "rabbit hole" situation.  It was not fun.

Anyway, I'm going to explain the difference between margin, border, and padding in this week's technical blog.  I'll attach a helpful image below as well.  So here we go!

<!--more-->

Let's do this from the inside out.  First up: padding.  Padding is the area that surrounds the content inside of a box model in html.  For instance, if you have a div tag with some text centered inside of it, the padding is the area between the text (also referred to as content) and the outside (border) of the div.  You can adjust the padding in css with the padding-left, padding-right, etc., atrributes.  You can also change all of them in one line with like this: padding: 10px 20px 10px 20px. The values begin with the top and go clockwise around the box.

Next up is border. The border is the line that contains the content and padding.  You can call it in css using border:.  You can assign different widths and colors to it, or you can make it solid, dashed, 3D, etc.

The margin is the area that surrounds the border.  Essentially, the area bertween the border and other html boxes.  It works in css much the same as padding does.  You can call margin-left, et al., or you can call all four values in one line.  I hope this was a helpful explanation of padding, border, and margin.  Thanks so much for taking the time to read this!
