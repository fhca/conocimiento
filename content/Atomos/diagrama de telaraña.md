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

Es una forma gráfica de representar un [[mapeo]] $f(x):\textbf{R}\longrightarrow \textbf{R}$. Consiste en dibujar una diagonal a 45º sobre los ejes de coordenadas, fijándonos en especial en el intervalo sobre el eje $x$: $X=[\text{xmin}, \text{xmax}]$; donde $f(X)\subseteq X$. A continuación dibujar el mapeo de la siguiente manera:
1. Sea $i=0$
2. Supóngase que una ”araña” se sitúa inicialmente en el punto $(x_0, 0)$, con $x_0\in X$
3. La araña avanza verticalmente hasta el punto $(x_i, x_{i+1})$, con $x_{i+1}=f(x_i)$
4. La araña avanza horizontalmente hasta el punto $(x_{i+1},x_{i+1})$, que está sobre la diagonal
5. Hacer $i = i+1$ y repetir desde el paso 3

Programas de ejemplo:
- [diagrama de telaraña en Netlogo](logistica.nlogo)
- [diagrama de telaraña en Python](https://colab.research.google.com/drive/1cU-AvvgHt5v4WDELKHt1VLh7OZj3FkII)
