**LABORATORIO 1**

*TEXT MINING & IMAGE RECOGNITION*

**Problema 1:** (carpeta PARIS 2024)
Desarrolle una función la cual reciba dos parámetros, una imagen y un entero llamado color, la
función debe devolver una imagen la cual tenga activos los canales de color según los siguientes
puntos:
- Si el parámetro color vale 1, la imagen debe mostrar activos únicamente el color azul.
- Si el parámetro color vale 2, la imagen debe mostrar activos únicamente el color verde.
- Si el parámetro color vale 3, la imagen debe mostrar activos únicamente el color rojo.
- Si el parámetro color vale 10, la imagen debe mostrar activos únicamente los colores rojo y
  verde.
- Si el parámetro color vale 20, la imagen debe mostrar activos unicamente los colores verde y
azul.
- Si el parámetro color vale 30, la imagen debe mostrar activos unicamente los colores azul y
rojo.

**Problema 2:** (Carpeta IMAGEN 1, IMAGEN 2, PERRO)
En el .zip del laboratorio se le compartió un conjunto de imágenes en escala de grises (imagen1,
imagen2, perro) estas imágenes fueron creadas utilizando una escala de grises en 3D, cree una
funcion que dadas las 3 imágenes se construya la imagen original a color.

**Problema 3:** (Carpeta Simpsons)
Cree una función que dada una imagen cree una escala de grises en tres dimensiones, tome en
cuenta que su función debe crear 3 imágenes como salida. Para entregar este ejercicio debe incluir
una las imágenes que haya utilizado como prueba y el resultado de las misma, no puede utilizar la
imagen del Problema #2.

**Problema 4:** 
Cree una función que dada una imagen, muestre el histograma de cada canal de color y el de
escala de grises (utilice un promedio aritmético para su escala de grises, no puede usar funciones
de opencv), sus histogramas deben incluir una línea vertical la cual muestre el valor de la media
de la distribución.

**Problema 5:** (Carpeta Simpsons)
Investigue en que consiste el enfoque de escala de grises ponderado, luego de esto implemente una
función que dada una imagen, realice una escala de grises ponderada (notar que no existe una
solución única).

**Problema 6:**
Investigue brevemente en que consiste el espacio de color HSV y como se mapean colores a dicho
espacio, para entregar este ejercicio puede hacerlo por medio de Markdown en el mismo Notebook
donde trabajó los demás ejercicios.
