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
First guess would be:
007.to_s.reverse

But this returns "7" instead of "700."

("%03d" % 7).reverse
returns "700," but it feels like I'm not perfectly answering the question.

(Source: https://mallibone.wordpress.com/2011/03/10/ruby-print-number-with-leading-zeros/)

```

Please write the code that takes the following array `[23,56,3,7]` sorts it
then reverses that array returning and modifying the refrence to the original
array.

```ruby
  [23, 56, 3, 7].sort!.reverse
```

What does an exclamation point after a method usually signify?

```ruby
  Modify the data to which we're attaching the method (rather than a copy of that data).
```

How do you create a class in Ruby?

```ruby
  Use the keyword "class" followed by the (capitalized) name of the new class. 

  Ex:

  class Dinosaur
```

If I modify a class in Ruby will already created instances of that class have
the methods I added?

```ruby
  Yes. Modifying a class will modify all existing instances of that class.
```

Please give an example of iterating in Ruby?

```ruby
  comics.each do |name, url|
    link name, url
  end
```
