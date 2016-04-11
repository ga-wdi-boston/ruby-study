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
# This just returns "7"... not sure how to store leading zeros in integers.
```

Please write the code that takes the following array `[23,56,3,7]` sorts it
then reverses that array returning and modifying the refrence to the original
array.

```ruby
[23,56,3,7].sort.reverse!
```

What does an exclamation point after a method usually signify?

```ruby
# The exclamation point indicates that the method will modify the object its called on.
```

How do you create a class in Ruby?

```ruby
class example
  # methods for this class are defined in here
end
```

If I modify a class in Ruby will already created instances of that class have
the methods I added?

```ruby
# Yes, the changes will be present in any new objects you create and available in existing objects of that class.
```

Please give an example of iterating in Ruby?

```ruby
books.values.each { |rate| ratings[rate] += 1 }
# iterates through the hash called books, adds the value of each key to another hash called ratings, counting how many times each key was in the books hash and assigning the count as the value in the ratings hash.
```
