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
ticket = [23, 56, 3, 7]


ticket.sort

ticket.reverse
```

What does an exclamation point after a method usually signify?

```ruby
not, opposite of whatever it is next to
```

How do you create a class in Ruby?

```ruby
class Test
end

If I modify a class in Ruby will already created instances of that class have
the methods I added?

```ruby
Yes both future and past instances of that class will be updated to reflect that
change.
```

Please give an example of iterating in Ruby?

```ruby
@names.each do |name|
  puts "Hello #{name}!"
end
```
