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
007.to_s.reverse
```

Please write the code that takes the following array `[23,56,3,7]` sorts it
then reverses that array returning and modifying the refrence to the original
array.

```ruby
[23,56,3,7].sort!.reverse!
```

What does an exclamation point after a method usually signify?

```md
That the method will alter the current data it is working on rather than make
a copy.
```

How do you create a class in Ruby?

```md
You create a class by defining a class name, putting functions within in with
indentation and end statements. And closing with an end statement. Like so:
```

```ruby
class Greeter
  def initialize(name = "World")
    @name = name
  end
  def say_hi
    puts "Hi #{@name}!"
  end
  def say_bye
    puts "Bye #{@name}, come back soon."
  end
end
```

If I modify a class in Ruby will already created instances of that class have
the methods I added?

```md
No.
```

Please give an example of iterating in Ruby?

```ruby
@names.each do |name|
  puts "Hello #{name}!"
end
```
