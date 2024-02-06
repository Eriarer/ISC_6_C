# Asignaciones
`x <- 5`
`8 -> y`
## Generación de vectores
### Vector normal
- Vector de 1 a 100
`x <- 1:100 `
- Vector de 10 a 1
`x <- 10:1`
### Seq()
- Vector de 1 a 9, de 3 en 3
`x <- seq(1, 9, 3)`
- Vector de 1 a 9, de 0.1 en 0.1
`x <- seq(1, 9, 0.1)`
- Vector de 0 a 100 con 20 elementos equidistantes
`x <- seq(0, 100, length.out = 20)`
### Rep()
- Vector con 5 repeticiones del número 9
`x <- rep(9, 5)`
- Vector repetido de 1 a 3, dos veces
`x <- rep(1:3, 2)`

### Concatenar
- 0 y 1 una vez _asignación ordinaria_
- 1 y 2 tres veces _rep_
- 3 a 15 de dos en dos _seq_
`x <- c(0, 1, rep(1:2, 3), seq(3, 15, 2))`


# Comandos
## sum
Calcula la suma de todos los elementos en el vector 'x'
`sum_result <- sum(x)`

## mean
 Calcula el promedio de los elementos en el vector 'x'
`mean_result <- mean(x)`

## min
Encuentra el valor mínimo en el vector 'x'
`min_value <- min(x)`

## max
Encuentra el valor máximo en el vector 'x'
`max_value <- max(x)`

## length
Obtiene la longitud (número de elementos) del vector 'x'
`length_x <- length(x)`

# Operaciones con vectores
- Suma de vectores
`sum_vectors <- x + y`

- Resta de vectores
`subtraction_vectors <- x - y`

- Multiplicación de vectores
`multiplication_vectors <- x * y`

- División de vectores
`division_vectors <- x / y`


# Acceso a elementos y filtrado
## Indexado
 - Accede al segundo elemento en el vector 'y'
 `second_element <- y[2]`
- Excluyendo el segundo elemento en el vector 'y'
`elements_except_second <- y[-2]`

- Excluyendo los elementos del 1 al 3 en el vector 'y'
`elements_except_1_to_3 <- y[-(1:3)]`

- Incluye solo los elementos en 'y' que son menores que 8
`elements_less_than_8 <- y[y < 8]`

- Incluye solo los elementos en 'y' cuyos índices son mayores que 2
`filtered_elements <- y[x > 2]`


# Funciones

## Función factorial
```R
factorial_function <- function(x) {
    result <- 1
    for (i in 1:x)
        result <- result * i
    return(result)
}
```