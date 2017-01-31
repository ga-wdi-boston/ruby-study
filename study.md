# Ruby Study

Use your favorite search engine and the provided readings to research and
respond to the following questions.

In your responses, be sure to cite any relevant sources you consulted in your
search. We ask you to write responses in your own words in order to see how you
process what you've read. Please do not respond with direct quotes from source
material. Instead, digest what you've read and repeat it in your own voice.

## Required Readings

-   [Try Ruby](http://tryruby.org/)
-   [Ruby in Twenty Minutes](https://www.ruby-lang.org/en/documentation/quickstart/)
-   [Poignant Guide](http://poignant.guide/)
-   [Code School: Ruby](https://www.codeschool.com/learn/ruby) (Ruby Bits 1 and 2).
-   [% Notation](https://en.wikibooks.org/wiki/Ruby_Programming/Syntax/Literals#The_.25_Notation)

## Type Conversion

Write the Ruby code that takes the integer `700` and returns the string `"007"`.

```ruby
let num = "700"
num.to_s
num.reverse
```

## Array Manipulation

Write the Ruby code that takes the following array, `[23, 56, 3, 7]`, and
manipulates it by sorting it and then reversing it in place (i.e., modifying the
reference to the original).

```ruby

arr  = [23, 56, 3, 7]
elements = []

for number in arr
  if number > (number + 1 )
    elements.push(number)
  end
end

```

## Class#method!

What does an exclamation point after a method usually signify?  e.g.,
`my_string.capitalize!`

```md
The exclamation point indicates that the method will change the object which it's called on.  In the situation above, it indicates that it will modify "my_string"
```

## Instantiation
How do you create an instance of a class in Ruby?

```ruby
class Home
  def initialize(rooms, bathrooms, sqFt)
    #Instances
    @rooms = rooms
    @bathrooms = bathrooms
    @sqFt = sqFt
  end
end
```

## Class Modification

If a class in Ruby gets modified while there are existing instances of it, then
will those instances also have those modifications?

```md
If a class in Ruby gets modified, previous instances will be impacted.
```

## Iteration

Write an example of iteration in Ruby.

```ruby
for i in 0..5
  print "#{i} "
end
```
