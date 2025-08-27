## Selección avanzada ##
# Seleccionar columnas específicas
print(df[["Nombre", "Salario"]])

# Selección por condición
print(df[df["Edad"] > 30])

# Selección con múltiples condiciones
print(df[(df["Ciudad"] == "Bogotá") & (df["Salario"] > 2800)])

## Agrupamiento y agregación ##
# Agrupar por ciudad y calcular salario promedio
print(df.groupby("Ciudad")["Salario"].mean())

# Múltiples funciones de agregación
print(df.groupby("Ciudad")["Salario"].agg(["mean", "max", "min"]))

## Ordenamiento ##

# Ordenar por salario
print(df.sort_values(by="Salario"))

# Ordenar por edad descendente
print(df.sort_values(by="Edad", ascending=False))

## Manejo de valores nulos ##
# Insertamos algunos valores nulos
df.loc[2, "Salario"] = np.nan
df.loc[4, "Edad"] = np.nan

print(df)

# Verificar valores nulos
print(df.isnull())

# Rellenar valores nulos
print(df.fillna({"Salario": df["Salario"].mean(), "Edad": df["Edad"].median()}))

# Eliminar filas con valores nulos
print(df.dropna())

## Merge y Join ##

# Creamos un DataFrame extra
extra = pd.DataFrame({
    "Ciudad": ["Bogotá", "Cali", "Medellín"],
    "Población": [8000000, 2500000, 2600000]
})

# Merge (unión por ciudad)
merged = pd.merge(df, extra, on="Ciudad")
print(merged)
