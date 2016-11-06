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
"700".reverse
```

Please write the code that takes the following array `[23,56,3,7]` sorts it
then reverses that array returning and modifying the refrence to the original
array.

```ruby
arr = [23,56,3,7]  makes the array
arr.sort!.reverse!   sorts and modifies in ascending order and then reverses it
[56,23,7,3]     changes array to this
arr.sort_by!{}      I'm stuck on this part.  I can reverse it again, but that's not what we want here.
                    how do I get the array to show b,a,b,a when b<a while reordering the indexes
                      to 2,1,4,3?  There must be a even/odd index method, but that's not exactly what we want either.  What we want is to reaarange the indexes during the first method, keeping
                      23=[1] 56=[2] 3=[3] and 7=[4], and then setting the array to [2],[1],[4],[3] in order to keep those values and then simply arrange again back to original array of [1],[2],[3],[4].  Is there a way to keep original indexes when modifying the array?
                      I've overlooked something and I'm moving on to the next question.


```

What does an exclamation point after a method usually signify?

```ruby
  That the method is actually changing(modifying) the array, not just displaying values.
```
How do you create a class in Ruby?

```ruby
Using ::
```

If I modify a class in Ruby will already created instances of that class have
the methods I added?

```ruby
Yes on master classes, no on Singleton classes (subclasses of a masterclass which allows
new methods to apply only to the intended class)
```

Please give an example of iterating in Ruby?

```ruby
a = [1,2,3,4]
a.inject {|acc,i| acc + i}     This will iterate through and return the value of
                                [i]+[i]+[i]+[i] etc etc depending on how many [i]
                                values you have and what you specify.
```
