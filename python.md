# WHAT IS NUMPY ? 
NumPy (Numerical Python) is a Python library for fast mathematical and scientific computing.
It provides a special data structure called ndarray (N-dimensional array), which is faster and more efficient than normal Python lists for handling numbers.
```
pip install numpy
```
ex: import numpy as np

arr = np.array([1, 2, 3, 4])  
print(arr * 5)


| Category                        | Key Functions / Methods                                                             | What It Does                                                       |
| ------------------------------- | ----------------------------------------------------------------------------------- | ------------------------------------------------------------------ |
| **Array Creation**              | `np.array()`, `np.zeros()`, `np.ones()`, `np.arange()`, `np.linspace()`, `np.eye()` | Create arrays in different ways (empty, sequence, identity matrix) |
| **Random / Probabilities**      | `np.random.rand()`, `np.random.randint()`, `np.random.randn()`                      | Generate random numbers, useful for testing and simulations        |
| **Array Operations**            | `+`, `-`, `*`, `/`, `**`                                                            | Element-wise arithmetic operations                                 |
| **Aggregations / Statistics**   | `sum()`, `mean()`, `max()`, `min()`, `std()`, `var()`                               | Compute totals, averages, standard deviation, variance, etc.       |
| **Indexing / Slicing**          | `arr[0]`, `arr[0:3]`, `arr[arr>5]`, `arr[[0,2]]`                                    | Access elements, slices, boolean and fancy indexing                |
| **Reshape / Transform**         | `reshape()`, `ravel()`, `flatten()`, `transpose()`, `resize()`                      | Change the shape or orientation of arrays                          |
| **Linear Algebra**              | `np.dot()`, `np.cross()`, `np.linalg.inv()`, `np.linalg.det()`                      | Matrix multiplication, inverse, determinant, cross products        |
| **Math Functions**              | `np.sin()`, `np.cos()`, `np.exp()`, `np.log()`                                      | Apply mathematical operations element-wise                         |
| **Array Combining / Splitting** | `np.concatenate()`, `np.vstack()`, `np.hstack()`, `np.split()`                      | Merge or split arrays vertically or horizontally                   |
| **Sorting / Uniques**           | `np.sort()`, `np.argsort()`, `np.unique()`                                          | Sort arrays, get sorted indices, or unique elements                |


