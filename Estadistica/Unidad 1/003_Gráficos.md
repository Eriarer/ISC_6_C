Los gráficos son *representaciones visuales* de un conjunto de *datos*. Los gráficos, tienen:
- **Título** Nos indica la información que representa el gráfico, y por lo regular, es similar al de una tabla de datos. $evitar\ el\ tipo\ de\ gráfico$
- **Cuerpo** Es la representación en si del *conjunto* de *datos*.
- **Escalas** Son la graduación y las etiquetas de los *ejes* $cuando\ existan$
- **Fuente o Descripción** Indica de donde provienen, o cómo se obtuvieron los datos. 
# Tipos de gráficos
## Barras
Es una representación para datos *categóricos* o *cuantitativos $discretos$*, en el cual se asocia a cada categoría una barra de altura proporcional $la\ anchura\ no\ importa$ a algunas de las frecuencias $relativas\ o\ absolutas$.

Se suelen poner las *barras* separadas unas de las otras, que va a ser una diferencia que se verá con respecto al *histograma*.
### Pictograma
Como casos especiales de un gráfico de barras, se tiene a los pictogramas; en los que, en lugar de barras se utilizan figuras de altura proporcional a la frecuencia. Para lograrlo primero se escogen figuras alusivas al tema, se recomienda que todas las figuras sean del mismo tamaño.
Y estas se alargan de manera que llegue a la altura requerida o se repite hasta alcanzar la altura necesaria. En este caso, la figura de hasta arriba, puede aparecer mutilada
## Gráfico de sectores o $Pastel$
Un gráfico de sectores o de $pastel$ es un gráfico basado en un circulo (Representa a la totalidad de los datos) y expresa de manera gráfica la distribución proporcional de los eventos o datos en estudio.
> [!warning] Barras y Pastel
> - Estos gráficos no se recomiendan  cuando hay muchas categorías.
> - No se recomienda agregar efectos 3D o perspectiva. 
> - Si hay muchas categorías, sobre todo de poca frecuencia,  se pueden agrupar en 1 sola que se llamen otras o varias.
> - En el gráfico de **sectores** se deben de mostrar de forma explicita, los conteos o porcentajes de cada categoría, ya sea dentro del gráfico, o en una leyenda.
### Ejercicio
En la siguiente tabla se muestran los datos correspondientes a la fruta preferida de los alumnos del grupo 6$^{to}$-C

|Fruta preferida| N. Alumnos |
| --- | :-: |
| Naranja | 3 |
| Plátano | 4 |
| Manzana | 7 |
| Uva | 12 |
| Fresa | 8 |

Elabore un gráfico de barras, un pictograma y un gráfico de sectores para representar los datos.

Solución
```mermaid
pie title Fruta preferida
    "Naranja" : 3
    "Plátano" : 4
    "Manzana" : 7
    "Uva" : 12
    "Fresa" : 8
```

```mermaid
---
config:
  xyChart:
    width: 1000
    height: 600
  themeVariables:
    xyChart:
      backgroundColor: "#00000000"
      titleColor: "#ffffff"
      xAxisLabelColor: "#ffffff"
      xAxisTitleColor: "#ffffff"
      xAxisTickColor: "#ffffff"
      xAxisLineColor: "#ffffff"
      yAxisLabelColor: "#ffffff"
      yAxisTitleColor: "#ffffff"
      yAxisTickColor: "#ffffff"
      yAxisLineColor: "#ffffff"
      plotColorPalette: "#21caeb"
---
xychart-beta
title "Fruta preferida"
x-axis "Fruta" [Naranja, Platano, Manzana, Uva, Fresa]
y-axis "N. Alumnos" 0 --> 12
bar [3,4,7,12,8]
```
## Puntos
Los gráficos de puntos funcionan en el caso de pequeños conjuntos de datos (dados de forma extensiva), y se crean colocando un punto, que representa a cada observación a lo largo de una recta numérica. En el caso de que hayan observaciones idénticas o muy próximas, los puntos se apilan o se colocan al lado o uno sobre otro para que se muestren de manera individual
En el caso de que los datos tengan asociada una categoría, esta  se puede usar para separar los datos, agregando varios ejes paralelos con la misma escala.  
![Diagrama de puntos](../../0media/Estadistica/Diagrama_Puntos_Ejemplo.png)
## Histograma
Un histograma se emplea para ilustrar muestras agrupadas en intervalos (tipo III) esta integrado por rectángulos unidos (adyacentes) cuyos vértices de la base coinciden con los límites de los intervalos. 
Los histogramas no son adecuados para comparar dos grupos de datos. En este caso puede ser más adecuado un polígono de frecuencias, en el cual los rectángulos se sustituyen por puntos en la parte superior de los rectángulos, uniendo dichos puntos con lineas rectas.    
En los histogramas se pierde el orden en que fueron tomados los datos; por lo que no perite observar patrones a lo largo del tiempo.
Se recomienda que el eje que representa a las frecuencias,  comience en $\large0$.  

![Histograma](../../0media/Estadistica/Diagrama_Histograma.png)
## Ojiva
Una ojiva representa frecuencias acumuladas y está formado por puntos unidos en lineas rectas. Suele acompañar a un diagrama de barras o a un histograma.  

![Ojiva](../../0media/Estadistica/Diagrama_Ojiva.png)
## Caja y brazos (Boxplot)
1. $\large Q_1,Q_2,Q_3, IQR$  
1. Calculamos la cercas interiores inferiores y superiores:  
      $\large CI_i = Q_1-1.5*IQR$
      $\large CI_s = Q_3+1.5*IQR$  
1. Se consideran datos comunes o típicos a los datos dentro del intervalo definido por las *cercas interiores*.
   Se denominan datos atípicos o aberrantes a los datos fuera del intervalo antes mencionado. Los datos atípicos se marcan con un símbolo de manera individual.     
   ![](../../0media/Estadistica/Diagrama_Boxplot2.png)
   ![Boxplot](../../0media/Estadistica/Diagrama_BoxPlot.png)
   ### Ejemplo
   Elabore el diagrama *boxplot* para los siguientes datos:  
   
   1|2|3|4|5|6|7|8|9|10|11|12|13|14
   :-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:
   89|557|1200|918|593|499|76|203|465|200|513|207|18|513
   ![Grafico por computadora](../../0media/Estadistica/Grafico_Boxplot_EJ1.png)