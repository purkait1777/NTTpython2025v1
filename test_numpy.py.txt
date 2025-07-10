import numpy as np

# Create a 1D ndarray from a Python list
arr1d = np.array([1, 2, 3, 4, 5])
print("1D Array:", arr1d)
print("Shape of 1D Array:", arr1d.shape)

# Create a 2D ndarray (matrix)
arr2d = np.array([[1, 2, 3], [4, 5, 6]])
print("\n2D Array:\n", arr2d)
print("Shape of 2D Array:", arr2d.shape)
print("Data type of elements:", arr2d.dtype)

# Perform an element-wise operation
result = arr2d * 2
print("\nResult of element-wise multiplication:\n", result)