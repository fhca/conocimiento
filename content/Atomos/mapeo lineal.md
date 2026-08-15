---
aliases:
tags:
  - átomo
URL:
Temas:
  - Complejidad
Número de página:
Creación de nota:
rank: 1
destacado:
destacado_en:
---

Ejemplo 1: Una recta horizontal $f(x)=k$ es demasiado simple y $f^n(x)=k$. Su órbita es $\{k,k,\ldots\}$.

![[Pasted image 20260815154130.png]]


Ejemplo 2: Una recta que pase por el origen $f(x)=kx$, iterada nos da: $f^2(x)=k(kx)=k^2x$, así $f^n(x)=k^nx$. Su [[convergencia]] es a 0 para $|k|<1$ (fig. 2), a $x$ para $k=1$ (fig. 3) y diverge para $|k|>1$ (fig. 4).

![[Pasted image 20260815154545.png]]

Ejemplo 3: Una recta que no pase por el origen $f(x)=kx+b$, al iterarla nos dará:

$$\begin{align}
kx+b,\\
k^2x+kb+b,\\
k^3x+k^2b+kb+b,\\
\ldots,\\
k^nx+B,\\
\ldots
\end{align}
$$
donde $B=\sum_{i=0}^{n-1}k^ib$. Lo que de nuevo converge para $|k|\le1$ y diverge en caso contrario.

En el programa [[diagrama de telaraña en Python]], usando la función "Linear" podemos ver el [[diagrama de telaraña]] de una recta que pasa por el punto $(0, 0.5)$. Variando $k$ en $[0, 4]$ obtenemos rectas con pendientes en $[-0.5, 0.5]$. Toda [[órbita]] tiene [[convergencia]] a un [[puntos fijos|punto fijo]] [[atractor]]. Para calcularlo usamos la ecuación $f(x)=x$ de esta manera:

$$\begin{align}
(k/4-0.5) * x + 0.5 =\;& x \\
x - (k/4-0.5) * x =\;& 0.5 \\
x =\;& 0.5 / (1.5 - k/4) \\
x =\;& 0.5 / ((6 - k)/4) \\
x =\;& 2 / (6 - k)
\end{align}$$
Por lo que al variar $k$ como se ha dicho, el punto fijo varia en $[\frac{1}{3}, 1]$, tal como se observa en el programa.

![[Pasted image 20260815154630.png]]
Nota: Obsérvese que este conjunto de rectas se escoge, una vez fijada la intersección en $(0, 0.5)$, de manera que si tomamos $k\in[0,4]$, siempre tenemos que $f(I)\subseteq I$, con $I=[0,1]$; lo cual es conveniente para poder iterar el mapeo y que la figura no se salga del cuadrado unitario. Esto es, necesitamos que $I$ sea [[invariante]] bajo el mapeo $f(x)$. 