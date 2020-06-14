### Excel
#### Vector por escalar
Excel es un programa de pago de la empresa Microsoft, consiste en una _hoja de cálculo_ donde se puede representar un vector como una columna:

![](../img/excel/excel1.png)

Si se fijan, hay algunos números que aparecen al lado izquierdo y otros al lado derecho. Dependiendo de la configuración en excel, la separación de decimales va a ser o bien una coma o bien un punto. En sistemas en español suele venir como una coma, por lo que si queremos que excel entienda esos números, tenemos que cambiar los puntos por comas.

![](img/excel/excel2.png)

Vemos que ahora todos nuestro números están alineados a la derecha, este es el comportamiento que esperamos.


Ahora vamos a multiplicar la columna de variable independiente por 3.14. Para esto, primero hagamos que una celda tenga ese valor. Una vez hecho eso, creamos una nueva columna donde vamos a multiplicar la variable dependiente por el escalar y en la primera fila de la columna introducimos el siguiente texto: '=CPVD*$LCE$NCE' donde CPVD es la celda de la primera variable dependiente, LCE la letra de la celda del escalar y NCE es el número de la celda del escalar.

![](img/excel/excel3.png)

Una vez hecho eso, presione la tecla 'enter' y deberia aparecer el primer resultado como en la imágen anterior.

Ahora arrastre el punto verde de la primera celda de la columna de la multiplicacion del escalar con la variable dependiente

![](img/excel/excel4.gif)

#### Graficando

Para graficar los resultados excel tiene botones rápidos. Primero sosteniendo la tecla Ctrl en Windows o cmd en Mac seleccionamos las dos columnas que queremos graficar juntas, siempre primero seleccionamos la variable independiente y luego la dependiente.

![](img/excel/excel5.gif)


Una vez seleccionado vaya al menú insetar en las pestañas superiores, sobreponga su cursor en el botón de gráfico con puntos y seleccione dispersión

![](img/excel/excel6.png)

Al hacer click debería aparecerles un gráfico automático.

![](img/excel/excel7.png)

Ahora puede agregar los títulos de los ejes de la siguiente manera:
Primero seleccione el gráfico y vaya a _Diseño de gráfico_, luego _Agregar elemento de gráfico -> títulos de los ejes_ y marque ambos

![](img/excel/excel8.gif)


Ahora pueden cambiar tanto el título del gráfico como las etiquetas, dando doble click y escribiendo los nuevos títulos.

#### Importando datos en Excel

Lo primero que hacemos es abrir un nuevo archivo de Excel en blanco, luego hacemos click en ``Archivo>Importar`` y en la ventana que aparece seleccione ``Archivo de texto``

![](img/LTSpice/LTSpice2.gif)


Luego de esto les aparecerá una ventana donde tienen que selesccionar el archivo con los datos a importar. Luego aparecerá otra ventana en donde debe hecer click en ``Finalizar``.

![](img/LTSpice/LTSpice3.gif)


Con eso deberían tener los datos de esta manera


![](img/LTSpice/LTSpice2.png)
