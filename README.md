## Demo Super Lesson

## Objectives

1. Present valid readme syntax.
2. Include examples of all possible lesson readme elements.

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

### Example 3: Video

Video (`iframe`) with download link.

<iframe width="1280" height="720" src="https://www.youtube.com/embed/uxANgIcjmQg?rel=0&amp;showinfo=0&html5=1" frameborder="0" allowfullscreen></iframe>

[Download Video](http://flatiron-videos.s3.amazonaws.com/ironboard/welcome%20to%20the%20shell.mp4)

### Example 4: Image

![catz](https://after-school-assets.s3.amazonaws.com/cat.gif "CATZ")

### Example 5: Code block

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

### Example 6: Blockquote

> Lorem ipsum dolor sit amet, consectetuer adipiscing elit. 
> Aliquam hendrerit mi posuere lectus.
> Vestibulum enim wisi, viverra nec, fringilla in, laoreet vitae, risus.

### Example 7: Table

| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| Lorem ipsum   | dolor sit     | $1000 |
| amet          | consectetuer  |  $200 |
| adipiscing    | elit.         |   $30 |

<a href='https://learn.co/lessons/demo-super-lesson' data-visibility='hidden'>View this lesson on Learn.co</a>
