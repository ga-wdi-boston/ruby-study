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

## Additional Resources

-   [RubyMonk - Interactive Ruby tutorials](https://rubymonk.com/)
-   [Why's (Poignant) Guide to Ruby](http://poignant.guide/)

## Type Conversion

Write the Ruby code that takes the integer `700` and returns the string `"007"`.

```ruby
a = "700"
a.reverse!
puts a```

## Array Manipulation

Write the Ruby code that takes the following array, `[23, 56, 3, 7]`, and
manipulates it by sorting it and then reversing it in place (i.e., modifying the
reference to the original).

```ruby
a = [[23, 56, 3, 7]]
a.sort {a[1] <=> b[1] }
puts a```

## Class#method!

What does an exclamation point after a method usually signify?  e.g.,
`my_string.capitalize!`

```md
methods that end in ! indicate that the method will modify the object it's called on(my_string).
```

## Instantiation
How do you create an instance of a class in Ruby?

```ruby
Class Vehicle
{
}```

## Class Modification

If a class in Ruby gets modified while there are existing instances of it, then
will those instances also have those modifications?

```md
wasn't able to find the answer to this question.
```

## Iteration

Write an example of iteration in Ruby.

```ruby
ary = [1,2,3,4,5]
ary.each do |i|
   puts i
end
```
