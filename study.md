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
700.to_s.reverse

Used first lesson for this response.
```

## Array Manipulation

Write the Ruby code that takes the following array, `[23, 56, 3, 7]`, and
manipulates it by sorting it and then reversing it in place (i.e., modifying the
reference to the original).

```ruby
# your answer here
```

## Class#method!

What does an exclamation point after a method usually signify?  e.g.,
`my_string.capitalize!`

```md
The exclamation point signifies that we want to modify that existing string rather than create a new copy of it to modify.

Also from first lesson.
```

## Instantiation
How do you create an instance of a class in Ruby?

```ruby
class ClassName
  def initialize(parameters)
    @something = something
    @otherThing = otherThing
  end

then:

ClassName.new('Whatever', 'iWrote')

Second lesson: Ruby in 20 minutes
```

## Class Modification

If a class in Ruby gets modified while there are existing instances of it, then
will those instances also have those modifications?

```md
Yes, you will be able to access the changes in new or existing classes
```

## Iteration

Write an example of iteration in Ruby.

```ruby
@names.each do |name|
  puts "Hello #{name}!"
end
  this came from the second reading/lesson
```
