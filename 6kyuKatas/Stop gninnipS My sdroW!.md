### Description:

Write a function that takes in a string of one or more words, and returns the same string, but with all five or more letter words reversed (Just like the name of this Kata). Strings passed in will consist of only letters and spaces. Spaces will be included only when more than one word is present.

Examples:

```
spinWords( "Hey fellow warriors" ) =&gt; returns "Hey wollef sroirraw" 
spinWords( "This is a test") =&gt; returns "This is a test" 
spinWords( "This is another test" )=&gt; returns "This is rehtona test"
```

### Given Code

```python
def spin_words(sentence):
    pass
```

### Solution

```python
def spin_words(sentence):
    words = sentence.split()
    spun_words = [word[::-1] if len(word) >= 5 else word for word in words]
    return " ".join(spun_words)

```
