## Demo Super Lesson

## Objectives

1. Present valid readme syntax.
2. Include examples of all possible lesson readme elements.
3. Do some other crazy lesson stuff, edit 2

## Overview

Below are examples of elements that could appear in any **Learn lesson README**.

## Instructions

* Do stuff
* Make tests pass
* Emphasize stuff with _italics_
* Pay attention to `code snippets`

### Example 1: Quiz

Check out this sweet quiz below.

???

# Quiz title

?: Question with one correct answer

( ) Answer 1
( )
```ruby
def answer_two
  puts 'incorrect'
end
```
(X) Answer 3

?: Question with multiple correct answers

[X] Correct answer
[X]
```ruby
def correct_answer
  puts 'correct answer'
end
```
[ ] Incorrect answer

???

### Example 2: Repl (Code Challenge)

Code challenges - also known as repls - are super kewl.

%%%

### Code challenge title

Write a method that reverses a string, and call it, passing "12345" as an argument.

~~~ruby

def my_reverse(string)
  # Code your solution here
end

~~~solution

def my_reverse(string)
  string.reverse
end

my_reverse("12345")

~~~validation

assert_equal(response, "54321")
assert_length(response, 5)

~~~

%%%

### Example 3: Combinations

This section includes the following examples:

1. Video
2. Image
3. Code block
4. Blockquote
5. Table
6. Lists

Video (`iframe`) with download link.

<iframe width="1280" height="720" src="https://www.youtube.com/embed/uxANgIcjmQg?rel=0&amp;showinfo=0&html5=1" frameborder="0" allowfullscreen></iframe>

[Download Video](http://flatiron-videos.s3.amazonaws.com/ironboard/welcome%20to%20the%20shell.mp4)

Ok, now `/giphy` me.

![catz](https://after-school-assets.s3.amazonaws.com/cat.gif "CATZ")

Paragraph. [Lorem ipsum](http://www.lipsum.com/) dolor sit amet, consectetur adipiscing elit. Ut nec metus quam. Integer luctus accumsan ante, et auctor sapien placerat in. Donec eget nunc a mauris sagittis posuere at ut velit. Nam sollicitudin rhoncus lacus non hendrerit. Duis semper quis turpis ac ultrices. Integer nec faucibus tortor, eu malesuada leo. Aenean imperdiet erat vel efficitur ullamcorper.

Another paragraph. Nunc eleifend sodales pellentesque. [Suspendisse tortor nibh](#not-a-real-link), sollicitudin eget hendrerit facilisis, tristique id odio. Phasellus erat lectus, tempus sit amet blandit id, sollicitudin eget purus. Donec vel iaculis enim, feugiat porta ligula. Vivamus tincidunt odio in ante scelerisque, vitae placerat felis cursus.

Next up is a code block.

```javascript
var fizzbuzz = function (num) {
  if (num % 15 === 0) {
    return 'FizzBuzz';
  } else if (num % 3 === 0) {
    return 'Fizz';
  } else if (num % 5 === 0) {
    return 'Buzz';
  } else {
    return num;
  }
};
```

Inspiring quote [[source](#not-really)]:

> Lorem ipsum dolor sit amet, consectetur adipiscing elit.
> Ut nec metus quam. Integer luctus accumsan ante, et auctor sapien placerat in.
> Donec eget nunc a mauris sagittis posuere at ut velit.

Let's throw another [link](#nowhere) in here.

| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| Lorem ipsum   | dolor sit     | $1000 |
| amet          | consectetuer  |  $200 |
| adipiscing    | elit.         |   $30 |

<a href='https://learn.co/lessons/demo-super-lesson' data-visibility='hidden'>View this lesson on Learn.co</a>

<p class='util--hide'>View <a href='https://learn.co/lessons/demo-super-lesson'>demo super lesson</a> on Learn.co and start learning to code for free.</p>
