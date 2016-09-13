# Ruby Study

The purpose of this study is to get you aquanited with Ruby as a programming
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
  007.to_s.reverse is what I would think, but this returns '7'...
  '007'.to_s.reverse does return '700' but I dont think this is right either.
```

Please write the code that takes the following array `[23,56,3,7]` sorts it
then reverses that array returning and modifying the refrence to the original
array.

```ruby
  arr = [23,56,3,7]
  arr.sort!.reverse!
```

What does an exclamation point after a method usually signify?

```ruby
  That it will modify the original value in place
```

How do you create a class in Ruby?

```ruby
  class My_Class
    def initialize
    end
  end
```

If I modify a class in Ruby will already created instances of that class have
the methods I added?

```ruby
  Yes they will! Once you modify a class in Ruby, all instances (including those already created)
  will have access to the new methods

  class Dog
    def bark
      puts "Bark"
    end
  end

  d = Dog.new
  d.bark => "Bark"

  class Dog
    def two_bark
      puts "bark bark"
    end
  end

  d.two_bark => "bark bark"
```

Please give an example of iterating in Ruby?

```ruby
  array.each do |num|
    puts num
  end
```
