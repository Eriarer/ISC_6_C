Las medidas de dispersión son números que indican que tan separados o dispersos se encuentran los datos entre si.

Mientras más grande sea el valor de la medida de dispersión, más alejados estarán los datos unos de otros.

$$\large \text{Sea } x={x_1,x_2,...,x_n}$$
$$\large D=D(x_1,x_2,...,x_n)\text{ Es medida de dispersión si:}$$ 
- No depende del orden de los datos de entrada
- D $\ge$ 0
- Si todos los dados son **iguales** -> D=0
- Invariante de traslación
  $\large D(x_1+a,x_2+a,...,x_n+a)=D(x_1,...,x_n)$
- Cambio de escala
  Sí $a<1$ entonces:
  $\large D(ax_1,...,ax_n)\lt D(x_1,...,x_n)$
  si $a>1$
  $\large D(ax_1,...,ax_n)\gt D(x_1,...,x_n)$
## Medidas más comunes
- Rango
- $\large R=x_{(n)}-x_{1}$
- Rango Intercuartílico
  $\large RIQ=Q_3-Q_1$
- Varianza poblacional
  $\LARGE S^2=\frac{\sum_{i=1}^{N} (x_i - \bar{x})^2}{n}$
  $\scriptsize\text{en el curso usaremos la notación }S_n^2$
- Varianza muestral
  $\LARGE \hat{S}^2=\frac{\sum_{i=1}^{N} (x_i - \bar{x})^2}{n-1}$
  $\scriptsize\text{en el curso usaremos la notación }S_{n-1}^2$
- Desviación estándar poblacional
  $\Large S=\sqrt{S^2}=\sqrt{\frac{\sum_{i=1}^{N} (x_i - \bar{x})^2}{n}}$
- Desviación estándar muestral
  $\Large \hat{S}=\sqrt{\hat{S}^2}=\sqrt{\frac{\sum_{i=1}^{N} (x_i - \bar{x})^2}{n-1}}$
# Ejercicio
Calcule el Rango, Rango intercuartílico, varianza y desviación  estándar
8, 2, 4, 9, 7

valores ordenados: 2, 4, 7, 8, 9

- Rango:
    $\large x_n=9$
    $\large x_1=2$
    $\large R=9-2=7$
- Rango intercuartílico:
      $\large n=5$ por lo tanto:
      $Q_3=\frac{3(5-1)}{4}+1=4$ entonces $Q_3=8$
      $Q_1=\frac{5-1}{4}=1.5$ entonces $Q_1=4$
      RIQ=5
- Varianza:
  $\LARGE \sum_{i=1}^{N} x_i^2=8^2+2^2+4^2+7^2+9^2=214$
  $\LARGE S_n^2=\frac{214}{5}-6^2=6.8$
- Desviación estándar:](<## Ejercicio: Medidas de dispersión

Calcule las medidas de dispersión para los siguientes datos:

| 8   | 2   | 4   | 9   | 7   |
| --- | --- | --- | --- | --- |

1. Ordenar los datos de menor a mayor.

- 2 4 7 8 9

2. Calcular el rango.

- $R = 9 - 2$
- $R = 7$

3. Calcular el rango intercuartílico.

- $Q_1 = 4$
- $Q_3 = 8$
- $RIQ = 8 - 4$
- $RIQ = 4$

Para calcular Q1 y Q3 se debe calcular el $C_{0.25}$ y el $C_{0.75}$.

4. Calcular la varianza.

- $\bar{x} = \frac{2 + 4 + 7 + 8 + 9}{5}$
- $\bar{x} = 6$
- $S^2_{n} = \frac{(2-6)^2 + (4-6)^2 + (7-6)^2 + (8-6)^2 + (9-6)^2}{5}$
- $S^2_{n} = \frac{34}{5}$
- $S^2_{n} = 6.8$
- $S^2_{n-1} = \frac{34}{4}$
- $S^2_{n-1} = 8.5$

5. Calcular la desviación estándar.

- $S_{n} = \sqrt{6.8}$
- $S_{n} = 2.6077$
- $S_{n-1} = \sqrt{8.5}$
- $S_{n-1} = 2.9155$

## Ejercicio: Propiedad

Calcule $S^2_{n}$ usando la siguiente propiedad:

$$S^2_{n} = \frac{\sum_{i=1}^{n} x_i^2}{n} - \bar{x}^2$$

1. Calcular $\sum_{i=1}^{n} x_i^2$

- $\sum_{i=1}^{n} x_i^2 = 8^2 + 2^2 + 4^2 + 9^2 + 7^2$
- $\sum_{i=1}^{n} x_i^2 = 214$

2. Calcular $S^2_{n}$

- $S^2_{n} = \frac{214}{5} - 6^2$
- $S^2_{n} = 6.8$
  