---
aliases:
tags:
  - átomo
URL:
Temas:
  - Complejidad
Número de página:
Creación de nota:
rank: 4
destacado:
destacado_en:
---
La logística es una función ([[mapeo]]) que inicialmente se utilizó para modelar el crecimiento poblacional. En su versión diferencial, es decir, la razón de cambio de una etapa a la siguiente, se puede escribir como
$$f_k(x)=kx(1-x)$$
Aquí, $f_k:\textbf{R}\longrightarrow\textbf{R}$, es una función que toma un valor real y devuelve un valor real, donde el parámetro $k$ está entre 0 y 4 y por lo general la $x$ está entre 0 y 1.
A continuación graficamos la diagonal a 45º (en azul), la logística $f_4(x)$ en naranja y la logística en su segunda iteración, o sea $f_4(f_4(x))=f_4^2(x)$ en verde. Como se puede ver, este mapeo se complica bastante rápido. El valor para $k$ es 4 el cual veremos, más adelante, que tiene implicaciones especiales.
![[logística 1.png]]
[ver programa completo en Colab](https://colab.research.google.com/drive/1kTcSAZb9IOgqMa0sl72Fjl_lDi8qVJfq?usp=sharing)
[versión paso a paso](https://colab.research.google.com/drive/16YBf4L4p3htqMtj1zr8FvDE5zB8X-BwV?usp=sharing)

- [[logística - análisis de puntos fijos]]
- análisis caótico
- [[diagrama de telaraña]]
- diagrama de feigenbaum
- 