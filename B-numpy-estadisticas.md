https://colab.research.google.com/drive/1gjLXfsqGpGuUmOEGazMRviYgH1FI_XDo#scrollTo=2e61d52b&line=36&uniqifier=1

# Usaremos el arreglo unidimensional creado anteriormente para los ejemplos
arr_unidimensional = np.array([1, 2, 3, 4, 5])
print("Arreglo para estadística:")
print(arr_unidimensional)

# Media (promedio)
media = np.mean(arr_unidimensional)
print(f"\nMedia: {media}")

# Mediana
mediana = np.median(arr_unidimensional)
print(f"Mediana: {mediana}")

# Desviación estándar
desviacion_estandar = np.std(arr_unidimensional)
print(f"Desviación estándar: {desviacion_estandar}")

# Varianza
varianza = np.var(arr_unidimensional)
print(f"Varianza: {varianza}")

# Valor mínimo
minimo = np.min(arr_unidimensional)
print(f"Valor mínimo: {minimo}")

# Valor máximo
maximo = np.max(arr_unidimensional)
print(f"Valor máximo: {maximo}")

# Suma de todos los elementos
suma_total = np.sum(arr_unidimensional)
print(f"Suma total: {suma_total}")

# Producto de todos los elementos
producto_total = np.prod(arr_unidimensional)
print(f"Producto total: {producto_total}")

## resuelve

Arreglo para estadística:
[1 2 3 4 5]

Media: 3.0
Mediana: 3.0
Desviación estándar: 1.4142135623730951
Varianza: 2.0
Valor mínimo: 1
Valor máximo: 5
Suma total: 15
Producto total: 120

## referencias ## 
Referencias de consulta

McKinney, W. (2017). Python for Data Analysis: Data Wrangling with Pandas, NumPy, and IPython (2nd ed.). O’Reilly Media.

Harris, C. R., Millman, K. J., van der Walt, S. J., Gommers, R., Virtanen, P., Cournapeau, D., ... & Oliphant, T. E. (2020). Array programming with NumPy. Nature, 585(7825), 357–362. https://doi.org/10.1038/s41586-020-2649-2

Wes McKinney. (2022). pandas: Powerful Python data analysis toolkit. Documentation. https://pandas.pydata.org/docs/

NumPy Developers. (2022). NumPy Reference Documentation. https://numpy.org/doc/

VanderPlas, J. (2016). Python Data Science Handbook. O’Reilly Media. https://jakevdp.github.io/PythonDataScienceHandbook/
