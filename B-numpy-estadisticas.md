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