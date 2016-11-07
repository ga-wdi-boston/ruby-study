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
x = 700
x.to_a.reverse

```

Please write the code that takes the following array `[23,56,3,7]` sorts it
then reverses that array returning and modifying the refrence to the original
array.

sorts the array for what? -KF

```ruby

a = [23, 56, 3, 7]
a.sort!
```

What does an exclamation point after a method usually signify?

```ruby
To modify the orignal array and set it equal to the return of the statement.
```

How do you create a class in Ruby?

```ruby
class Cat
  def initialize(breed, name)
    # Instance variables
    @breed = breed
    @name = name
  end

  def Meow
    puts 'Meow! Meow!'
  end

  def display
    puts "I am of #{@breed} breed and my name is #{@name}"
  end
end
```

If I modify a class in Ruby will already created instances of that class have
the methods I added?

```ruby
Yes already created instances will recieve methods added to classes.
```

Please give an example of iterating in Ruby?

```ruby
array = [2,4,6,8]
array.each do |i|
   puts i
end
```
