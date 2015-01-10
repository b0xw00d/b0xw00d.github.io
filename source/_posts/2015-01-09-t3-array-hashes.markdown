---
layout: post
title: "t3-array-hashes"
date: 2015-01-09 16:57:14 -0600
comments: true
categories:
---

This week at DBC we started the section on Ruby!  A lot of this week's material was review for me but I still learned a bunch and I definitely sharpened my skills a bit in the process.  I'm going to write this blog about hashes and arrays.  Hopefully some of you find it useful!

<!--more-->

Let's start by describing arrays.  An array is a list of elements that are grouped together and presented in an ordered list.  Every element in an array is representative of a single object.  These can be strings, numbers, variables -- any object.  The Array class in ruby come with a ton of predefined methods which can be called on arrays to manipulate these elements.  Arrays are extremely useful for sorting and arranging large amounts of data quickly.

Arrays are created just like any other variable except that they accept a list of elements contained by brackets like so: my_array = [2,22,222];.  As I stated earlier, there are plenty of other ways to initialize and define an array.  I won't get into all of them here.

Now for hashes.  Hashes are very similar to arrays with one major difference and some smaller ones as well.  In an array every element corresponds to one specific value -- not the case for hashes.  Every elment in a hash is a key-value pair.  Meaning you can have a with 10 different keys name "dog" that all hold a different value; names of dogs, breeds, dogs in the family, etc.  This is especially useful for sorting and organizing information.

Hashes, like arrays, have plenty of ways of being intitialized.  I'll show you the syntax which, in my opinion, is easiest to read here: pets = {"dog": "rat terrier", "dog": "shiba inu", "cat": "himalayan"};.  Here, the hash named pets has two "keys" -- dog and cat.  The values paired with these keys are different breeds.

You can see how organizing information in this way can be especially useful when coding web apps.  The use of both arrays and hashes allows the programmer a ton of felxibility and organization.  Warning: this can get really confusing, realy fast, and there is a ton to learn about both of these Classes in Ruby.  I've barely scratched the surface here but I hope this has served as a useful primer on the subject.  Thanks for taking the time to read this!
