---
layout: post
title: "t6-oop-concepts"
date: 2015-01-11 11:39:39 -0600
comments: true
categories:
---
Class methods are a super important part of the Ruby programming language.  They allow users to call a method on an instance of a class directly (e.g. String#length).  Length is a class method contained in the String class of Ruby.  Therefore, .length can be called on any string and will return the number of characters in that string.

<!--more-->

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

> Notice in the code above that we needed to create a new instance of the class Foo to call the instance method > bar.  In the first example, this wasn't necessary because we defined .bar as a class method.

It should be noted that this is not the only way to create instance or class methods in Ruby.  There are 3 ways to create each.  I only included the syntax I prefer here for the sake of brevity.