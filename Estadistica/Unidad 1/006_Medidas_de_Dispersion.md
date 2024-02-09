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
### Rango R = $\Large x_{(n)}-x_{(1)}$
- Rango Intercuartílico
  $\large RIQ=Q_3-Q_1$
- Varianza
  $\LARGE S_n^2=\sum_{i=1}^{N} \frac{(x_i - \bar{x})^2}{n}$
  $\LARGE S_{n-1}^2=\sum_{i=1}^{N} \frac{(x_i - \bar{x})^2}{n-1}$
- Desviación estándar
  $\Large S_n=\sqrt{S_n^2}$
  $\Large S_{n-1}=\sqrt{S_{n-1}^2}$
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
- Desviación estándar:
  