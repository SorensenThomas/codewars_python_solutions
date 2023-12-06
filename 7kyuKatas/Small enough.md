## No Loops 2 - You only need one
### No Loops Allowed

[Problem in CodeWars.com](https://www.codewars.com/kata/no-loops-1-small-enough)

You will be given an array (a) and a limit value (limit). You must check that all values in the array are below or equal to the limit value. If they are, return True. Else, return False.

You can assume all values in the array are numbers.

Do not use loops. Do not modify input array.

### Given Code

```python
def small_enough(a, limit):
    # your code here
    pass
```

### Solution

```python
def small_enough(a, limit): 
    return max(a) <= limit
```

