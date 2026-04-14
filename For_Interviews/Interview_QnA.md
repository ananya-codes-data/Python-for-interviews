# ✅ Python Interview Questions With Answers 🐍

1. What is Python?

- Interpreted, high-level programming language
- Created by Guido van Rossum in 1991
- Used for web dev, data analysis, automation, AI

2. What is an interpreter?

- Executes code line-by-line without compilation
- Python uses CPython as default interpreter
- Faster for development, slower runtime than compiled languages

3. What are variables?

- Named storage for data values
- Dynamically typed: type inferred at runtime
- Example:

```python
age = 30 #(int)
name = "Bonus" #(str)
```

4. What are data types?

- Built-in types: int, float, str, bool, list, tuple, dict, set
- Mutable: list, dict, set (can change contents)
- Immutable: int, str, tuple (cannot change after creation)

5. What is a list?

- Ordered, mutable collection of items
- Allows duplicates, indexed from 0
- Example: customers = ["A", "B", "A"]

6. What is a dictionary?

- Unordered key-value pairs (ordered since Python 3.7)
- Keys unique, values any type
- Example: user = {"id": 1, "name": "Bonus"}

7. Difference between list and tuple

- List mutable [], Tuple immutable ()
- List slower, Tuple faster and hashable
- Use tuple for fixed data like coordinates

8. What are loops?

- For: iterate sequences (for i in range(5))
- While: condition-based (while x < 10)
- Used for repeating tasks efficiently

9. What are functions?

- Reusable code blocks defined with def
- Can take parameters, return values
- Example:

```python
def greet(name): 
         return f"Hello {name}"
```

10. Interview tip you must remember

- Always explain with code example
- Discuss time complexity (O(1), O(n))
- Practice on LeetCode for data roles

11. What are if-else statements?

- Conditional execution based on boolean conditions

```python

  if condition:
      ...
  elif condition:
      ...
  else:
      ...
```

Example:

```python
  if age >= 18:
      print("Adult")
  else:
      print("Minor")
```

12. What are classes and objects?

- Class: blueprint for creating objects
- Object: instance of a class with attributes/methods

Example:

```python
  class Car:
      def __init__(self, brand):
          self.brand = brand
```

13. What is inheritance?

- Child class inherits properties from parent class
- Promotes code reuse

Example:

```python
  class ElectricCar(Car):
      def charge(self):
          pass
```

14. What is polymorphism?

- Same method name, different behaviors in child classes
- Method overriding

Example:

```python
  class Animal:
      def speak(self):
          pass
  class Dog(Animal):
      def speak(self):
          return "Bark"
  class Cat(Animal):
      def speak(self):
          return "Meow"
```

15. What are exceptions?

- Errors during execution (ZeroDivisionError, KeyError)
- Handle with try-except-else-finally

Example:

```python
  try:
      x / 0
  except:
      print("Cannot divide by zero")
```

16. What is a module?

- File with Python code (functions, classes)
- Import with `import math` or `from math import sqrt`
- Standard library: os, datetime, json

17. What is a package?

- Directory with modules and `__init__.py` file
- Organizes related modules
- Example: numpy.random, pandas.io

18. What are list comprehensions?

- Concise way to create lists
- `[x2 for x in range(5)]` → `[0, 2, 4, 6, 8]`
- Faster and more readable than for loops

19. What is lambda function?

- Anonymous single-expression function
- `lambda x: x2`
- Used in map(), filter(), sorted(key=)

20. Interview tip you must remember

- Draw class diagrams for OOP questions
- Always mention time/space complexity
- Code live during interviews (use print debugging)

21. What are generators?

- Functions that yield values one at a time (memory efficient)
- Use yield keyword instead of return
- Example:

```python
def count():
    for i in range(1, 5):
        yield i
```

22. What is a decorator?

- Function that modifies another function's behavior
- @timer syntax adds functionality before/after

Example:

