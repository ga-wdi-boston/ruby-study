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
700.to_s
```

[Poignant Guide](http://poignant.guide/book/chapter-3.html)

## Array Manipulation

Write the Ruby code that takes the following array, `[23, 56, 3, 7]`, and
manipulates it by sorting it and then reversing it in place (i.e., modifying the
reference to the original).

```ruby
[23, 56, 3, 7].sort.reverse
```

[Ruby Docs](http://ruby-doc.org/core-2.3.1/Array.html)

## Class#method!

What does an exclamation point after a method usually signify?  e.g.,
`my_string.capitalize!`

```md
A bang at the end of a method name usually signifies that it will permantly alter the object it's called on.
```

[Stack Overflow](http://stackoverflow.com/questions/612189/why-are-exclamation-marks-used-in-ruby-methods)

## Instantiation
How do you create an instance of a class in Ruby?

```ruby
Class.new
```

[Ruby Docs](http://ruby-doc.org/core-2.3.1/Class.html)

## Class Modification

If a class in Ruby gets modified while there are existing instances of it, then
will those instances also have those modifications?

```md
Yes. The existing instances of the class will also be updated.
```

I used `irb` to test this myself.

```ruby
irb(main):032:0> class Stuff
irb(main):033:1>  def do_math(x,y)
irb(main):034:2>    x * y
irb(main):035:2>  end
irb(main):036:1> end
=> :do_math
irb(main):037:0> my_stuff = Stuff.new
=> #<Stuff:0x007f81500300d8>
irb(main):038:0> my_stuff.do_math(3,5)
=> 15
irb(main):039:0> class Stuff
irb(main):040:1>  def do_math(x,y)
irb(main):041:2>    x + y
irb(main):042:2>  end
irb(main):043:1> end
=> :do_math
irb(main):044:0> my_stuff.do_math(3,5)
=> 8
```

## Iteration

Write an example of iteration in Ruby.

```ruby
[1,2,3,4].each do |num|
  num + 5
end
```

[Poignant Guide](http://poignant.guide/book/chapter-3.html)
