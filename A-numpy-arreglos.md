https://colab.research.google.com/drive/1gjLXfsqGpGuUmOEGazMRviYgH1FI_XDo#scrollTo=2e61d52b&line=36&uniqifier=1

# Arreglo unidimensional (vector)
arr_unidimensional = np.array([1, 2, 3, 4, 5])
print("Arreglo unidimensional:")
print(arr_unidimensional)

# Arreglo bidimensional (matriz)
arr_bidimensional = np.array([[1, 2, 3], [4, 5, 6]])
print("\nArreglo bidimensional:")
print(arr_bidimensional)

# Arreglo de ceros
arr_ceros = np.zeros((2, 3))
print("\nArreglo de ceros:")
print(arr_ceros)

# Arreglo de unos
arr_unos = np.ones((3, 2))
print("\nArreglo de unos:")
print(arr_unos)

# Arreglo con un rango de valores
arr_rango = np.arange(0, 10, 2) # Inicia en 0, termina antes de 10, con paso de 2
print("\nArreglo con rango:")
print(arr_rango)

# Arreglo con valores espaciados linealmente
arr_linspace = np.linspace(0, 10, 5) # 5 valores entre 0 y 10 (inclusive)
print("\nArreglo con linspace:")
print(arr_linspace)

# Arreglo con números aleatorios
arr_aleatorio = np.random.rand(2, 2) # Arreglo 2x2 con valores aleatorios entre 0 y 1
print("\nArreglo aleatorio:")
print(arr_aleatorio)

## Resuelve 

Arreglo unidimensional:
[1 2 3 4 5]

Arreglo bidimensional:
[[1 2 3]
 [4 5 6]]

Arreglo de ceros:
[[0. 0. 0.]
 [0. 0. 0.]]

Arreglo de unos:
[[1. 1.]
 [1. 1.]
 [1. 1.]]

Arreglo con rango:
[0 2 4 6 8]

Arreglo con linspace:
[ 0.   2.5  5.   7.5 10. ]

Arreglo aleatorio:
[[0.79723199 0.3610346 ]
 [0.87983776 0.55090396]]


 ## referencias ##
 
 Referencias de consulta

McKinney, W. (2017). Python for Data Analysis: Data Wrangling with Pandas, NumPy, and IPython (2nd ed.). O’Reilly Media.

Harris, C. R., Millman, K. J., van der Walt, S. J., Gommers, R., Virtanen, P., Cournapeau, D., ... & Oliphant, T. E. (2020). Array programming with NumPy. Nature, 585(7825), 357–362. https://doi.org/10.1038/s41586-020-2649-2

Wes McKinney. (2022). pandas: Powerful Python data analysis toolkit. Documentation. https://pandas.pydata.org/docs/

NumPy Developers. (2022). NumPy Reference Documentation. https://numpy.org/doc/

VanderPlas, J. (2016). Python Data Science Handbook. O’Reilly Media. https://jakevdp.github.io/PythonDataScienceHandbook/
