### (1) Print the numbers from 1 to 10 separated by a space in one line and also print them in new lines.

```python
def print_horizontally():
    pass


def print_vertically():
    pass
```

### (2) Sort a list of integer lists with respect to the length of the inner lists.

Example:
```python
lst = [[1, 2, 4], [8], [7, 6], [], [3, 5, 9, 10]],
```
Expected output:
```python
[[3, 5, 9, 10], [1, 2, 4], [7, 6], [8], []]
```

```python
def sort_by_length(lst):
    pass
```

### (3) Flatten a list of lists containing integers.

Example:

```python
lst = [[1, 2, 4], [8], [7, 6], [], [3, 5, 9, 10]],
```
Expected output:
```python
[1, 2, 4, 8, 7, 6, 3, 5, 9, 10]
```

```python
def flatten(lst):
    pass
```

### (4) Implement random-sort
Given a list of integers, repeat the following two steps:
1. check if the array is sorted in O(n) time
2. permute the elements of the list randomly

```python
def random_sort(lst):
    pass
````

### (5) For a given string remove consecutive duplicate characters.
Example:
```python
s = "kukkkuuuurrrriiiikuuuuuuuu"
```

Expected output:
```python
"kukuriku"
```
```python
def deduplicate(string):
    pass
```

### (6) For a given $[a, b]$ interval ($a\leq b$) return the list of Fibonacci numbers contained in this interval.

The Fibonacci numbers are defined as follows:
$$
    f_0 = f_1 = 1, \qquad f_n = f_{n-1} + f_{n-2} \quad (n\geq 2)
$$

```python
def fibonacci_numbers_in_interval(a, b):
    pass
```

### (7) Return the 20 most frequent letters from the webpage https://en.wikipedia.org/wiki/Machine_learning

```python
def top_20_most_frequent_letters(url):
    pass
```

### (8) Implement complex number or rational number arithmetic using classes.

Represent them as an object, and define the usual algebraic operations.

Example:
```python
z = ComplexNumber(1, 2)  # 1 + 2i
w = ComplexNumber(2, -3)  # 2 - 3i

z * w = ComplexNumber(8, 1)  # 8 + i
```
or
```python
p = Rational(1, 4)  # 1/4

p + p = Rational(1, 2) # 1/4 + 1/4 = 1/2
```
```python
class ComplexNumber:
    pass
```

### (9) Bonus: given a finite sequence of integers, find the length of the longest increasing subsequence.
A subsequence of a sequence $a_1, a_2,\dotsc,a_n$ is of the form $a_{i_1},\dotsc,a_{i_k}$, where $i_1 < i_2 < \ldots < i_k$.

Example:
```python
lst = [5, 3, 2, 4, 6, 1]
```
Expected output:
```python
# the longest increasing subsequences are [2, 4, 6] or [3, 4, 6]
3
```