## Dundering Featureclasses 

Chapter 4 of the text book discusses the use of dunder methods.  Create a class called `FeatureClass` with a minimum of the listed dunder methods below:

+ addition - merge two datasets together and produce a 3rd feature class
+ subtraction - erase data from the first dataset based on the second dataset.  The return should be a new feature class.
+ iteration - return a iterable object for each record in the feature class

This will give you an 8/10 if done correctly.  Implement an additional dunder method that performs an operation on the dataset (this means we are excluding str, len, repr, etc..) to get a 10/10.

**Ensure PEP-8 standards are followed.**

Starting Code:

```python
class FeatureClass():
    """
    Update my docstring
    """
    _path = None
    
    def __init__(self, path:str):
        """Intializer"""
        self._path = path
    
```


### About the Assignment

+ **Number of Points:** 10
+ **Due Date:** End of Week 2, Sunday @ 11:59 PM

### Data Links

Download the [Feature Classes](https://raw.githubusercontent.com/achapkowski/AS.430.618/gh-pages/lessons/data/assignment_01/class.txt)

### What to turn in?

A Jupyter Notebook containing workable code (50%), description on how to run/use the program with proper documentation standards (50%).

Submit assignments using blackboard.