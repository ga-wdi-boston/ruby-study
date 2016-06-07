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
array = [23, 56, 3, 7]
array.sort!.reverse!
```

What does an exclamation point after a method usually signify?

```ruby
A dangerous method! The method will modify the reference it is called upon.
```

How do you create a class in Ruby?

```ruby
class <name>
  #instance variables
  def initialize(<variableName1>, <variableName2>)
    @<variableName1> = <variableName1>
    @<variableName2> = <variableName2>
  end
  #methods
  def <methodName>
    puts "<someText>"
  end
end
```

If I modify a class in Ruby will already created instances of that class have
the methods I added?

```ruby
Yes, they have access to them.
```

Please give an example of iterating in Ruby?

```ruby
array = [1, 2, 3, 4, 5]
array.each { |x| puts x }
```
