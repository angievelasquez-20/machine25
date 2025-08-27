## Valores básicos ##

arr = np.array([5, 10, 15, 20, 25])

np.min(arr)     # mínimo
np.max(arr)     # máximo
np.sum(arr)     # suma de todos
np.mean(arr)    # promedio
np.median(arr)  # mediana
np.std(arr)     # desviación estándar
np.var(arr)     # varianza

## Estadística en arreglos multidimensionales ##

mat = np.array([[1,2,3],[4,5,6],[7,8,9]])

np.mean(mat, axis=0)  # promedio por columna
np.mean(mat, axis=1)  # promedio por fila
np.sum(mat, axis=0)   # suma por columnas
np.sum(mat, axis=1)   # suma por filas

## Ordenamiento y percentiles ##
 
 arr = np.array([7, 1, 9, 3, 5])

np.sort(arr)         # orden ascendente
np.percentile(arr, 50) # percentil 50 (mediana)
np.percentile(arr, 90) # percentil 90
   
   ## correlaciones  y  covarianza ##
   
   x = np.array([1,2,3,4,5])
y = np.array([5,4,3,2,1])

np.corrcoef(x,y)   # correlación
np.cov(x,y)        # covarianza
