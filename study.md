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
  numbers = [23, 56, 3, 7]

  numbers.sort.reverse
```

What does an exclamation point after a method usually signify?

```tx

  Rather than just making a new copy of something, the exclamation makes
  a permanent change to something.
```

How do you create a class in Ruby?

```tx
class <class name>

Example:
class poop
```

If I modify a class in Ruby will already created instances of that class have
the methods I added?

```tx
  Yes, the changes will be present in any new objects created.
```

Please give an example of iterating in Ruby?

```tx
.each is an example of iterating in Ruby.  Much like a for loop, it will go over every element in an array and return those elements.
```
