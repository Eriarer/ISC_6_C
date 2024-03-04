$\large X:A$ -> $\large R$
$\large \Omega =\{$

   |   |   
 :-: | :-: | :-:
 x|x|x
 x|x|c
 x|c|x
 x|c|c
 c|x|x
 c|x|c
 c|c|x
 c|c|c
$\large \}$

$x=x(w) \small{\text{        x = cantidad de caras}}$
$P(x=k)=P(\{w|w(x)=k\})$

K | P(x=k)
:-: | :-:
0 | 1/8
1| 3/8
2 | 3/8
3 | 1/8

$y=y(w) \small{\text{        y = cantidad de cruces}}$
$P(y=k)=P(\{w|w(y)=k\})$

K | P(y=k)
:-: | :-:
0 | 1/8
1| 3/8
2 | 3/8
3 | 1/8

En este caso, decimos que la distribución de probabilidad de $x$ y $y$ son iguales. Las distribuciones de probabilidad se caracterizan, por las *funciones de distribución de probabilidad*.  
Una función $f$ es una función de distribución de probabilidad, sí:
- $f(x)\ge 0 \forall x\in Z$
  $\Large \Sigma _x f(x)=1$
  Ejemplo de f(x)=
  
   | 
   :-: | :-:
   1/8 | x=0
   3/8 | x=1
   3/8 | x=2
   1/8 | x=3
   Esta función $f$ nos da la *función de distribución de probabilidad* de las $X$ y $Y$ de ejemplo de las monedas. En este caso decimos, que $X$ tiene distribución $f$  -> $x \thicksim f$
-  Una familia de distribuciones de probabilidad es un conjunto de *funciones de distribución de probabilidad* con expresión algebraica similar. Las funciones en una familia se distingue por el valor de una constante que llamaremos parámetro de las distribuciones.
  Propiedades ties:
    - $\sum_{n = 0}^{\infty} r^n = \frac{1}{1 - r}$ , para $|r| < 1$
    - $(x + y)^n$ = $\sum_{k = 0}^{n} \binom{n}{k} x^{n-k} y^k$
    - $\text{exp}(x) = e^x = \sum_{n = 0}^{\infty} \frac{x^n}{n!}$