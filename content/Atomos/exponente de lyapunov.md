---
aliases:
tags:
  - átomo
Temas:
  - Complejidad
Número de página:
rank: 4
destacado:
destacado_en:
---

#investigar
El exponente de Lyapunov mide la velocidad de divergencia de una [[órbita]], por lo que implica comparar el límite de la razón entre dos valores consecutivos de esta.

(def. mas formal)


## Para mapeos
- definición de caos?
- Como cuantificar la dependencia en las condiciones iniciales en un sistema dinámico [[caos|caótico]]? exp. de lyapunov
- Sistemas dinámicos discretos
- Sea $x_0$ una condición inicial y sea $x_0+d_0$ un punto cercano, así $d_n$ es la separación de la orbita de $x_0$ de la de $x_0+d_0$.
- Si $|d_n|\approx |d_0|e^{n\lambda}$, entonces $\lambda$ es el *exponente de Lyapunov*.
- $\lambda>0$ es un indicativo de caos.
- $d_n=f^n(x_0+d_0)-f^n(x_0)$ por lo que entonces $\lambda\approx\frac{1}{n}\ln|\frac{d_n}{d_0}| = \frac{1}{n}\ln|\frac{f^n(x_0+d_0)-f^n(x_0)}{d_0}| = \frac{1}{n}\ln|(f^n)'(x_0)|$ 
- Pero $(f^n)'(x_0) = \Pi_{i=0}^{n-1}f'(x_i)$
- Por tanto $\lambda\approx \frac{1}{n}\ln|\Pi_{i=0}^{n-1}f'(x_i)| = \frac{1}{n}\sum_{i=0}^{n-1}\ln|f'(x_i)|$
- Exponente: $\lambda=\lim_{n\rightarrow\infty}\frac{1}{n}\sum_{i=0}^{n-1}\ln|f'(x_i)|$
- Promedio de encogimientos o estiramientos de la separación en la orbita



 Si $|d_n|\approx |d_0|e^{n\lambda}$, entonces $\lambda$ es el *exponente de Lyapunov*.
- $\lambda>0$ es un indicativo de caos.
- $d_n=x_n-x_{n-1}$ por lo que entonces $\lambda\approx\frac{1}{n}\ln|\frac{d_n}{d_0}| = \frac{1}{n}\ln|\frac{x_n-x_{n-1}}{d_0}| = \frac{1}{n}\ln|(f^n)'(x_0)|$ 
- Pero $(f^n)'(x_0) = \Pi_{i=0}^{n-1}f'(x_i)$
- Por tanto $\lambda\approx \frac{1}{n}\ln|\Pi_{i=0}^{n-1}f'(x_i)| = \frac{1}{n}\sum_{i=0}^{n-1}\ln|f'(x_i)|$
- Exponente: $\lambda=\lim_{n\rightarrow\infty}\frac{1}{n}\sum_{i=0}^{n-1}\ln|f'(x_i)|$
- Promedio de encogimientos o estiramientos de la separación en la orbita

---
- caos
- caos y orden
- caos y azar
- caos espacial y caos temporal
- caos y filosofía
	- cognocibilidad del universo
- caos determinista y caos probabilista
- gráfica del exponente de Lyapunov
- serie de tiempo
- periodo 3