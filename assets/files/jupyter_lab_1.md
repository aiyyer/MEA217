# Hello, JupyterLab!
print("Welcome to JupyterLab 🚀")

# A simple calculation
a = 5
b = 7
print("The sum of a and b is:", a + b)

# Using a library
import matplotlib.pyplot as plt
import numpy as np

x = np.linspace(0, 10, 100)
y = np.sin(x)

plt.plot(x, y, label="sin(x)")
plt.xlabel("x")
plt.ylabel("y")
plt.title("Simple Sine Wave")
plt.legend()
plt.show()
