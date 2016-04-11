# Ruby Study

The purpose of this study is to get you aquanited with Ruby as a programming
language.

## Required Activities

-   [Try Ruby](http://tryruby.org/)
-   [Ruby in Twenty Minutes](https://www.ruby-lang.org/en/documentation/quickstart/)

## Suggested Activities

-[Poignant Guide](http://poignant.guide/)
-[Code School: Ruby](https://www.codeschool.com/learn/ruby) (Ruby Bits 1 and 2).

## Ruby

Please write the code that would take the following integer `007` and return the
string `"700"`

```ruby
700.to_s.reverse
```

Please write the code that takes the following array `[23,56,3,7]` sorts it
then reverses that array returning and modifying the refrence to the original
array.

```ruby
[23,56,3,7].reverse
```

What does an exclamation point after a method usually signify?

```ruby
Makes the method destructive in that it alters it completely from its orginal
value without leaving the original value intact.
```

How do you create a class in Ruby?

```ruby
Use the keyword 'class' with any particular 'name' with any corresponding
methods associated with it.
```

If I modify a class in Ruby will already created instances of that class have
the methods I added?

```ruby
yes, they will have the created instances you added if I am understanding your
question correctly.
```ß

Please give an example of iterating in Ruby?

```ruby
fruit.each do |orange, orange|
  fruit.gsub!(orange, red)

fruitstand.sort_by {|fruit| fruit[:color]}.each do |fruit|
    print "These fruits are sorted by color."
  end
end
```
