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
700.to_s.reverse // converts the integer 700 to string and then reverses the
string "700" to "007".
```

Please write the code that takes the following array `[23,56,3,7]` sorts it
then reverses that array returning and modifying the refrence to the original
array.

```ruby
  arr = [23,56,3,7]
  arr.sort         // sorts the array. [3,7,23,56]
  arr.reverse!     // reverses the array and modifies it permanenty. [56,23,7,3]
  arr              // now arr becomes [56,23,7,3]
```

What does an exclamation point after a method usually signify?

```ruby
  '!' after a method indicates that the method will modify the object it is
  called on.
```
How do you create a class in Ruby?

```ruby
  using keyword class followed by the name of the class. The class ends using
  the keyword end.

  class ClassName


  end
```

If I modify a class in Ruby will already created instances of that class have
the methods I added?

```ruby
  Yes, changes to a class in ruby will reflect in new objects as well as
  existing objects of that calss.
```

Please give an example of iterating in Ruby?

```ruby
Ruby uses 'each' method to loop through a block of code.

Eg -
[23,56,7,3].each do |i|
  puts i
end

prints out
23
56
7
3
=> [23,56,7,3]
```
