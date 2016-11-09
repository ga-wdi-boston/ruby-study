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

Please write the code that would take the following integer `700` and return the
string `"007"`

```ruby
#  700.to_s.reverse
```

Please write the code that takes the following array `[23,56,3,7]` sorts it
then reverses that array returning and modifying the refrence to the original
array.

```ruby
#  [23,56,3,7].sort!.reverse!
```

What does an exclamation point after a method usually signify?

```ruby
#  It tells ruby that we want to directly modify the original data with method we're using instead of creating a copy of the data with the method applied.
```
How do you create a class in Ruby?

```ruby

  class Greeter
    def initialize(name = "Matt")
      @name = name
    end
    def say_hi
      puts "Hi #{@name}"
    end
  end

```

If I modify a class in Ruby will already created instances of that class have
the methods I added?

```ruby
  # Yes, we are able to 'open' a class up and modify it. These changes will be present in any new object that we create and will be available in existing objects of that class.
```

Please give an example of iterating in Ruby?

```ruby

class Greeter
  attr_accessor :names

  def initialize(names = "World")
    @names = names
  end

  def say_hi
    if @name.nil?
      puts "..."
    elsif @name.respond_to?("each")
      @names.each do |name|  # Pretty sure this is exactly where the iterating is happening.
        puts "Hello #{name}"
      end
    else
        puts "Hello #{@names}"
    end


```
