### Description:

### A square of squares

You like building blocks. You especially like building blocks that are squares. And what you even like more, is to arrange them into a square of square building blocks!

However, sometimes, you can't arrange them into a square. Instead, you end up with an ordinary rectangle! Those blasted things! If you just had a way to know, whether you're currently working in vain… Wait! That's it! You just have to check if your number of building blocks is a _perfect square_.

### Task

Given an integral number, determine if it's a [square number](https://en.wikipedia.org/wiki/Square_number):

> In mathematics, a **square number** or **perfect square** is an integer that is the square of an integer; in other words, it is the product of some integer with itself.

The tests will _always_ use some integral number, so don't worry about that in dynamic typed languages.

### Examples

```
-1  =&gt;  false
 0  =&gt;  true
 3  =&gt;  false
 4  =&gt;  true
25  =&gt;  true
26  =&gt;  false
```


### Given Code

```python
def is_square(n):    
    return False # fix me
```

### Solution

```python
def is_square(n):
    return n > -1 and (int(n ** 0.5) ** 2 == n)
```
