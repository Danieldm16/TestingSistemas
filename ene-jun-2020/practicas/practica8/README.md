# Práctica 8
Programa 2 funciones que interactuen entre si y los las pruebas integrales para probar su relación.

## Primera función
La primera función es un algoritmo de censura. Toma 3 parámetros, el primero es un arreglo de strings, que contiene palabras malas, y el segundo parámetro es un string que contiene un texto en el cuál debes buscar palabras del primer arreglo y reemplazarlas con el tercer parámetro.

### Ejemplo
```
func(["popo", "sangre", "muerte", "maldito"], "El animal maldito se acercó con una mirada de muerte. Manchas de sangre cubrían el suelo", "kawai")

return -> "El animal kawai se acercó con una mirada de kawai. Manchas de kawai cubrían el suelo"
```

## Segunda función
La segunda función toma un texto, lo pasa por la función de censura y luego determina si el resultado sigue siendo válido o no. Para determinar si es válido compara el tamaño del texto de entrada y el de salida, si tienen una diferencia mayor a un determinado número no es válido.

La función toma los mismos parámetros de la primera función y uno adicional, un entero que marca el límite que puede tener la diferencia entre la entrada y el texto resultante.

## Tests
Escribe los tests para probar la integración de las 2 funciones, puedes hacerlo top down o bottom up.