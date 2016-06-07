# Ruby Study

The purpose of this study is to get you acquainted with Ruby as a programming
language.

## Required Activities

-   [Try Ruby](http://tryruby.org/)
-   [Ruby in Twenty Minutes](https://www.ruby-lang.org/en/documentation/quickstart/)

## Suggested Activities

-   [Poignant Guide](http://poignant.guide/)
-   [Code School: Ruby](https://www.codeschool.com/learn/ruby) (Ruby Bits 1 and 2).

## Ruby

Please write the code that would take the following integer `007` and return the
string `"700"`

```ruby

007.to_s.reverse

```

Please write the code that takes the following array `[23,56,3,7]` sorts it
then reverses that array returning and modifying the reference to the original
array.

```ruby

[13, 56, 3, 7].sort

```

What does an exclamation point after a method usually signify?

```ruby

An exclamation point modifies the object permanently instead of making a
new copy.

```

How do you create a class in Ruby?

```ruby

By using the class keyword we can define a new class. For example:

class Greeter
end

The name should always be in initial capitals and you can terminate the class
by using the keyword end.

```

If I modify a class in Ruby will already created instances of that class have
the methods I added?

```ruby

Yes, it will.

For example:
class Greeter
attr_accessor :name
end

The class Greeter already contains defined methods. The example above shows how we're
altering the class by using attr_accessor, which adds two new methods.
When creating a new instance of the class not only do we have the two new methods,
but the class also has its previously methods.


```

Please give an example of iterating in Ruby?

```ruby

@names.each do |name|
        puts "Hello #{name}!"
      end

Assuming @names is a list of some kind, at each instance of the variable we're
passing the parameter name and putting it into the string.

```
