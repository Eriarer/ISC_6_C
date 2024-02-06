- **Tendencia central**
        Valores *representativos* de un conjunto de datos. Una medida de tendencia central $M$ pretende resumir todos los datos en un único valor.  
        **Propiedades:**
    - Es invariante al orden de los datos de entrada.
    - $M$ Es un valor entre el mínimo y el máximo de los datos
            $x_{(1)}\le M_{(x_1,...x_n)}\le X_{(n)}$
    - **Cambio de escala** la medida $M$ de los datos escalados, es la medida original escalada.
              $M(ax_1,ax_2,...,ax_n) = aM(x_1,...,x_n)$
    - **Traslación** Al cambiar el origen de los datos, $M$ también cambia.
              $M(x_1+a,x_2+a,...x_n+a) = M(x_1,...,x_n)+a$
    - Medidas de tendencia central más comunes:
        - Media aritmética **promedio *media***
            $\Huge\displaystyle \bar{x} = \frac{1}{n} \sum_{i=1}^{n} x_i$  <- Datos tipo 1
            $\Huge\displaystyle \bar{x} = \frac{\sum_{k=1}^{k} w_k \times n_k}{n}$ <- Datos tipo 2
        - Mediana
          Datos tipo 1
          $$\Huge\tilde{x}= \begin{cases} x_{\frac{n}{2}} & \text{si } n \text{ es impar} \\ \frac{x_{\frac{n}{2}} + x_{\frac{n}{2}+1}}{2} & \text{si } n \text{ es par} \end{cases}$$
        - Moda
          En este curso la moda tiene que estar completamente definida, es decir, un unico dato que se repite más
         $\Huge\hat{x} = \text{arg} \max_i n_i$
> [!note] Ejemplo
> 9, 9, 11, 10, 7, 10, 10, 9, 10, 8, 9, 10
> Calcule media, mediana y moda
> media: 9.3333
> mediana: 9.5
> moda: 10

| Dato| Frecuencia |$N_k$ |
| :-: | :-: | :-:|
|7|1|1|
|8|1|2|
|9|4|6|
|10|5|11|
|11|1|12|

$\large \bar{x} = \frac{7*1+8*1+9*4+10*5+11*1}{12} = 9.3333$
$\large\tilde{x} = \frac{9+10}{2} = 9.5$

- **Dispersión**
        
- Concentración
- Posición
