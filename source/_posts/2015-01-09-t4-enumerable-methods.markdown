---
layout: post
title: "t4-enumerable-methods"
date: 2015-01-09 17:01:35 -0600
comments: true
categories:
---

Just finished week 4 at Dev Bootcamp!  We did a lot of work with Ruby's public methods this week.  I used plenty of methods like .each,.each_slice,.count,.to_s,.to_a, etc., and will be explaining the Enumerable#map method to you in the following blog.

The map method is a method that can be very useful to rubyists in many ways.  What map does, is take and array, run the block given for every element of the array, and return a new array with new elments.  For instance, if I had the array [1,2,3,4], and I ran .map at the end of it like this: [1,2,3,4].map {|bango| bango + 1}, the new array would look like this: [2,3,4,5].  The map method iterated over every element of our original array, stored those elements in the variable "bango" and ran the block of code {bango + 1} for each.  It stores it's results in the corresponding indices of the new array.  Very useful!

So that's how the map method works.  Cool, right?  I should probably state here that Ruby has another method which does, literally, the same exact thing.  The name of this synonym method is #collect.  Ruby has these synonyms built in for easier use or transition from other languages.

I hope this explanation of #map was useful.  Thanks for taking the time to read this!
