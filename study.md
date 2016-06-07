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
  007.to_s.reverse.
```

Please write the code that takes the following array `[23,56,3,7]` sorts it
then reverses that array returning and modifying the refrence to the original
array.

```ruby
[23,56,3,7].sort.reverse!
```

What does an exclamation point after a method usually signify?

```ruby
! means to store the modified the original variable/array and store it back to that original variable/array name
```

How do you create a class in Ruby?

```ruby
  class InsertNameOfClass
    def content blah blah
      @example instance of the variable example
      def function_1
        put functions
      end
      def function2
        put stuff
      end
    end
```

If I modify a class in Ruby will already created instances of that class have
the methods I added?

```ruby
  yes.
  InsertNameOfClass.instance_methods
    gives all the instances
  Greeter.instance_methods(false)
    does not return methods defined by ancestors
```

Please give an example of iterating in Ruby?

```ruby
  .each
    is equivalent
    to a for loop like for (i=0; i<number_of_elements; i++)
{
  do_something_with(element[i]);
}
```
