## Herramientas
La idea de las herramientas computacionales es facilitar cálculos que serían muy complejos o tediosos de hacer a mano. Además nos proporcionan la opción de graficar de manera precisa nuestros datos y ver cómo se comportan.

En esta guía básica veremos cómo utilizar 3 herramientas distintas:

  * Excel
  * Python
  * Octave

Para el caso de MATLAB ya existe una guía que estará disponible

Para cáda software haremos la misma tarea:
Dado un set de datos <img src="https://render.githubusercontent.com/render/math?math=\{(x_i, y_i)\}"> donde los <img src="https://render.githubusercontent.com/render/math?math=x_i"> corresponden a nuestra variable independiente (por ejemplo el tiempo) y nuestros <img src="https://render.githubusercontent.com/render/math?math=y_i"> son la variable dependiente (por ejemplo el voltaje).

Más concretamente usaremos los siguientes datos:

![](img/latex1.png)

Usaremos estos datos para operar vectores con escalares.

Cada uno de nuestros datos se puede ver como un vector <img src="https://render.githubusercontent.com/render/math?math=(x_i, y_i)"> donde <img src="https://render.githubusercontent.com/render/math?math=i \in \{0, 1, ..., N - 1\}">. En nuestro caso <img src="https://render.githubusercontent.com/render/math?math=N=10">

A su vez todos los datos de <img src="https://render.githubusercontent.com/render/math?math=x"> se pueden ver como un vector, tal como presentamos los datos anteriormente. Lo mismo es válido para los datos <img src="https://render.githubusercontent.com/render/math?math=y">. La gracia de esto es que ahora los podemos trabajar como todos los datos para la variable independiente por un lado, y todos los datos para la variable dependiente por otro.

Por lo general queremos trabajar los datos de la variable intependiente. Por lo que en este documento haremos lo siguiente:

  + Primero vamos a definir las variables según cada programa
  + Multiplicaremos la variable independiente por un escalar 3.14
  + Haremos un gráfico

Estos pasos los haremos en todos los programas
