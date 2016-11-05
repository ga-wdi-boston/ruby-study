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
700.to_s
```

Please write the code that takes the following array `[23,56,3,7]` sorts it
then reverses that array returning and modifying the refrence to the original
array.

```ruby
[23,56,3,7].sort.reverse  # your answer here
```

What does an exclamation point after a method usually signify?

```ruby
It means that you are making a permanent change to an array and not simply
copying it with the change or modification method being applied.
```
How do you create a class in Ruby?

```ruby
class Name
  (name being the name of the class being created)
```

If I modify a class in Ruby will already created instances of that class have
the methods I added?

```ruby
Yes
```

Please give an example of iterating in Ruby?

```ruby
superheroes = ['Daredevil', 'Superman', 'Hulk', 'Spider-Man']
superheroes.each do |superhero|
  puts "My favorite hero is: #{superhero}"
end
```