```python
def timer(func):
    def wrapper():
        print("Time started")
        func()
        print("Time ended")
    return wrapper

@timer
def my_func():
    print("Hello")
```

23. What are args and kwargs?

- args: variable positional arguments (tuple)
- kwargs: variable keyword arguments (dict)
- Example:

```python
def func(args, kwargs):
    print(args, kwargs)
```

24. What is list slicing?

- Extract portions: list[start:end:step]
- my_list[1:4] gets elements 1 to 3
- Negative indices: [-3:] gets last 3 elements

Example:

```python
my_list = [1, 2, 3, 4, 5]
print(my_list[1:4])  # [2, 3, 4]
```

25. What is the difference between == and is?

- == compares values (5 == 5.0 → True)
- is compares object identity (5 is 5 → True, but 500 is 500 → False)
- Use is for None, True, False checks

26. What are sets?

- Unordered collection of unique elements
- {1,2,3}, add(), remove(), union(), intersection()
- Great for membership testing (O(1))

27. What is string formatting?

- f-strings: f"Age: {age}"
- .format(): "Age: {}".format(age)
- % formatting: "Age: %d" % age (older style)

28. What are file operations?

- Open: with open('file.txt', 'r') as f:
- Modes: 'r', 'w', 'a', 'rb', 'wb'
- Read: f.read(), f.readline(), f.readlines()

29. What is map(), filter(), reduce()?

- map(): applies function to each item
- filter(): keeps items matching condition
- reduce(): accumulates (from functools import reduce)

Examples:

```python
list(map(lambda x: x2, [1, 2, 3]))  # [2, 4, 6]
list(filter(lambda x: x>1, [1, 2, 3]))  # [2, 3]
from functools import reduce
reduce(lambda x, y: x+y, [1, 2, 3])  # 6
```

30. Interview tip you must remember

- Know memory management (Garbage Collection)
- Practice debugging: print(), pdb, breakpoints
- Explain generator vs list for big data scenarios

31. What are context managers?

- Manages resources automatically (files, locks)
- with statement ensures cleanup

Example:

```python
with open('file.txt') as f:
    data = f.read()
# File auto-closes even if error
```

32. What is Garbage Collection?

- Automatic memory management
- Reference counting + cycle detection

Example:

```python
import gc
gc.collect()  # forces cleanup
```

33. What are iterators?

- Objects with next() method
- for loops use iterators internally

Example:

```python
class Countdown:
    def __init__(self, start):
        self.start = start
    def __iter__(self):
        return self
    def __next__(self):
        if self.start <= 0:
            raise StopIteration
        self.start -= 1
        return self.start + 1
```

34. What is the Global Interpreter Lock (GIL)?

- Limits multi-threading to one thread at a time
- Affects CPU-bound tasks, not I/O
- Use multiprocessing for true parallelism

35. What are pandas DataFrames?

- 2D table like Excel/ SQL tables

Example:

```python
import pandas as pd
df = pd.DataFrame({'A': [1, 2], 'B': [3, 4]})
```

36. What is NumPy?

- Library for numerical computing
- Arrays:

```python
import numpy as np
arr = np.array([1, 2, 3])
```

- Vectorized operations (fast)

37. What are virtual environments?

- Isolated Python environments
- Example:

python -m venv myenv
source myenv/bin/activate

- pip install only affects this env

38. What is pip?

- Python package installer

Example:
pip install pandas
pip freeze > requirements.txt

- Manages dependencies

39. What are list vs. NumPy array performance?

- NumPy arrays 50-100x faster for math ops
- Fixed type, contiguous memory
- Use NumPy for numerical data

40. Interview tip you must remember

- Pandas: head(), shape, dtypes, info() first
- Always check data types before operations
- Time your solutions (%%time in Jupyter)

41. What is a comprehension for dict/set?

- Dict: {k: v2 for k,v in data.items()}
- Set: {x2 for x in nums}
- One-liner for creating collections

