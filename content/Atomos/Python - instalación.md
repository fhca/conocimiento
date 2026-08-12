---
aliases:
tags:
  - átomo
URL:
Temas:
  - "[[Programación]]"
  - "[[Python]]"
Número de página:
Creación de nota: 20250802
rank: 2
---

## Ejecutar Python sin instalar

![Colaboratory logo|100x50](https://upload.wikimedia.org/wikipedia/commons/thumb/9/9b/Google_Colab_pic.png/250px-Google_Colab_pic.png)
Esta es una opción mucho más cómoda, aunque para usarse depende de la disponibilidad de red. Con una cuenta de Google y conectándose a [Google Colaboratory](https://colab.google) se puede disponer de un ambiente de libretas tipo Jupyter (iPython) que corren en un servidor de la nube; teniéndose la posibilidad de conectarse con la cuenta (Google Drive) en dicho servidor y cuyos programas se guarda ahí.
![250px-Kaggle_Logo.svg.png|100x40](https://upload.wikimedia.org/wikipedia/commons/thumb/f/f4/Kaggle_Logo.svg/250px-Kaggle_Logo.svg.png)
Otra opción, que ya también es de Google, es [Kaggle](https://kaggle.com). Está orientada a análisis de datos y competencias con conjuntos de datos que ahí se encuentran o que se pueden subir. Solía ser más rápida que Colaboratory, pero hay que revisar su estado actual.
Finalmente, tanto [Anaconda](https://anaconda.com/app/) como [Jupyter](https://jupyter.org/try-jupyter/lab/) y otros sitios web, ponen a disposición páginas similares a Colaboratory, útiles para probar o poner demostraciones no tan grandes.
## Instalación
![Python logo|200](https://www.python.org/static/img/python-logo.png)
Hay varias formas de instalar [[Python]], la principal y más elemental es descargar el instalador desde https://python.org. Para ello, vamos a la pestaña `Downloads` y presionamos el botón amarillo de `Download Python (versión)`. Posteriormente se pueden instalar bibliotecas (paquetes o módulos) con el programa instalador `pip`. La desventaja es, quizás, que todo se tiene que hacer tecleando desde una terminal del sistema operativo. Sin embargo se tiene más control de esta forma.
![Anaconda logo|200](https://www.anaconda.com/wp-content/uploads/2024/11/Anaconda-Logo.png)
Otra manera es con Anaconda. Para ello se descarga el instalador desde https://anaconda.org. En la parte superior se selecciona `Download Anaconda`, se teclea una dirección de correo y se presiona el botón de `Submit`. Esto descargará no solo Python sino varias bibliotecas útiles a corto y mediano plazo. Prácticamente no se teclea nada y todo es con ratón. Sin embargo, la cantidad de bibliotecas que descarga puede ser muy grande, por lo que requiere bastante espacio.
Una opción para cuando se dispone de poco espacio es instalar `miniconda` desde la parte baja de la última página mencionada; que instala lo mínimo para que Anaconda funcione.
Tanto Anaconda como miniconda usan el instalador `conda` para sus bibliotecas.

Nota: los instaladores de python.org y de Anaconda no son compatibles y no se deberían mezclar, aunque se pueden tener ambos sistemas en una sola computadora, sabiendo identificar cual se está usando.
Cabe notar que es muy recomendable, para cualquiera de estas dos tipos de instalaciones, el uso de ambientes virtuales (venv, etc.)

Por último, también se puede descargar un IDE, con el que además de programar también se puede instalar Python y sus bibliotecas, incluyendo el uso de ambientes virtuales.
## IDEs
Los IDEs (Integrated Development Environment) son programas, ambientes de desarrollo integrado, donde se puede ejecutar Python "localmente", es decir, en la computadora propia en un ambiente de ventanas y con mínima necesidad de interacción con una terminal. La mayoría también son compatibles con ambientes virtuales. Algunos de los principales son:
- vscode
- Spyder
- Pycharm
- Jupyter
entre muchos otros.
Este último, Jupyter, comenzó como el proyecto iPython de "libretas" en las que en cada celda de trabajo se puede escribir una porción de código. Son muy cómodas pues pueden tener textos Markdown incluidos, para documentación, el código y los resultados juntos, incluyendo figuras. Son un poquito mas lentos que ejecutar los programas directamente o en otro IDE pero las ventajas superan con mucho las desventajas. Jupyter tiene su implementación independiente, pero también está agregado a casi todos los IDEs de Python.

