La probabilidad es una forma de modelar la regularidad estadística de algunos fenómenos observables en la naturaleza.  
## Frecuentista  
La definición frecuentista consiste en definir la probabilidad como *el límite cuando el número de experimentos $\large n$ tiende a infinito* de la frecuencia relativa del evento. Cuando el numero $\large n$  de repeticiones se hace muy grande, la frecuencia relativa converge hacia un valor que se toma como la probabilidad del evento $\large A$.
Es imposible llegar a este límite, ya que no se puede repetir el experimento un número infinito de veces, pero sí un número suficientemente grande de veces y parar cuando las frecuencias relativas empiezan a estabilizarse.   
## Clásica  
Bajo este enfoque, la probabilidad de cualquier evento $\large A$  es igual al cociente entre el número de casos favorables que integran al evento $\large A$ y el número de casos posibles. Del espacio muestral $\large \Omega$.  
De manera formal:
$$\large P_{(A)}=\frac{n_A}{k}$$
- $\large n_A$: 

Sea experimento aleatorio cuyo correspondiente espacio muestral $\large \Omega$ está formado  por un número $\large k$ finito de posibles resultados distintos. Y con la misma probabilidad de ocurrir $\large \Omega=\{\omega_1,\omega_2,...\omega_k\}$. Sí un evento $\large A$ está constituido por $\large n_A$ elementos de $\large \Omega$ .  

> [!note] 1900
> Esta definición de probabilidad fue una de las primeras que se dieron de manera formal. Se atribuye a Laplace.  
  
## Subjetiva
Bajo este enfoque, cada persona le atribuye una cierta probabilidad a cada evento, basándose en experiencias similares al evento en cuestión. 

## Restringida
Sea $A$ y $B$ de dos eventos, con $P(B) \gt 0$ de define:  
$P(A | B)\small \text{   Probabilidad de "A dado B"}$
Como:
$P(A|B)=\Huge\frac{P(A\cap B)}{P(B)}$
Regla de multiplicación
$P(A\cap B) = P(A|B)P(B)$
## Independencia (estadística)
$A$ es independiente de B sí:
$P(A|B) = P(A)$
Equivalencias:
1. $P(A|B) = P(A)$
2. $P(A\cap B) = P(A)P(B)$ <- $\small \text{Esta solo se puede usar cuando son independientes.}$
3. $P(B|A) = P(B)$
### Pasando de 1 a 3
Supongamos $P(A|B) = P(A)$ entonces:  
$P(A\cap B) = P(A|B)P(B)$
$P(A\cap B) = P(A)P(B)$
