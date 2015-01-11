---
layout: post
title: "t6-oop-concepts"
date: 2015-01-11 11:39:39 -0600
comments: true
categories:
---
Class methods are a super important part of the Ruby programming language.  They allow users to call a method on a class directly as opposed to an instance class which requires a new instance to be called.  I illustrate this with code below:

```ruby
#defining a class method

class Foo
  def self.bar
    "This is a class method"
  end
end

Foo.bar   #=> This is a class method.


#defining an instance method

class Foo
  def bar
    "This is an instance method."
  end
end

baz = Foo.new
baz.bar #=> This is an instance method.
```
<!--more-->

> Notice in the code above that we needed to create a new instance of the class Foo to call the instance method > bar.  In the first example, this wasn't necessary because we defined .bar as a class method.

It should be noted that this is not the only way to create instance or class methods in Ruby.  There are 3 ways to create each.  I only included the syntax I prefer here for the sake of brevity.  Both types of method are extremely useful and learning to use both is an essential part of mastering the core concepts of Ruby.  Thanks for taking the time to read this!