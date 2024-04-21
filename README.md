# PAC2 - Visualització de dades

**José Ignacio Funes Castillo**  
**Fecha:** 2023-04-20  

## Tipos de Gráficos

### 3.1. Gráfico de líneas

#### 3.1.1 Origen
El gráfico de líneas es una de las formas más antiguas de representar datos. Fue creado por William Playfair en el siglo XVIII. Según la fuente encontrada en el [INE (Instituto Nacional de Estadística)](https://www.ine.es/expo_graficos2010/expogra_autor2.htm).

#### 3.1.2 Descripción/Funcionamiento
Este tipo de gráfico utiliza líneas para conectar puntos de datos en un eje de coordenadas, generalmente representando una variable en el eje y y otra en el eje x (aunque puede haber más ejes). Se utiliza principalmente para mostrar tendencias y cambios a lo largo del tiempo.

#### 3.1.3 Aplicaciones
Puede ser utilizado en una variedad de campos, como finanzas (por ejemplo, para mostrar el rendimiento de acciones) y análisis de datos en general. [Fuente de la imagen](https://datavizcatalogue.com/ES/metodos/grafica_de_linea.html).

### 3.2. Gauge diagram

#### 3.2.1 Origen
Los diagramas de medidores han sido utilizados durante décadas en diversas áreas, desde la ingeniería hasta el diseño de los indicadores del cuadro de mando de automóviles.

#### 3.2.2 Descripción/Funcionamiento
Este tipo de diagrama representa datos mediante una escala circular, con una aguja que señala un valor específico en esta escala. Se utiliza para mostrar el rendimiento o la posición de una variable en relación con unos ciertos límites o estándares. Según la [fuente](https://www.ibm.com/docs/en/cognos-analytics/11.1.0?topic=types-gauge-charts).

#### 3.2.3 Aplicaciones
Los paneles de automóviles que muestran la velocidad del vehículo son un ejemplo clásico de diagramas de medidores. También se pueden encontrar en paneles de control de fábricas para indicar el rendimiento de la maquinaria, o en paneles de control de software para mostrar métricas clave de rendimiento. [Fuente de la imagen](https://www.phdata.io/blog/how-to-use-the-gauge-chart-template/).

### 3.3. UpSet: Visualizando Conjuntos Intersectados

#### 3.3.1 Origen
El método UpSet fue propuesto en un artículo de investigación titulado "UpSet: Visualization of Intersecting Sets" por Alexander Lex, Nils Gehlenborg y Hendrik Strobelt, publicado en 2014. DOI: [10.1109/TVCG.2014.2346248](https://doi.org/10.1109/TVCG.2014.2346248).

#### 3.3.2 Descripción/Funcionamiento
UpSet es una técnica de visualización diseñada para mostrar conjuntos de datos y sus intersecciones. Consiste en una matriz de barras horizontales que representan los conjuntos de datos, y las intersecciones entre ellos se muestran como barras verticales conectadas. Esta técnica es útil para comprender la interacción entre diferentes conjuntos de datos y para identificar patrones de intersección.

#### 3.3.3 Aplicaciones
Se utiliza en bioinformática para visualizar la intersección de conjuntos de genes o proteínas en diferentes condiciones experimentales. También puede ser útil en análisis de datos sociales para visualizar la intersección de conjuntos de usuarios en redes sociales, entre otros campos. [Fuente de la imagen](https://upload.wikimedia.org/wikipedia/commons/4/44/Upset_Plot.png).

## Tipos de Datos y Estructuras

### 4.1. Gráfico de líneas

Los gráficos de líneas son ideales para representar datos cuantitativos que pueden ser medidos en una escala numérica, como cantidades, medidas o valores a lo largo del tiempo u otro tipo de serie. No obstante, también pueden ser utilizados para datos cualitativos si se asigna un valor numérico a cada categoría.

Se recomienda tener una estructura de datos en forma de pares de valores (x, y), donde "x" representa la variable independiente (por ejemplo, el tiempo) y "y" representa la variable dependiente (por ejemplo, la medida o cantidad).

No hay una limitación estricta en cuanto al tamaño del conjunto de datos para un gráfico de líneas. No obstante, a medida que aumenta el número de puntos de datos, la legibilidad del gráfico puede disminuir.

### 4.2. Gauge diagram

Los diagramas de medidores son más adecuados para representar datos cuantitativos, especialmente cuando se quiere mostrar la posición de una variable en relación con ciertos límites o estándares.

Se necesita un solo valor numérico que se quiere representar en el medidor, junto con los límites o estándares asociados.

No hay una limitación estricta en cuanto al tamaño del conjunto de datos para un diagrama de medidores. No obstante, debido a su naturaleza compacta y simplificada, son más efectivos cuando se utilizan para representar un solo valor o métrica
