# Ruby Study

Use your favorite search engine and the provided readings to research and
respond to the following questions.

In your responses, be sure to cite any relevant sources you consulted in your
search. We ask you to write responses in your own words in order to see how you
process what you've read. Please do not respond with direct quotes from source
material. Instead, digest what you've read and repeat it in your own voice.

## Required Readings

-   [Ruby Tutorial - Try Ruby](http://tryruby.org/)
-   [Ruby in Twenty Minutes](https://www.ruby-lang.org/en/documentation/quickstart/)
-   Code School (Only the free levels. **Do not pay for Code School unless you want to.**
    -   [Ruby Bits](https://www.codeschool.com/courses/ruby-bits)
    -   [Ruby Bits Part 2](https://www.codeschool.com/courses/ruby-bits-part-2)
-   [% Notation](https://en.wikibooks.org/wiki/Ruby_Programming/Syntax/Literals#The_.25_Notation)

## Additional Resources: Optional

-   [RubyMonk - Interactive Ruby tutorials](https://rubymonk.com/)
-   [Why's (Poignant) Guide to Ruby](http://poignant.guide/)
-   [Learn Ruby - With the Edge Case Ruby Koans](http://rubykoans.com/)

## Type Conversion

Write the Ruby code that takes the integer `700` and returns the string `"007"`.

```ruby
# 700.to_s.reverse
```

## Array Manipulation

Write the Ruby code that takes the following array, `[23, 56, 3, 7]`, and
manipulates it by sorting it and then reversing it in place (i.e., modifying the
reference to the original).

```ruby
# test = [23, 56, 3, 7]
#=> [23, 56, 3, 7]
# [2] pry(main)> test
# => [23, 56, 3, 7]
# [3] pry(main)> test.sort!
# => [3, 7, 23, 56]
# [4] pry(main)> test.reverse
# => [56, 23, 7, 3]
```

## Class#method!

What does an exclamation point after a method usually signify?  e.g.,
`my_string.capitalize!`

```md
<!-- It means to save the variable values with the method that was applied to it. For instance if I use .sort in a variable without the exclamation point it sorts the data; and when I call the variable it will show in its original form (not sorted). Using ! in sort will save the variable with its values sorted and when called the variable will have same data but sorted.  -->
```

## Instantiation
How do you create an instance of a class in Ruby?

```ruby
# With @- That means that variable with @ will be available in all the methods defined in one class.
```

## Class Modification

If a class in Ruby gets modified while there are existing instances of it, then
will those instances also have those modifications?

```md
<!-- Yes, once is modified all elements within the class will be changed.-->
```

## Iteration

Write an example of iteration in Ruby.

```ruby
# @games.each do |score|
      #puts "This is your score today, #{score}!"
```