42. What are property decorators?

- @property: getter for class attributes
- @attr.setter: controlled modification
- Example:

```python
class Circle:
    def __init__(self, radius): self._radius = radius
    @property
    def radius(self): return self._radius
    @radius.setter
    def radius(self, value): self._radius = value
```

43. What is enumerate()?

- Adds index to iterable: for i, item in enumerate(lst)
- Default start=0
- Better than range(len())

44. What is zip()?

- Pairs iterables: list(zip(keys, values)) → dict
- Stops at shortest iterable
- Example:

```python
names = ['A','B']
ages = [25,30]
print(list(zip(names, ages)))  # [('A',25),('B',30)]
```

45. What are type hints?

- Static typing: def add(a: int, b: int) -> int:
- Helps IDEs, mypy checker
- No runtime enforcement

46. What is `__str__` vs `__repr__`?

- `__str__`: user-friendly print(str(obj))
- `__repr__`: developer-friendly, eval-able
- Always implement both

47. What are slots in classes?

- `__slots__` = ['attr1', 'attr2']
- Saves memory, faster attribute access
- No `__dict__`

48. What is multiprocessing vs threading?

- Threading: I/O bound (GIL limits CPU)
- Multiprocessing: CPU bound, separate memory
- from multiprocessing import Pool

49. What is async/await?

- Asynchronous programming (asyncio)
- async def fetch(): await asyncio.sleep(1)
- For I/O heavy tasks (web scraping)

50. Interview tip you must remember

- Big O notation: list append O(1), slicing O(k)
- LeetCode mediums: two pointers, hashmaps
- Mock interview: explain as you code aloud

51. What is the difference between / and // in Python?

- `/` : True division always returns float (5/2 → 2.5)
- `//` : Floor division returns integer (5//2 → 2, -5//2 → -3)
- Example:

```python
print(5/2)   # 2.5
print(5//2)  # 2
print(-5//2) # -3
```

52. How do you reverse a list in Python? (3 ways)

```python
lst[::-1]          # slicing - creates new list
lst.reverse()      # modifies original, returns None
list(reversed(lst)) # iterator to list
```

- `lst[::-1]` most Pythonic for read-only

53. How to find duplicates in a list?

```python
seen = []
dups = [x for x in lst if x in seen or seen.append(x)]
# Better:
from collections import Counter
dups = [item for item, count in Counter(lst).items() if count > 1]
```

54. Check if string is palindrome (ignore case/spaces)?

```python
s = s.lower().replace(" ","")
return s == s[::-1]
```

- One-liner: `s.lower().replace(" ","") == s.lower().replace(" ","")[::-1]`

55. Flatten nested list (jagged)?

```python
[x for l in lst for x in l]              # comprehension
sum(lst, [])                            # simple but slow
```

Example: `[[1,2],[3],[4,5]] → [1,2,3,4,5]`

56. Merge two sorted lists efficiently?

```python
import heapq
merged = list(heapq.merge(list1, list2))  # generator
# Or simple:
sorted(list1 + list2)                     # O(n log n)
```

57. Remove all occurrences of an element from list?

```python
lst[:] = [x for x in lst if x != value]  # modifies original
# DON'T use lst.remove() in loop - shifts indices!
```

58. Find most frequent element in list?

```python
from collections import Counter
most_common = Counter(lst).most_common(1)[0]
# Returns (element, frequency) tuple
```

59. Rotate list by k positions?

```python
def rotate(lst, k):
    k = k % len(lst)  # handle large k
    return lst[-k:] + lst[:-k]  # left rotate
```

Example: `rotate([1,2,3,4,5], 2) → [4,5,1,2,3]`

60. Interview tip you must remember

- Always discuss time/space: slicing O(n), Counter O(n)
- Test edge cases: empty list `[]`, single element `[5]`
- Two pointers + hashmap = 80% of list problems solved
