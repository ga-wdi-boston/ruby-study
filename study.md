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

007.to_s.rjust(3, '0').reverse
=> "700"

```

Please write the code that takes the following array `[23,56,3,7]` sorts it
then reverses that array returning and modifying the refrence to the original
array.

```ruby
arr = [23,56,3,7]
=> [23,56,3,7]
arr.sort!
=> [3, 7, 23, 56]
array.reverse
=> [56, 23, 7, 3]
```

What does an exclamation point after a method usually signify?

```ruby
It impacts current data rather than making a copy of object that has method attached to it.
```

How do you create a class in Ruby?

```ruby
class <name of the class>
   def <name of the method>
      statement 1
      statement 2
   end
end
```

If I modify a class in Ruby will already created instances of that class have
the methods I added?

```ruby
Yes. The changes will be available in existing objects of the same class after the class was modified.
```

Please give an example of iterating in Ruby?

```ruby
@names.each do |name|
  puts "Hello #{name}!"
end

Each method will iterate through every element in a list, and will run the block of code between do and end. Block of code that will each method run will print out "Hello" and add variable name to it for each iteration. Command puts will print out the message and add a new line for each execution of the code.
```
