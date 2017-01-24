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
# Ruby's Integer class does not store leading zeros, so '007' is already an impossible thing for Ruby to store as an integer.  However, if you want to take the string '007' and return the string "700" you would use the following code

  007.reverse
```

Please write the code that takes the following array `[23,56,3,7]` sorts it
then reverses that array returning and modifying the refrence to the original
array.

```ruby
[23,56,3,7].sort.reverse!
```

What does an exclamation point after a method usually signify?

```ruby
store the change that was just made into the original variable calling the action that caused the change.
```
How do you create a class in Ruby?

```ruby
# create a new class Foo
class Foo
end
```

If I modify a class in Ruby will already created instances of that class have
the methods I added?

```ruby
  # Yes.  This is part of the beauty of OOP.
```

Please give an example of iterating in Ruby?

```ruby
  #  this will iterate from 1 to 10 and print each number along the way
  1.upto(10) do |i|
    p if
  end
```
