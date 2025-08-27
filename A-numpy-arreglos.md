# 📌 Datasheet NumPy - Arreglos

Este documento resume los comandos principales de **NumPy** para trabajar con arreglos.

---

## 🔹 1. Importar NumPy
```python
import numpy as np

## crear arreglos numpy ##
 
 # Arreglo 1D
arr1 = np.array([1, 2, 3])

# Arreglo 2D
arr2 = np.array([[1, 2, 3], [4, 5, 6]])

# Rango de valores
arr3 = np.arange(0, 10, 2)  # [0,2,4,6,8]

# Arreglo de ceros y unos
zeros = np.zeros((2,3))
ones = np.ones((3,3))

 
