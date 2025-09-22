---
layout: default
title: Lecture 6
nav_exclude: true
search_exclude: true
---



# Lecture 6: Sep 18



# Playing with numpy

# Reading Activity (approx 30 minutes)

- Navigate to [https://cs231n.github.io/python-numpy-tutorial/#numpy](https://cs231n.github.io/python-numpy-tutorial/#numpy) and read through the sections on numpy. Copy the code elements and run them as you read the sections. Questions? Ask me. Upload your ipynb file with coding exercise on moodle. But first make sure that I have examined your code in class.


# Short Review of arrays

## Introduction to NumPy Arrays

NumPy (Numerical Python) is a powerful Python library used for numerical computing.  
Its core feature is the **ndarray** (n-dimensional array), which allows efficient storage and manipulation of numerical data.

---

## Why NumPy Arrays?

- Faster than Python lists for numerical operations.
- Provide vectorized operations (apply operations to entire arrays at once).
- Support multidimensional data (matrices, tensors).
- Offer many built-in mathematical functions.

---

## Creating NumPy Arrays

First, import NumPy:



```
import numpy as np
$$ \nabla_\boldsymbol{x} J(\boldsymbol{x}) $$
# Creating a 1D NumPy array
arr1 = np.array([1, 2, 3, 4, 5])
print(arr1)

# Access elements
print("First element:", arr1[0])
print("Last element:", arr1[-1])

# Array operations
print("Array + 10:", arr1 + 10)
print("Array squared:", arr1 ** 2)

```

# Creating a 2D NumPy array
```

arr2 = np.array([[1, 2, 3],
                 [4, 5, 6]])
print(arr2)
```$$ \nabla_\boldsymbol{x} J(\boldsymbol{x}) $$

# Access elements
```

print("Element at row 0, col 1:", arr2[0, 1])   # row 0, column 1
print("First row:", arr2[0])
print("First column:", arr2[:, 0])
```

# Array operations
```

print("Transpose:\n", arr2.T)
print("Sum of all elements:", arr2.sum())
print("Column sums:", arr2.sum(axis=0))
print("Row sums:", arr2.sum(axis=1))
```

# Basic math and Trignometric functions

```

x = np.array([0, 1, 2, 3])
print("Exponential:", np.exp(x))
print("Square root:", np.sqrt(x))
print("pi:", np.pi)

angles = np.array([0, np.pi/6, np.pi/4, np.pi/2])  # radians
print("Angles (radians):", angles)
print("sin:", np.sin(angles))
print("cos:", np.cos(angles))
print("tan:", np.tan(angles))

```

# Coding excercise 1

- Create an array with 10 numbers that represent temperature in Farenheit. Then write code to convert the values to Celcius.

- upload the code to moodle
  
# Coding exercise 2

- create an array with 10 numbers that represent angles in degrees.  Then write code to convert the values to radians.
- upload the code to moodle
# Coding exercise 3



## Example: Estimate sin of an angle via series Expansion of sin(x). 

The Taylor series expansion for sin(x) is:

sin(x) = x - x^3/3! + x^5/5! - x^7/7! + ...


- Write code to first directly output  $\sin(30^\circ)$. (Remember to convert 30° to radians)
- Then write code to approximate  $\sin(30^\circ)$ using the Taylor expansion as shown above. Your code should output the estimate as you progressively increase the number of terms in the formula (start with just 1 term and then add other terms). Try using loops or recursions.

- upload the code to moodle



## Solutions

- Will be added here shortly.


# Resources

- [https://www.learnpythonwithjupyter.com/](https://www.learnpythonwithjupyter.com/)

- [https://nustat.github.io/DataScience_Intro_python/](https://nustat.github.io/DataScience_Intro_python/)


$$ \nabla_\boldsymbol{x} J(\boldsymbol{x}) $$
