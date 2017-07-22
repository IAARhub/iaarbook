Summary:Libro online de la comunidad de Inteligencia Artificial Argentina IAAR - Visión por computadora. ¿Qué es la visión por computadora?. Aplicaciones de la visión por computadora. Redes neuronales convolucionales. OpenCV. 

# Visión por Computadora

<center><img src="https://iaarbook.github.io/img/computer-vision.jpg" title="Visión artificial" alt="Visión artificial" width="80%" height="80%"></center>

De nuestros cinco sentidos, la *visión* es sin duda uno de los más importantes y uno de los que más dependemos. Hay quienes dicen incluso, que los ojos son una ventana hacia nuestro cerebro; ya que alrededor del 50 % de las áreas de nuestro cerebro se utilizan en funciones para procesar la gran cantidad de información que ingresa a través de nuestra vista.

En cierto sentido se podría decir que la *visión* es, en primer lugar, una tarea de procesamiento de información; pero a si mismo, es algo mucho más complejo, ya que para poder saber que es lo qué hay en el mundo nuestros cerebros deben ser capaces de *representar* esta información en toda su abundancia de color, forma, movimiento, detalle y belleza. El estudio de la *visión* debe entonces incluir, no solo el estudio de cómo extraer de las imágenes los diversos aspectos del mundo que nos son útiles, sino también una investigación sobre la naturaleza de las representaciones internas mediante las cuales captamos esta información y la utilizamos como base para las decisiones sobre nuestros pensamientos y acciones. Esta dualidad, de *representación* y *procesamiento de información* esta en el corazón de la mayoría de las tareas de procesamiento de la información y se profundizará más en el estudio de los problemas relacionados con la [Visión por computadora](https://es.wikipedia.org/wiki/Visi%C3%B3n_artificial). 

## ¿Qué es la visión por computadora?

Hoy en día, podemos encontrar imágenes y videos por todas partes. Los sitios para compartir videos y las redes sociales los tienen por billones. Prácticamente todos los teléfonos móviles y computadoras poseen cámaras incorporadas. Es muy común que las personas tengan varios giga-bytes de fotos y videos en sus dispositivos. Programar una computadora y diseñar los [algoritmos](https://iaarbook.github.io/glosario/#Algoritmo) para entender qué hay en esas fotos y videos, es el campo de estudio de la [Visión por computadora](https://es.wikipedia.org/wiki/Visi%C3%B3n_artificial) o [Computer vision](https://es.wikipedia.org/wiki/Visi%C3%B3n_artificial).

La [Visión por computadora](https://es.wikipedia.org/wiki/Visi%C3%B3n_artificial) consiste en la extracción automatizada de información de las imágenes. Por información podemos entender casi cualquier cosa; desde modelos 3D, posición de la cámara, reconocimiento de objetos, y agrupación y búsqueda de contenido. También puede incluir la deformación de las imágenes, la eliminación de ruidos y la realidad aumentada. Muchas veces la [Visión por computadora](https://es.wikipedia.org/wiki/Visi%C3%B3n_artificial) trata de imitar a la visión humana, pero otras ves la geometría o un enfoque más estadístico puede ser fundamental para resolver un problema. La [Visión por computadora](https://es.wikipedia.org/wiki/Visi%C3%B3n_artificial) contiene una mezcla de programación, modelado y matemática que lo convierte en un campo de estudio sumamente atractivo. 

## Aplicaciones de visión por computadora

La [Visión por computadora](https://es.wikipedia.org/wiki/Visi%C3%B3n_artificial) es un área con más de 40 años de investigación, por lo que ya contamos con varias aplicaciones de las técnicas desarrolladas. Estas aplicaciones incluyen:

* **[Reconocimiento óptico de caracteres (OCR)](https://es.wikipedia.org/wiki/Reconocimiento_%C3%B3ptico_de_caracteres)**: Que consiste en la identificación automáticamente a partir de una imagen de símbolos o caracteres que pertenecen a un determinado alfabeto, para luego almacenarlos en forma de datos.

* **Inspección robotizada**: La inspección rápida de las piezas para garantizar la calidad de los componentes de fabricación utilizando una visión estéreo con iluminación especializada. 

* **Venta al por menor**: Como ser los clásicos lectores de barras que encontramos en los supermercados para reconocer los precios de los productos en la línea de cajas. 

* **Construcción de modelos 3D**: La construcción automatizada de modelos 3D a partir de fotografías. 

* **Imágenes médicas**: Como ser la tecnología utilizada para tomar radiografías y las técnicas para detectar tumores malignos y anomalías en las mismas. 

* **Seguridad automotriz**: Ayudando a detectar obstáculos mediante un sistema de conducción asistida utilizando diferentes cámaras.    

* **Captura de movimiento**: Utilizando marcadores retro-reflexivos vistos desde múltiples cámaras u otras técnicas para la captura de movimientos de los actores para utilizar en [animación por computadora](https://es.wikipedia.org/wiki/Animaci%C3%B3n_por_computadora).

* **Vigilancia**: Monitoreo de intrusos, análisis del tráfico vial, y monitoreo de piscinas para víctimas de ahogamiento. 

* **Reconocimiento de huellas dactilares y biometría**: Para la identificación automática de accesos y también utilizada para aplicaciones forenses.

* **Detección de caras**: Utilizado para mejorar el foco de las cámaras y para hacer una búsqueda más relevante de personas en imágenes. 

Como estas, existen muchas más aplicaciones de las técnicas de [Visión por computadora](https://es.wikipedia.org/wiki/Visi%C3%B3n_artificial); muchas de las cuales son algo ya común para nosotros, como la sugerencia para etiquetar de Facebook. 


## Redes neuronales convolucionales 

Gracias a que el área del cerebro responsable de la [visión](https://es.wikipedia.org/wiki/Visi%C3%B3n) es una de las zonas más estudiadas y que más conocemos; sabemos que la [corteza visual](https://es.wikipedia.org/wiki/Corteza_visual) contiene una disposición jerárquica compleja de [neuronas](https://es.wikipedia.org/wiki/Neurona).  Por ejemplo, la información visual es introducida en la corteza a través del área visual primaria, llamada V1. Las [neuronas](https://es.wikipedia.org/wiki/Neurona) de V1 se ocupan de características visuales de bajo nivel, tales como pequeños segmentos de contorno, componentes de pequeña escala del movimiento, [disparidad binocular](https://es.wikipedia.org/wiki/Disparidad_binocular), e información básica de contraste y color. V1 luego alimenta de información a otras áreas, como V2, V4 y V5. Cada una de estas áreas se ocupa de los aspectos más específicos o abstractas de la información. Por ejemplo, las [neuronas](https://es.wikipedia.org/wiki/Neurona) en V4 se ocupan de objetos de mediana complejidad, tales como formas de estrellas en diferentes colores. La [corteza visual](https://es.wikipedia.org/wiki/Corteza_visual) de los animales es el más potente sistema de procesamiento visual que conocemos, por lo que suena lógico inspirarse en ella para crear una variante de [redes neuronales artificiales](https://es.wikipedia.org/wiki/Red_neuronal_artificial) que ayude a identificar imágenes; es así como surgen las [redes neuronales convolucionales](http://relopezbriega.github.io/blog/2016/08/02/redes-neuronales-convolucionales-con-tensorflow/).

Las [redes neuronales convolucionales](http://relopezbriega.github.io/blog/2016/08/02/redes-neuronales-convolucionales-con-tensorflow/) se componen de [neuronas](https://es.wikipedia.org/wiki/Neurona) que tienen *pesos* y *sesgos* que pueden aprender. Cada [neurona](https://es.wikipedia.org/wiki/Neurona) recibe algunas entradas, realiza un [producto escalar](https://es.wikipedia.org/wiki/Producto_escalar) y luego aplica una función de activación. Lo que diferencia a las [redes neuronales convolucionales](http://relopezbriega.github.io/blog/2016/08/02/redes-neuronales-convolucionales-con-tensorflow/) es que suponen explícitamente que las entradas son imágenes, lo que nos permite codificar ciertas propiedades en la arquitectura; permitiendo ganar en eficiencia y reducir la cantidad de parámetros en la red. Las [redes neuronales convolucionales](http://relopezbriega.github.io/blog/2016/08/02/redes-neuronales-convolucionales-con-tensorflow/) trabajan modelando de forma consecutiva pequeñas piezas de información, y luego combinando esta información en las capas más profundas de la red. Una manera de entenderlas es que la primera capa intentará detectar los bordes y establecer patrones de detección de bordes. Luego, las capas posteriores trataran de combinarlos en formas más simples y, finalmente, en patrones de las diferentes posiciones de los objetos, iluminación, escalas, etc. Las capas finales intentarán hacer coincidir una imagen de entrada con todos los patrones y arribar a una predicción final como una suma ponderada de todos ellos. De esta forma las [redes neuronales convolucionales](http://relopezbriega.github.io/blog/2016/08/02/redes-neuronales-convolucionales-con-tensorflow/) son capaces de modelar complejas variaciones y comportamientos dando predicciones bastantes precisas.

### Estructura de las Redes Neuronales Convolucionales

En general, las [redes neuronales convolucionales](http://relopezbriega.github.io/blog/2016/08/02/redes-neuronales-convolucionales-con-tensorflow/) van a estar construidas con una estructura que contendrá 3 tipos distintos de capas:

#### Capa convolucional

Esta es la capa que le nombre a la red, lo que distingue a las [redes neuronales convolucionales](http://relopezbriega.github.io/blog/2016/08/02/redes-neuronales-convolucionales-con-tensorflow/) de cualquier otra [red neuronal](https://es.wikipedia.org/wiki/Red_neuronal_artificial) es utilizan un operación llamada [convolución](https://es.wikipedia.org/wiki/Convoluci%C3%B3n) en alguna de sus capas; en lugar de utilizar la multiplicación de matrices que se aplica generalmente.
La operación de [convolución](https://es.wikipedia.org/wiki/Convoluci%C3%B3n) recibe como *entrada o input* la imagen y luego aplica sobre ella un *filtro o kernel* que nos devuelve un *mapa de las características* de la imagen original, de esta forma logramos reducir el tamaño de los parámetros.
La [convolución](https://es.wikipedia.org/wiki/Convoluci%C3%B3n) aprovecha tres ideas importantes que pueden ayudar a mejorar cualquier sistema de [Machine Learning](https://iaarbook.github.io/machine-learning/), ellas son: 
* **interacciones dispersas**, ya que al aplicar un filtro de menor tamaño sobre la entrada original podemos reducir drásticamente la cantidad de parámetros y cálculos;
* los **parámetros compartidos**, que hace referencia a compartir los parámetros entre los distintos tipos de filtros, ayudando también a mejorar la eficiencia del sistema; y las **representaciones equivariante**, que indican que si las entradas cambian, las salidas van a cambiar también en forma similar. 

Por otra parte, la [convolución](https://es.wikipedia.org/wiki/Convoluci%C3%B3n) proporciona un medio para trabajar con entradas de tamaño variable, lo que puede ser también muy conveniente.

<img alt="Convolución" title="Convolución" src="http://relopezbriega.github.io/images/conv_layer.png">


#### Capa de reducción o pooling

La capa de reducción o *pooling* se coloca generalmente después de la capa *convolucional*. Su utilidad principal radica en la reducción de las dimensiones espaciales (ancho x alto) del volumen de entrada para la siguiente capa *convolucional*. No afecta a la dimensión de profundidad del volumen.
La operación realizada por esta capa también se llama *reducción de muestreo*, ya que la reducción de tamaño conduce también a la pérdida de información. Sin embargo, una pérdida de este tipo puede ser beneficioso para la red por dos razones:

* la disminución en el tamaño conduce a una menor sobrecarga de cálculo para las próximas capas de la red;
* también trabaja para reducir el [sobreajuste](http://relopezbriega.github.io/blog/2016/05/29/machine-learning-con-python-sobreajuste/).

La operación que se suele utilizar en esta capa es *max-pooling*, que divide a la imagen de entrada en un conjunto de rectángulos y, respecto de cada subregión, se va quedando con el máximo valor.

<img alt="max pooling" title="max pooling" src="http://relopezbriega.github.io/images/Max_pooling.png">


#### Capa clasificadora totalmente conectada

Al final de las capas *convolucional* y de *pooling*, las redes utilizan generalmente capas completamente conectados en la que cada pixel se considera como una [neurona](https://es.wikipedia.org/wiki/Neurona) separada al igual que en una [red neuronal](https://es.wikipedia.org/wiki/Red_neuronal_artificial) regular. Esta última capa clasificadora tendrá tantas [neuronas](https://es.wikipedia.org/wiki/Neurona) como el número de clases que se debe predecir.

Los modelos de [Deep Learning](https://iaarbook.github.io/deeplearning/) basados en [redes neuronales convolucionales](http://relopezbriega.github.io/blog/2016/08/02/redes-neuronales-convolucionales-con-tensorflow/) han logrado resultados sorprendentes en varios problemas de [Visión por computadora](https://es.wikipedia.org/wiki/Visi%C3%B3n_artificial), como ser los casos de clasificación de imágenes y detección de objetos. 

## OpenCV

[OpenCV](http://opencv.org/) es una librería [Open Source](https://iaarbook.github.io/glosario/#OpenSource) de [Visión por computadora](https://es.wikipedia.org/wiki/Visi%C3%B3n_artificial) que nos permite manipular imágenes y videos para realizar una variedad de tareas que van desde la detección automática de caras, a la visualización de las imágenes de una cámara Web; o hasta enseñarle a un robot a reconocer objetos en la vida real. Fue creada en 1999, por Gary Bradski, quien trabajaba en [Intel](https://www.intel.la/content/www/xl/es/homepage.html), y que lanzó [OpenCV](http://opencv.org/) con la intensión de acelerar la [Visión por computadora](https://es.wikipedia.org/wiki/Visi%C3%B3n_artificial) y la [Inteligencia Artificial](https://iaarbook.github.io/inteligencia-artificial/) proporcionando una infraestructura sólida para todos los que trabajan en el campo. La librería está escrita en <a href="http://es.wikipedia.org/wiki/C_(lenguaje_de_programaci%C3%B3n)">C</a> y [C++](http://es.wikipedia.org/wiki/C%2B%2B) y se puede ejecutar bajo [Linux](https://www.linuxfoundation.org/), Windows y Mac OS X. Posee un desarrollo activo de interfaces para [Python](https://iaarbook.github.io/python/), <a href="http://es.wikipedia.org/wiki/Java_(lenguaje_de_programaci%C3%B3n)">Java</a> , MATLAB y otros lenguajes, incluyendo el soporte para plataformas como [Android](https://www.android.com/) e iOS para aplicaciones móviles. 

[OpenCV](http://opencv.org/) contiene más de 500 funciones que abarcan muchas áreas de [Visión por computadora](https://es.wikipedia.org/wiki/Visi%C3%B3n_artificial), incluyendo tales como: inspección de productos de fábrica, imágenes médicas, seguridad, interfaz de usuario, calibración de cámara, visión estéreo y robótica. Debido a que la [Visión por computadora](https://es.wikipedia.org/wiki/Visi%C3%B3n_artificial) y el [Machine Learning](https://iaarbook.github.io/machine-learning/) a menudo van de la mano, [OpenCV](http://opencv.org/) también contiene una librería completa de uso general de [Machine Learning](https://iaarbook.github.io/machine-learning/) (ML); la cual se centra en el reconocimiento de patrones estadísticos y el agrupamiento. [OpenCV](http://opencv.org/) es sin dudas el lugar por dónde comenzar para empezar a incursionar en el mundo de la [Visión por computadora](https://es.wikipedia.org/wiki/Visi%C3%B3n_artificial). 
