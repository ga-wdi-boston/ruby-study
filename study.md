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
str = '00%o' % 007.to_s
str.reverse
```

Please write the code that takes the following array `[23,56,3,7]` sorts it
then reverses that array returning and modifying the refrence to the original
array.

```ruby
array = [23,56,3,7]
array.sort!.reverse!
```

What does an exclamation point after a method usually signify?

```ruby
  # It modifies the element instead of modifying it and returning a new one
  #based on the modification.
```

How do you create a class in Ruby?

```ruby
  class Cat_Fail
    def initialize(name, epic_fail)
      @name = name
      @epic_fail = epic_fail
    end
  end
```

If I modify a class in Ruby will already created instances of that class have
the methods I added?

```ruby
  # Yes
```

Please give an example of iterating in Ruby?

```ruby
array = [5, 1, 4, 9, 0]
array.each { |x| puts x }
```
