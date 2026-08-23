---
aliases:
tags:
  - átomo
URL:
Temas:
  - Complejidad
Número de página:
rank: 1
destacado:
destacado_en:
---
Ya se ha visto el caso de que un [[mapeo]] [[convergencia|converja]] a un punto o valor. Sin embargo si no converge, nos va a interesar el caso cuando $\lim_{n\rightarrow\infty}f^n(x) = C$, para un conjunto de puntos $C$ llamado el *atractor* de $f$.
Esto último se puede escribir con la definición de límites de esta manera:
Dada cualquier $c\in C$, tenemos que $\forall\epsilon>0,\, \exists N\in \mathbb{N}$ tal que $\text{dist}(f^n(x),C)<\epsilon$ para toda $n\ge N$. Donde $\text{dist}(y,C) = \inf_{c\in C} |y-c|$, es decir, se acerca al conjunto completo.
Lo anterior se aplica a conjuntos arbitrarios de puntos, pero para fractales u otros atractores extraños, se usa la convergencia en el sentido de Hausdorff:
Dados dos conjuntos $A, B\subset\mathbb{R}^n$ (o $\mathbb{C}^n$), definimos la distancia de Hausdorff entre ellos como:
$$\text{dist}_H(A,B) = \max\{\sup_{a\in A}\inf_{b\in B}|a-b|,\,\sup_{b\in B}\inf_{a\in A}|b-a|\}$$
Así, $f^n(x)$ converge al conjunto $C$ en el sentido de Hausdorff si $\forall\epsilon>0, \exists N\in \mathbb{N}$ tal que $\text{dist}_H(f^n(x),C)<\epsilon$ para toda $n\ge N$.

---
- [[convergencia]]
- [[mapeo]]
- [[fractal]]
- [[atractor extraño]]
- [[órbita]]