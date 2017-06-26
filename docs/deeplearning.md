# Introducción al Deep Learning

<center><img src="https://iaarhub.github.io/images/Inteligencia-Artificial-Deep-Learning.jpg" title="Deep Learning" alt="Deep Learning"></center>

El [Deep Learning](https://es.wikipedia.org/wiki/Aprendizaje_profundo) es sin duda el área de investigación más popular dentro del campo de la [inteligencia artificial](https://iaarhub.github.io/capacitacion/2017/04/30/introduccion-a-la-inteligencia-artificial/). La mayoría de las nuevas investigaciones que se realizan, trabajan con modelos basados en las técnicas de [Deep Learning](https://es.wikipedia.org/wiki/Aprendizaje_profundo); ya que las mismas han logrado resultados sorprendes en campos como [Procesamiento del lenguaje natural](https://es.wikipedia.org/wiki/Procesamiento_de_lenguajes_naturales) y [Visión por computadora](https://es.wikipedia.org/wiki/Visi%C3%B3n_artificial). Pero... ¿qué es este misterioso concepto que ha ganado tanta popularidad? y... ¿cómo se relaciona con el campo de la [inteligencia artificial](https://iaarhub.github.io/capacitacion/2017/04/30/introduccion-a-la-inteligencia-artificial/) y el [Machine Learning](http://relopezbriega.github.io/category/machine-learning.html)?. 

### Inteligencia artificial, Machine learning y Deep learning <a name="IA-ML-DL"></a>

En general se suelen utilizar los términos de [inteligencia artificial](https://iaarhub.github.io/capacitacion/2017/04/30/introduccion-a-la-inteligencia-artificial/), [Machine Learning](http://relopezbriega.github.io/category/machine-learning.html) y [Deep Learning](https://es.wikipedia.org/wiki/Aprendizaje_profundo) en forma intercambiada. Sin embargo, éstos términos no son los mismo y abarcan distintas cosas. 

#### Inteligencia Artificial

El término [inteligencia artificial](https://iaarhub.github.io/capacitacion/2017/04/30/introduccion-a-la-inteligencia-artificial/) es el más general y engloba a los campos de [Machine Learning](http://relopezbriega.github.io/category/machine-learning.html) y [Deep Learning](https://es.wikipedia.org/wiki/Aprendizaje_profundo) junto con otras técnicas como los [algoritmos de búsqueda](https://es.wikipedia.org/wiki/Algoritmo_de_b%C3%BAsqueda), el [razonamiento simbólico](https://es.wikipedia.org/wiki/Inteligencia_artificial_simb%C3%B3lica), el [razonamiento lógico](https://en.wikipedia.org/wiki/Logical_reasoning) y la [estadística](http://relopezbriega.github.io/category/pobabilidad-y-estadistica.html). Nació en los años 1950s, cuando un grupo de pioneros de la computación comenzaron a preguntarse si se podía hacer que las computadoras *pensaran*. Una definición concisa de la [inteligencia artificial](https://iaarhub.github.io/capacitacion/2017/04/30/introduccion-a-la-inteligencia-artificial/) sería: *el esfuerzo para automatizar las tareas intelectuales que normalmente realizan los seres humanos*. 

#### Machine Learning

El [Machine Learning](http://relopezbriega.github.io/category/machine-learning.html) o [Aprendizaje automático](http://relopezbriega.github.io/category/machine-learning.html) se refiere a un amplio conjunto de técnicas informáticas que nos permiten dar a las computadoras *la capacidad de aprender sin ser explícitamente programadas*. Hay muchos tipos diferentes de algoritmos de [Aprendizaje automático](http://relopezbriega.github.io/category/machine-learning.html), entre los que se encuentran el [aprendizaje por refuerzo](https://es.wikipedia.org/wiki/Aprendizaje_por_refuerzo), los [algoritmos genéticos](https://es.wikipedia.org/wiki/Algoritmo_gen%C3%A9tico), el aprendizaje basado en [reglas de asociación](https://es.wikipedia.org/wiki/Reglas_de_asociaci%C3%B3n), los [algoritmos de agrupamiento](https://es.wikipedia.org/wiki/Algoritmo_de_agrupamiento), los [árboles de decisión](https://es.wikipedia.org/wiki/%C3%81rbol_de_decisi%C3%B3n), las [máquinas de vectores de soporte](https://es.wikipedia.org/wiki/M%C3%A1quinas_de_vectores_de_soporte) y las [redes neuronales](https://es.wikipedia.org/wiki/Red_neuronal_artificial). Actualmente, los algoritmos más populares dentro de este campo son los de [Deep Learning](https://es.wikipedia.org/wiki/Aprendizaje_profundo).

#### Deep Learning

El [Deep Learning](https://es.wikipedia.org/wiki/Aprendizaje_profundo) o [aprendizaje profundo](https://es.wikipedia.org/wiki/Aprendizaje_profundo) es un subcampo dentro del [Machine Learning](http://relopezbriega.github.io/category/machine-learning.html), el cuál utiliza distintas estructuras de [redes neuronales](https://es.wikipedia.org/wiki/Red_neuronal_artificial) para lograr el aprendizaje de sucesivas *capas de representaciones* cada vez más significativas de los datos. El *profundo* o *deep* en [Deep Learning](https://es.wikipedia.org/wiki/Aprendizaje_profundo) hace referencia a la cantidad de *capas de representaciones* que se utilizan en el modelo; en general se suelen utilizar decenas o incluso cientos de *capas de representación*. las cuales *aprenden* automaticamente a medida que el modelo es entrenado con los datos.

<img src="https://iaarhub.github.io/images/DL.png" title="Deep Learning" alt="Deep Learning">

## ¿Qué es el Deep Learning? <a name="Que-es-DL"></a>

Antes de poder entender que es el [Deep Learning](https://es.wikipedia.org/wiki/Aprendizaje_profundo), debemos en primer lugar conocer dos conceptos fundamentales: las [redes neuronales artificiales](https://es.wikipedia.org/wiki/Red_neuronal_artificial) y la [Propagación hacia atrás](https://es.wikipedia.org/wiki/Propagaci%C3%B3n_hacia_atr%C3%A1s).


### Redes Neuronales 

Las [redes neuronales](https://es.wikipedia.org/wiki/Red_neuronal_artificial) son un modelo computacional basado en un gran conjunto de unidades neuronales simples ([neuronas artificiales](https://es.wikipedia.org/wiki/Neurona_de_McCulloch-Pitts)), de forma aproximadamente análoga al comportamiento observado en los axones de las neuronas en los cerebros biológicos. 

Cada una de estas neuronas simples, va a tener una forma similar al siguiente diagrama:

<img src="https://relopezbriega.github.io/images/neurona.png">

En donde sus componentes son:

* $x_1, x_2, \dots, x_n$: Los datos de entrada en la neurona, los cuales también puede ser que sean producto de la salida de otra neurona de la red.

* $x_0$: La unidad de sesgo; un valor constante que se le suma a la entrada de la función de activación de la neurona. Generalmente tiene el valor 1. Este valor va a permitir cambiar la función de activación hacia la derecha o izquierda, otorgándole más flexibilidad para aprender a la neurona.

* $w_0, w_1, w_2, \dots, w_n$: Los pesos relativos de cada entrada. Tener en cuenta que incluso la unidad de sesgo tiene un peso.

* a: La salida de la neurona. Que va a ser calculada de la siguiente forma:

$$a = f\left(\sum_{i=0}^n w_i \cdot x_i \right)$$

Aquí $f$ es la ***función de activación*** de la neurona. Esta función es la que le otorga tanta flexibilidad a las [redes neuronales](https://es.wikipedia.org/wiki/Red_neuronal_artificial) y le permite estimar complejas relaciones no lineales en los datos. Puede ser tanto una [función lineal](https://es.wikipedia.org/wiki/Funci%C3%B3n_lineal), una [función logística](https://es.wikipedia.org/wiki/Funci%C3%B3n_log%C3%ADstica), [hiperbólica](https://es.wikipedia.org/wiki/Funci%C3%B3n_hiperb%C3%B3lica), etc.

Cada unidad neuronal está conectada con muchas otras y los enlaces entre ellas pueden incrementar o inhibir el estado de activación de las neuronas adyacentes. Estos sistemas aprenden y se forman a sí mismos, en lugar de ser programados de forma explícita, y sobresalen en áreas donde la detección de soluciones o características es difícil de expresar con la programación convencional.

<img src="https://iaarhub.github.io/images/neural_network.svg">


### Propagación hacia atrás 

La [propagación hacia atrás](https://es.wikipedia.org/wiki/Propagaci%C3%B3n_hacia_atr%C3%A1s) o [backpropagation](https://es.wikipedia.org/wiki/Propagaci%C3%B3n_hacia_atr%C3%A1s) es un algoritmo que funciona mediante la determinación de la pérdida (o error) en la salida y luego propagándolo de nuevo hacia atrás en la red. De esta forma los pesos se van actualizando para minimizar el error resultante de cada neurona. Este algoritmo es lo que les permite a las [redes neuronales](https://es.wikipedia.org/wiki/Red_neuronal_artificial) aprender.

<img src="https://iaarhub.github.io/images/backprop.png" title="Backprop" alt="Backprop" width="50%" height="50%">


### ¿Cómo funciona el Deep Learning?  <a name="como-funciona-DL"></a>

En general, cualquier técnica de [Machine Learning](http://relopezbriega.github.io/category/machine-learning.html) trata de realizar la asignación de entradas (por ejemplo, imágenes) a salidas objetivo (Por ejemplo, la etiqueta "gato"), mediante la observación de un gran número de ejemplos de entradas y salidas. El [Deep Learning](https://es.wikipedia.org/wiki/Aprendizaje_profundo) realiza este mapeo de entrada-a-objetivo por medio de una [red neuronal artificial](https://es.wikipedia.org/wiki/Red_neuronal_artificial) que está compuesta de un número grande de *capas* dispuestas en forma de jerarquía. La [red](https://es.wikipedia.org/wiki/Red_neuronal_artificial) aprende algo simple en la capa inicial de la jerarquía y luego envía esta información a la siguiente capa. La siguiente capa toma esta información simple, lo combina en algo que es un poco más complejo, y lo pasa a la tercer capa. Este proceso continúa de forma tal que cada capa de la jerarquía construye algo más complejo de la entrada que recibió de la capa anterior. De esta forma, la [red](https://es.wikipedia.org/wiki/Red_neuronal_artificial) irá *aprendiendo* por medio de la exposición a los datos de ejemplo.

La especificación de lo que cada *capa* hace a la entrada que recibe es almacenada en los *pesos* de la capa, que en esencia, no son más que números. Utilizando terminología más técnica podemos decir que la transformación de datos que se produce en la *capa* es *parametrizada* por sus *pesos*. Para que la [red](https://es.wikipedia.org/wiki/Red_neuronal_artificial) aprenda debemos encontrar los *pesos* de todas las *capas* de forma tal que la [red](https://es.wikipedia.org/wiki/Red_neuronal_artificial) realice un mapeo perfecto entre los ejemplos de entrada con sus respectivas salidas objetivo. Pero el problema reside en que una [red](https://es.wikipedia.org/wiki/Red_neuronal_artificial) de [Deep Learning](https://es.wikipedia.org/wiki/Aprendizaje_profundo) puede tener millones de *parámetros*, por lo que encontrar el valor correcto de todos ellos puede ser una tarea realmente muy difícil, especialmente si la modificación del valor de uno de ellos afecta a todos los demás.

<img src="https://iaarhub.github.io/images/DL1.png" title="Deep Learning" alt="Deep Learning">

Para poder controlar algo, en primer lugar debemos poder observarlo. En este sentido, para controlar la salida de la [red neuronal](https://es.wikipedia.org/wiki/Red_neuronal_artificial), deberíamos poder medir cuan lejos esta la salida que obtuvimos de la que se esperaba obtener. Este es el trabajo de la *[función de pérdida](https://en.wikipedia.org/wiki/Loss_functions_for_classification)* de la [red](https://es.wikipedia.org/wiki/Red_neuronal_artificial). Esta función toma las predicciones que realiza el modelo y los valores objetivos (lo que realmente esperamos que la [red](https://es.wikipedia.org/wiki/Red_neuronal_artificial) produzca), y calcula cuán lejos estamos de ese valor, de esta manera, podemos capturar que tan bien esta funcionando el modelo para el ejemplo especificado. El truco fundamental del [Deep Learning](https://es.wikipedia.org/wiki/Aprendizaje_profundo) es utilizar el valor que nos devuelve esta  *[función de pérdida](https://en.wikipedia.org/wiki/Loss_functions_for_classification)* para retroalimentar la  [red](https://es.wikipedia.org/wiki/Red_neuronal_artificial) y ajustar los *pesos* en la dirección que vayan reduciendo la *pérdida* del modelo para cada ejemplo. Este ajuste, es el trabajo del *optimizador*, el cuál implementa la [propagación hacia atrás](https://es.wikipedia.org/wiki/Propagaci%C3%B3n_hacia_atr%C3%A1s). 

<img src="https://iaarhub.github.io/images/DL3.png" title="Deep Learning" alt="Deep Learning">

Resumiendo, el funcionamiento sería el siguiente: inicialmente, los *pesos* de cada *capa* son asignados en forma aleatoria, por lo que la [red](https://es.wikipedia.org/wiki/Red_neuronal_artificial) simplemente implementa una serie de transformaciones aleatorias. En este primer paso, obviamente la salida del modelo dista bastante del ideal que deseamos obtener, por lo que el valor de la *[función de pérdida](https://en.wikipedia.org/wiki/Loss_functions_for_classification)* va a ser bastante alto. Pero a medida que la [red](https://es.wikipedia.org/wiki/Red_neuronal_artificial) va procesando nuevos casos, los *pesos* se van ajustando de forma tal de ir reduciendo cada vez más el valor de la *[función de pérdida](https://en.wikipedia.org/wiki/Loss_functions_for_classification)*. Este proceso es el que se conoce como *entrenamiento* de la [red](https://es.wikipedia.org/wiki/Red_neuronal_artificial), el cual repetido una suficiente cantidad de veces, generalmente 10 iteraciones de miles de ejemplos, logra que los *pesos* se ajusten a los que minimizan la *[función de pérdida](https://en.wikipedia.org/wiki/Loss_functions_for_classification)*. Una [red](https://es.wikipedia.org/wiki/Red_neuronal_artificial) que ha minimizado la *pérdida* es la que logra los resultados que mejor se ajustan a las salidas objetivo, es decir, que el modelo se encuentra *entrenado*. 



## Arquitecturas de Deep Learning <a name="arquitectura-DL"></a>

La estructura de datos fundamental de una [red neuronal](https://es.wikipedia.org/wiki/Red_neuronal_artificial) está vagamente inspirada en el cerebro humano. Cada una de nuestras células cerebrales (neuronas) está conectada a muchas otras neuronas por sinapsis. A medida que experimentamos e interactuamos con el mundo, nuestro cerebro crea nuevas conexiones, refuerza algunas conexiones y debilita a los demás. De esta forma, en nuestro cerebro se desarrollan ciertas regiones que se especializan en el procesamiento de determinadas *entradas*. Así vamos a tener un área especializada en la visión, otra que se especializa en la audición, otra para el lenguaje, etc. De forma similar, dependiendo del tipo de *entradas* con las que trabajemos, van a existir distintas *arquitecturas* de [redes neuronales](https://es.wikipedia.org/wiki/Red_neuronal_artificial) que mejor se adaptan para procesar esa información. Algunas de las arquitecturas más populares son:

### Redes neuronales prealimentadas

Las [Redes neuronales prealimentadas](https://es.wikipedia.org/wiki/Red_neuronal_prealimentada) fueron las primeras que se desarrollaron y son el modelo más sencillo. En estas redes la información se mueve en una sola dirección: hacia adelante. Los principales exponentes de este tipo de arquitectura son el [perceptrón](https://es.wikipedia.org/wiki/Perceptr%C3%B3n) y el [perceptrón multicapa](https://es.wikipedia.org/wiki/Perceptr%C3%B3n_multicapa). Se suelen utilizar en problemas de clasificación simples. 

<img src="https://iaarhub.github.io/images/perceptron.png" title="Perceptrón multicapa" alt="Perceptrón multicapa">


### Redes neuronales convolucionales

Las [redes neuronales convolucionales](http://relopezbriega.github.io/blog/2016/08/02/redes-neuronales-convolucionales-con-tensorflow/) son muy similares a las [redes neuronales](https://es.wikipedia.org/wiki/Red_neuronal_artificial) ordinarias como el [perceptron multicapa](https://es.wikipedia.org/wiki/Perceptr%C3%B3n_multicapa); se componen de [neuronas](https://es.wikipedia.org/wiki/Neurona) que tienen *pesos* y *sesgos* que pueden aprender. Cada [neurona](https://es.wikipedia.org/wiki/Neurona) recibe algunas entradas, realiza un [producto escalar](https://es.wikipedia.org/wiki/Producto_escalar) y luego aplica una función de activación. Al igual que en el [perceptron multicapa](https://es.wikipedia.org/wiki/Perceptr%C3%B3n_multicapa) también vamos a tener una *función de pérdida o costo* sobre la última capa, la cual estará totalmente conectada. Lo que diferencia a las [redes neuronales convolucionales](http://relopezbriega.github.io/blog/2016/08/02/redes-neuronales-convolucionales-con-tensorflow/) es que suponen explícitamente que las entradas son imágenes, lo que nos permite codificar ciertas propiedades en la arquitectura; permitiendo ganar en eficiencia y reducir la cantidad de parámetros en la red. 

En general, las [redes neuronales convolucionales](http://relopezbriega.github.io/blog/2016/08/02/redes-neuronales-convolucionales-con-tensorflow/) van a estar construidas con una estructura que contendrá 3 tipos distintos de capas:

1. Una capa [convolucional](https://es.wikipedia.org/wiki/Convoluci%C3%B3n), que es la que le da le nombre a la red.
2. Una capa de reducción o de *pooling*, la cual va a reducir la cantidad de parámetros al quedarse con las características más comunes.
3. Una capa clasificadora totalmente conectada, la cual nos va dar el resultado final de la red.

Algunas implementaciones específicas que podemos encontrar sobre este tipo de redes son: [inception v3](https://keras.io/applications/#inceptionv3), [ResNet](https://keras.io/applications/#resnet50), [VGG16](https://keras.io/applications/#vgg16) y [xception](https://keras.io/applications/#xception), entre otras. Todas ellas han logrado excelentes resultados.

<img src="https://iaarhub.github.io/images/cnn.png" title="Redes neuronales convolucionales" alt="Redes neuronales convolucionales" width="70%" height="70%">

### Redes neuronales recurrentes

Los seres humanos no comenzamos nuestro pensamiento desde cero cada segundo, sino que los mismos tienen una persistencia. Las [Redes neuronales prealimentadas](https://es.wikipedia.org/wiki/Red_neuronal_prealimentada) tradicionales no cuentan con esta persistencia, y esto parece una deficiencia importante. Las [Redes neuronales recurrentes](https://en.wikipedia.org/wiki/Recurrent_neural_network) abordan este problema. Son redes con bucles de retroalimentación, que permiten que la información persista.

Una [Red neural recurrente](https://es.wikipedia.org/wiki/Red_neuronal_prealimentada) puede ser pensada como una red con múltiples copias de ella misma, en las que cada una de ellas pasa un mensaje a su sucesor. Esta naturaleza en forma de cadena revela que las [Redes neurales recurrentes](https://es.wikipedia.org/wiki/Red_neuronal_prealimentada) están íntimamente relacionadas con las secuencias y listas; por lo que son ideales para trabajar con este tipo de datos. En los últimos años, ha habido un éxito increíble aplicando [Redes neurales recurrentes](https://es.wikipedia.org/wiki/Red_neuronal_prealimentada)  a una variedad de problemas como: reconocimiento de voz, modelado de lenguaje, traducción, subtítulos de imágenes y la lista continúa.

Las [redes de memoria de largo plazo a corto plazo](https://en.wikipedia.org/wiki/Long_short-term_memory) - generalmente llamadas [LSTMs](https://en.wikipedia.org/wiki/Long_short-term_memory) - son un tipo especial de [Redes neurales recurrentes](https://es.wikipedia.org/wiki/Red_neuronal_prealimentada), capaces de aprender dependencias a largo plazo. Ellas también tienen una estructura como cadena, pero el módulo de repetición tiene una estructura diferente. En lugar de tener una sola capa de red neuronal, tiene cuatro, que interactúan de una manera especial permitiendo tener una memoria a más largo plazo.

<img src="https://iaarhub.github.io/images/rnn.png" title="Redes neuronales recurrentes" alt="Redes neuronales recurrentes" width="50%" height="50%">

Para más información sobre diferentes arquitecturas de [redes neuronales](https://es.wikipedia.org/wiki/Red_neuronal_artificial) pueden visitar el siguiente artículo de [wikipedia](https://en.wikipedia.org/wiki/Types_of_artificial_neural_networks).

## Logros del Deep Learning <a name="logros-DL"></a>

En los últimos años el [Deep Learning](https://es.wikipedia.org/wiki/Aprendizaje_profundo) ha producido toda una revolución en el campo del [Machine Learning](http://relopezbriega.github.io/category/machine-learning.html), con resultados notables en todos los problemas de *percepción*, como *ver* y *escuchar*, problemas que implican habilidades que parecen muy naturales e intuitivas para los seres humanos, pero que desde hace tiempo se han mostrado difíciles para las máquinas. En particular, el [Deep Learning](https://es.wikipedia.org/wiki/Aprendizaje_profundo) ha logrado los siguientes avances, todos ellos en áreas históricamente difíciles del [Machine Learning](http://relopezbriega.github.io/category/machine-learning.html).

* Un nivel casi humano para la clasificación de imágenes.
* Un nivel casi humano para el reconocimiento del lenguaje hablado.
* Un nivel casi humano en el reconocimiento de escritura.
* Grandes mejoras en traducciones de lenguas.
* Grandes mejoras en conversaciones *text-to-speech*.
* Asistentes digitales como Google Now o Siri.
* Un nivel casi humano en autos autónomos.
* Mejores resultados de búsqueda en la web.
* Grandes mejoras para responder preguntas en lenguaje natural.
* Alcanzado Nivel maestro (superior al humano) en varios juegos.

En muchos sentidos, el [Deep Learning](https://es.wikipedia.org/wiki/Aprendizaje_profundo) todavía sigue siendo un campo misterioso para explorar, por lo que seguramente veremos nuevos avances en nuevas áreas utilizando estas técnicas. Tal vez algún día el [Deep Learning](https://es.wikipedia.org/wiki/Aprendizaje_profundo) ayuda a los seres humanos a hacer ciencia, desarrollar software y mucho más.

## ¿Por qué estos sorprendentes resultados surgen ahora?  <a name="por-que-ahora-DL"></a>

Muchos de los conceptos del [Deep Learning](https://es.wikipedia.org/wiki/Aprendizaje_profundo) se desarrollaron en los años 80s y 90s, algunos incluso mucho antes. Sin embargo, los primeros resultados exitosos del [Deep Learning](https://es.wikipedia.org/wiki/Aprendizaje_profundo) surgieron en los últimos 5 años. ¿qué fue lo que cambio para lograr la popularidad y éxito de los modelos basados en [Deep Learning](https://es.wikipedia.org/wiki/Aprendizaje_profundo) en estos últimos años? 

Si bien existen múltiples factores para explicar esta *revolución* del [Deep Learning](https://es.wikipedia.org/wiki/Aprendizaje_profundo), los dos principales componentes parecen ser la **disponibilidad de masivos volúmenes de datos**, lo que actualmente se conoce bajo el nombre de [Big Data](https://es.wikipedia.org/wiki/Big_data); y el **progreso en el poder de computo**, especialmente gracias a los [GPUs](https://es.wikipedia.org/wiki/Unidad_de_procesamiento_gr%C3%A1fico). Entonces, dentro de los factores que explican esta popularidad de los modelos de [Deep Learning](https://es.wikipedia.org/wiki/Aprendizaje_profundo) podemos encontrar:

* **La disponibilidad de conjuntos de datos enormes y de buena calidad**. Gracias a la  revolución digital en que nos encontramos, podemos generar conjuntos de datos enormes con los cuales alimentar a los algoritmos de [Deep Learning](https://es.wikipedia.org/wiki/Aprendizaje_profundo), los cuales necesitan de muchos datos para poder *generalizar*.

* **Computación paralela masiva con [GPUs](https://es.wikipedia.org/wiki/Unidad_de_procesamiento_gr%C3%A1fico)**. En líneas generales, los modelos de [redes neuronales](http://relopezbriega.github.io/category/redes-neuronales.html) no son más que complicados cálculos numéricos que se realizan en paralelo. Gracias al desarrollo de los [GPUs](https://es.wikipedia.org/wiki/Unidad_de_procesamiento_gr%C3%A1fico) estos cálculos ahora se pueden realizar en forma mucho más rápida, permitiendo que podamos entrenar modelos más profundos y grandes. 

* **Funciones de activación amigables para [Backpropagation](https://es.wikipedia.org/wiki/Propagaci%C3%B3n_hacia_atr%C3%A1s)**. La [progación hacia atrás](https://es.wikipedia.org/wiki/Propagaci%C3%B3n_hacia_atr%C3%A1s) o [Backpropagation](https://es.wikipedia.org/wiki/Propagaci%C3%B3n_hacia_atr%C3%A1s) es el algoritmo fundamental que hace funcionar a las [redes neuronales](http://relopezbriega.github.io/category/redes-neuronales.html); pero la forma en que trabaja implica cálculos realmente complicados. La transición desde funciones de activación como `tanh` o `sigmoid` a funciones como <a href="https://en.wikipedia.org/wiki/Rectifier_(neural_networks)">ReLU</a> o [SELU](https://arxiv.org/abs/1706.02515) han simplificado estos problemas. 

* **Nuevas arquitecturas**. Arquitecturas como [Resnets](https://arxiv.org/abs/1512.03385), [inception](https://www.cs.unc.edu/~wliu/papers/GoogLeNet.pdf) y [GAN](https://en.wikipedia.org/wiki/Generative_adversarial_networks) mantienen el campo actualizado y continúan aumentando las flexibilidad de los modelos. 

* **Nuevas técnicas de <a href="https://en.wikipedia.org/wiki/Regularization_(mathematics)">regularización</a>**. Técnicas como <a href="https://en.wikipedia.org/wiki/Dropout_(neural_networks)">dropout</a>, [batch normalization](https://arxiv.org/abs/1502.03167) y [data-augmentation](https://arxiv.org/pdf/1609.08764.pdf) nos permiten entrenar redes más grandes con menos peligro de [sobreajuste](http://relopezbriega.github.io/blog/2016/05/29/machine-learning-con-python-sobreajuste/).

* **Optimizadores más robustos**. La [optimización](http://relopezbriega.github.io/blog/2017/01/18/problemas-de-optimizacion-con-python/) es fundamental para el funcionamiento de las [redes neuronales](http://relopezbriega.github.io/category/redes-neuronales.html). Mejoras sobre el tradicional procedimiento de [SGD](https://en.wikipedia.org/wiki/Stochastic_gradient_descent), como [ADAM](https://arxiv.org/pdf/1412.6980.pdf) han ayudado a mejorar el rendimiento de los modelos.

* **Plataformas de software**. Herramientas como [TensorFlow](https://www.tensorflow.org/), [Theano](http://deeplearning.net/software/theano/), [Keras](https://keras.io/), [CNTK](https://www.microsoft.com/en-us/research/product/cognitive-toolkit/), [PyTorch](http://pytorch.org/), [Chainer](https://chainer.org/), y [mxnet](http://mxnet.io/) nos permiten crear prototipos en forma más rápida y trabajar con [GPUs](https://es.wikipedia.org/wiki/Unidad_de_procesamiento_gr%C3%A1fico) sin tantas complicaciones. Nos permiten enfocarnos en la estructura del modelo sin tener que preocuparnos por los detalles de más bajo nivel.

Otra razón por la que el [Deep Learning](https://es.wikipedia.org/wiki/Aprendizaje_profundo) ha tenido tanta repercusión últimamente además de ofrecer un mejor rendimiento en muchos problemas; es que el [Deep Learning](https://es.wikipedia.org/wiki/Aprendizaje_profundo) esta haciendo la resolución de problemas mucho más fácil, ya que automatiza completamente lo que solía ser uno de los pasos más difíciles y cruciales en el flujo de trabajo de [Machine Learning](http://relopezbriega.github.io/category/machine-learning.html): la *[ingeniería de atributos](https://en.wikipedia.org/wiki/Feature_engineering)*. Antes del [Deep Learning](https://es.wikipedia.org/wiki/Aprendizaje_profundo), para poder entrenar un modelo, primero debíamos refinar las *entradas* para adaptarlas al tipo de transformación del modelo; teníamos que cuidadosamente [seleccionar los atributos](http://relopezbriega.github.io/blog/2016/04/15/ejemplo-de-machine-learning-con-python-seleccion-de-atributos/) más representativos y desechar los poco informativos. El [Deep Learning](https://es.wikipedia.org/wiki/Aprendizaje_profundo), en cambio, automatiza este proceso; aprendemos todos los atributos de una sola pasada y el mismo modelo se encarga de adaptarse y quedarse con lo más representativo.  

## ¿Cómo mantenerse actualizado en el campo de Deep Learning? <a name="actualizado-DL"></a>

El campo del [Deep Learning](https://es.wikipedia.org/wiki/Aprendizaje_profundo) se mueve muy rapidamente, con varios *papers* que se publican por mes; por tal motivo, mantenerse actualizado con las últimas tendencias del campo puede ser bastante complicado. Algunos consejos pueden ser:

* **Estarse atento a las publicaciones en [arxiv](https://arxiv.org/)**, especialmente a la sección de [machine learning](https://arxiv.org/list/stat.ML/recent). La mayoría de los *papers* más relevantes, los vamos a poder encontrar en esa plataforma.

* **Seguir el blog de [keras](https://blog.keras.io/)** en el cual podemos encontrar como implementar varios modelos utilizando esta genial librería.

* **Seguir el blog de [openai](https://blog.openai.com/)** en dónde detallan las investigaciones que van realizando, especialmente trabajando con [GANs](https://en.wikipedia.org/wiki/Generative_adversarial_networks).

* **Seguir el blog de [Google research](https://research.googleblog.com/)**; en dónde se viene haciendo bastante foco en los modelos de [Deep Learning](https://es.wikipedia.org/wiki/Aprendizaje_profundo).

* **Utilizar la sección de Machine Learning de [reddit](https://www.reddit.com/r/MachineLearning/)**.

* **Suscribirse al podcast [Talking machines](http://www.thetalkingmachines.com/)**; en dónde se entrevista a los principales exponentes del campo de la [inteligencia artificial](https://iaarhub.github.io/capacitacion/2017/04/30/introduccion-a-la-inteligencia-artificial/).

* Por último, obviamente estar atentos a las **publicaciones que se realizan en [IAAR](https://www.facebook.com/groups/InteligenciaArtificialArgentina/)**. 
