i $P(A)\geq 0$  
ii $P(\Omega)\ =\ 1$  
iii Si $A$ y $B$ son excluyentes, $P(A\cup B)\ =\ P(A)\ +\ P(B)$

> - La probabilidad de un evento es un número no negativo.
> - La probabilidad del espacio muestral es igual a 1.
> - Si dos eventos son excluyentes, la probabilidad de la unión de los dos eventos es igual a la suma de las probabilidades de los dos eventos.

## Propiedades

- $P(A^c)\ =\ 1\ -\ P(A)$
- $P(A)\ \leq\ 1$
- $P(B-A)\ =\ P(B)\ -\ P(A\cap B)$
- $P(A\cup B)\ =\ P(A)\ +\ P(B)\ -\ P(A\cap B)$
# Demostración
## A
$P(\Omega)=1$ == $P(A\cup A^c)$
Cómo $A\cap A^c = 0$, entonces son excluyentes, y de iii
$P(A)+P(A^c)=1$
Así que:
$P(A^c)=1-P(A)$
## B
De i) $P(A)\geq 0$ o $P(A)\geq 0$  
De a) 
$1-P(A)\geq 0$
$1\geq P(A)$
$P(A) \leq 1$
## C
$P(B-A)=P(B) - P(B \cap A)$
$P(B-A)=P(B\cap A^c)$
$P(B)=P(B\cap \Omega)$
$P(B)=P(B\cap (A\cup A^c))$
$P(B)=P((B\cap A) \cup (B\cap A^c))$
$P(B)=P((B\cap A) \cup (B\cap A^c))$
Como $(B\cap A) \cap (B\cap A^c)$
$(A\cap A^c)\cap (B\cap B)$
$0 \cap B$
$0$
Al ser excluyentes podemos usar iii
$P(B)=P(B\cap A) + P(B\cap A^c)$
$P(B)=P(B\cap A) + P(B-A)$
Así $P(B-A)=P(B)-P(B\cap A)$
## D
$A\cup (B-A) = A\cup (B\cap A^c)$
$A\cup (B-A) = (A\cup B)\cap (A\cup A^c)$
$A\cup (B-A) = (A\cup B)\cap \Omega$
$A\cup (B-A) = (A\cup B)$
Por lo tanto
$P(A\cup B) = P(A\cup (B-A))$
Revisamos que sean excluyentes $A\cup (B-A)$
$A\cap (B-A)=A\cap (B\cap A^c)$
$A\cap (B-A)=B\cap (A\cap A^c)$
$A\cap (B-A)=B\cap 0$
$A\cap (B-A)=0 \text{ Por lo que si son excluyentes}$
A si con iii)
$P(A\cup B) = P(A+(B-A))$
$P(A\cup B) = P(A)+P(B)+P(B\cap A)$
$P(A\cup B) = P(A)+P(B)+P(A\cap B)$

# Ejemplo
Sean $A$ y $B$ eventos tales que $P(A)=0.65$ $P(B)=0.23$ y $P(A\cap B)=0.08$.
Calcule $P(A\cup B)\ P(A-B)\ P(A^c\cap B^c)$ 