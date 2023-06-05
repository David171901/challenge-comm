# Descripción de la Prueba Técnica:

La prueba técnica consiste en desarrollar una página web que muestre tres gráficos utilizando la librería "amCharts v3". Deberás utilizar las siguientes herramientas: JavaScript, CSS y HTML.

## Instrucciones de Maquetado:
1- Crea una estructura HTML básica con los elementos necesarios: doctype, etiquetas html, head y body.
2- En el head, agrega las referencias a los archivos CSS y JavaScript de amCharts v3. 
3- Dentro del body, crea un elemento header con el título "COMM PiVision".
4- A continuación, crea un contenedor para los gráficos. Este contenedor debe ocupar el 100% de la pantalla.
5- Utiliza CSS para dar estilo a la página y los elementos.

## Instrucciones para los gráficos:

Para la creación de los gráficos, utilizaremos la librería "amCharts v3". A continuación, se proporcionan los pasos y recursos necesarios:

Documentación:
La documentación completa de la librería "amCharts v3" está disponible en el siguiente enlace: https://docs.amcharts.com/3/javascriptcharts. 

Ejemplos:
Puedes acceder a los ejemplos en el siguiente enlace: https://www.amcharts.com/demos-v3/.

Descarga de la librería:
Puedes descargar la librería "amCharts v3" desde el siguiente enlace: https://www.amcharts.com/download-v3/. 

### Grafico N1:
Para crear el gráfico N1 utilizando el array de datos proporcionado (EventsN1), puedes seguir estos pasos:

1- Crea un nuevo array para almacenar los datos agrupados por nombre de evento y realiza la sumatoria de los valores correspondientes. Puedes utilizar un bucle for o funciones de manipulación de arrays para realizar esta tarea. 

2- Ahora, tienes un nuevo array que contiene los datos agrupados y listos para ser utilizados en el gráfico circular. 

3- Utiliza la librería "amCharts v3" para crear un gráfico circular y mostrar los datos. Puedes utilizar la documentación y ejemplos proporcionados en los enlaces mencionados anteriormente para obtener más información sobre cómo configurar y personalizar el gráfico.

(Opcional) Personaliza el aspecto visual del gráfico según tus preferencias utilizando las opciones y configuraciones disponibles en la librería. Puedes definir colores, etiquetas, leyendas y otros elementos visuales para mejorar la presentación del gráfico.

Ejemplo: https://www.amcharts.com/demos-v3/simple-pie-chart-v3/

### Grafico N2:
Para crear el gráfico N2 utilizando el array de datos proporcionado (WindmillN1), puedes seguir estos pasos:


Ejemplo: https://www.amcharts.com/demos-v3/angular-gauge-v3/

1- Crea un nuevo array vacío para almacenar los datos agrupados por día. Puedes utilizar un bucle for o funciones de manipulación de arrays para realizar esta tarea.

2- Crea un nuevo array para almacenar los datos maximos por dia. Puedes utilizar un bucle for o funciones de manipulación de arrays para realizar esta tarea.

3- Al finalizar el bucle, tendrás un array con los valores máximos agrupados por día.

4- Calcula el promedio de todos los valores máximos obtenidos en el paso anterior. Puedes recorrer los grupos y sumar todos los valores máximos, luego dividir entre la cantidad de valores para obtener el promedio.

5- Adapta el resultado para que pueda utilizarse en un gráfico Gauge de la librería amCharts v3. En el caso del gráfico Gauge, necesitarás un objeto con una propiedad value que represente el valor promedio obtenido en el paso anterior.

Utiliza la librería amCharts v3 para crear un gráfico Gauge y mostrar el valor promedio. Puedes utilizar la documentación y ejemplos proporcionados en los enlaces mencionados anteriormente para obtener más información sobre cómo configurar y personalizar el gráfico.

(Opcional) Personaliza el aspecto visual del gráfico según tus preferencias utilizando las opciones y configuraciones disponibles en la librería. Puedes definir colores, etiquetas, rangos y otros elementos visuales para mejorar la presentación del gráfico Gauge.

Ejemplo: https://www.amcharts.com/demos-v3/angular-gauge-v3/

### Grafico N3 (Extra):
Para elaborar el gráfico de barras utilizando la biblioteca AmCharts v3 a partir de los datos proporcionados (WindmillN2), puedes seguir los siguientes pasos:

1- Crea un nuevo array vacío para almacenar los datos agrupados por día. Puedes utilizar un bucle for o funciones de manipulación de arrays para realizar esta tarea.

2-Al finalizar el bucle, tendrás un array con los datos agrupados por día. Cada grupo contendrá todos los valores correspondientes a ese día.

3- Calcula el valor promedio para cada día. Puedes recorrer los grupos y sumar todos los valores, luego dividir entre la cantidad de valores para obtener el promedio.

4- Adapta los valores para que sean aptos con el gráfico de barras de la librería amCharts v3. 

5- Utiliza la librería amCharts v3 para crear un gráfico de barras y mostrar los valores promedio por dia. Puedes utilizar la documentación y ejemplos proporcionados en los enlaces mencionados anteriormente para obtener más información sobre cómo configurar y personalizar el gráfico.

(Opcional) Personaliza el aspecto visual del gráfico según tus preferencias utilizando las opciones y configuraciones disponibles en la librería. Puedes definir colores, etiquetas, leyendas y otros elementos visuales para mejorar la presentación del gráfico.

Ejemplo: https://www.amcharts.com/demos-v3/column-with-rotated-series-v3/

#### Observacion

Para esta prueba técnica, es importante tener en cuenta que se valora la utilización de buenas prácticas en el desarrollo del código. Se recomienda utilizar variables con nombres descriptivos que faciliten la comprensión del código. Asimismo, es fundamental asegurarse de que el código sea legible y entendible, siguiendo las convenciones de estilo y estructura adecuadas.

Cabe destacar que el gráfico número 3, es considerado un extra en esta prueba técnica. Su implementación será valorada como un elemento adicional en el desarrollo. 