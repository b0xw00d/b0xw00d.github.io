---
layout: post
title: "t7-JavaScript"
date: 2015-01-17 07:54:20 -0600
comments: true
categories: 
---
This week we learned all about Javascript at Dev Bootcamp.  It was definitely a change of pace from the previous four weeks.  After learning the basics of both languages, I can see a ton of similarities and a ton of differences as well.  The following post will highlight the differences between Javascript objects and Ruby hashes.

<!--more-->

I'll start by showing examples of each of these variable types in both languages.  Below is a basic object variable in Javascript.

```javascript
//basic object variable in JS

var bango = {
	name: "Bango",
	breed: "Shiba",
	weight: "feather"
};

```
Here I have an object named bango.  In this object there are 3 properties that come in the form of key-value pairs.  The key name: holds the value "Bango," the key breed holds the value "Shiba."  Now compare that with a hash in Ruby, which is created like this:

```ruby
#basic hash in Ruby

bango = {name: "Bango", breed: "Shiba", weight: "feather"}

```

Aside from the var keyword in front of the Javascript object, these two examples look almost identical.  The difference come when you start to add functions to these things.  Look what I can do inside a JS object:

```javascript
//basic method in JS object

var bango = {
		name: "Bango",
		breed: "Shiba",
		weight: "feather",
		beCute: function(){
		console.log(chirp.chirp.chirp.);
		}
	}

```
Notice how I can put a function inside of this object?  That can't be done with a Ruby hash.  This actually reminds me more of a Class in Ruby.  In order to do this in Ruby it would look something like this:

```ruby
#basic Class in ruby

class Bango

	def initialize
		@name = "Bango"
		@breed = "Shiba"
		@weight = "feather"
	end

	def be_cute
		puts "chirp.chirp.chirp."
	end

end

```

I hope this was helpful.  I only touched on this topic briefly.  There's a lot more you can do with hashes, object, and classes that I don't have time to cover here.  If you're interested in learning more I suggest to look up the documentation in both languages.












