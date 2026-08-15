---
rank:
destacado: true
destacado_en:
  - "[[index]]"
---

# DNS
Domain Name Service (Servicio de Nombres de Dominio). Es un [[#servidor]] que traduce la dirección alfanumérica de otro servidor (por ejemplo "localhost") a dirección numérica (por ejemplo 127.0.0.1). Es utilizado ampliamente en internet pues los humanos solemos recordar más los nombres que los números de dirección, en especial cuando estos son muchos, como en las direcciones del protocolo IPv6.

# HTML
Hyper-Text Markup Language (lenguaje de marcado para hipertexto), es un tipo de archivo estándar y un lenguaje para hipertextos en el que su sintaxis permite incluir archivos multimedia y ligas o vínculos a otro media e hipertextos. Su estandarización permitió que muchas grupos generaran [[#navegador|navegadores]] que entienden este lenguaje. Puede haber programas que generen archivos html, ejecutados por el servidor aunque estos tengan tipos diversos. Así que aunque la [[#URL]] no indique un recurso html, el resultado aún será descrito por este lenguaje.

# HTTP
Hyper-Text Transfer Protocol (protocolo de transferencia de hipertexto) es un protocolo para acceder a recursos de hipertexto (texto que puede incluir imágenes, sonidos y ligas o vínculos a otros hipertextos). Se se suele asociar a las siglas WWW de World Wide Web "telaraña (red de araña) mundial" o solo "web", pues fue lo que hizo inmensamente popular al internet, tanto que actualmente se piensa que son lo mismo (aunque no es así). También se le suele asociar a recursos [[#HTML|html]] pues es el principal lenguaje para recursos en linea.

# navegador
Programa que permite visualizar [[#HTML|hipertextos]] almacenados en [[#servidor|servidores]] a los que se accede mediante direcciones [[#URL]]. Entre los iniciales se encuentran Netscape que sobrevive internamente en la base de muchos navegadores actuales con el nombre de Mozilla. Entre los populares actualmente (2026) se encuentran Chrome, Internet Explorer, Safari, Dia

# servidor
Coloquialmente es como se le llama a la computadora (hardware) que contiene información como sitio web o de otro tipo. Sin embargo de manera más precisa es el programa (software) que provee tal información almacenado en un hardware (o varios) para dicho propósito.
# URL
Uniform Resource Location (dirección de recurso uniforme). Es una forma estandarizada de referirse a un "recurso" (por lo general es un archivo, pero puede ser una conexión), por ejemplo en http://google.com se indica con [[#HTTP|http]] y "google.com" es la dirección [[#DNS]] del [[#servidor]]. Si no se le da un nombre de recurso (nombre de archivo) específico después del nombre del servidor, este tiene "defaults" descritos en su configuración como por ejemplo el archivo "index.html" (aunque pueden ser muchos otros). Así por ejemplo http://google.com/index.html puede ser equivalente a http://google.com/.
En el siguiente ejemplo https://www.google.com/index.html?atvm=2 observamos que el protocolo a utilizar es http y la "s" es de "seguro", es decir, utiliza un mecanismo de "llave pública" para encriptar o codificar la información que recibe y envía al cliente (a nuestra máquina), de manera que solo nosotros veamos lo que pasa por ese canal de comunicación. Luego viene el nombre DNS del servidor "google.com" y el nombre del recurso, es este caso el archivo index.[[#HTML|html]] (el separador usado hasta ahora es "/"). A continuación se indican "variables" (después del "?") y de haber más se separan con "&", en este caso la variable "atmv" vale "2" y que sirven por ejemplo, para mandar a secciones o variantes del recurso. Cabe aclarar que algunos recursos pueden ser "dinámicos" es decir, pueden ser programas que generan hipertexto y no solo archivos estáticos de hipertexto, dichos archivos pueden o no usar la información que tu programa de navegador le mande y que puede incluir tu posición geográfica, tipo de navegador, tipo de computadora que usas, lenguaje, etc.