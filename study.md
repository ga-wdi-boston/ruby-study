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
007.to_s.ljust(3, "0")
```

Please write the code that takes the following array `[23,56,3,7]` sorts it
then reverses that array returning and modifying the refrence to the original
array.

```ruby
test = [23, 56, 3, 7]

test.sort!.reverse!
```

What does an exclamation point after a method usually signify?

```ruby
It usually signifies that the method is a dangerous/destructive method, i.e.,
it modifies whatever it is acting upon. For an example, please refer to the
previous answer.
```

How do you create a class in Ruby?

```ruby
class Animal
  def initialize(sound)
    @sound = sound
  end
  def vocalize()
    puts "#{@sound}"
  end
end
```

If I modify a class in Ruby will already created instances of that class have
the methods I added?

```ruby
Yes.
```

Please give an example of iterating in Ruby?

```ruby
phrase = ["Hello", "World", "!"]

phrase.each do |word|
  puts word
end

phrase.each { |word| puts word }
```
