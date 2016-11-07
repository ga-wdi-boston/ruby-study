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
"700".reverse
```

Please write the code that takes the following array `[23,56,3,7]` sorts it
then reverses that array returning and modifying the refrence to the original
array.

```ruby
[23,56,3,7].sort.reverse!
```

What does an exclamation point after a method usually signify?

```ruby
  that the function mutates the original variable, rather than just using it in an operation
```
How do you create a class in Ruby?

```ruby
class Thing
  #somestuff
end

```

If I modify a class in Ruby will already created instances of that class have
the methods I added?

```ruby
  yes
```

Please give an example of iterating in Ruby?

```ruby
@names.each do |name|
  puts "Hello #{name}!"
end
```
