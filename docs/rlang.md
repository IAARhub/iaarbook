# Introducción a R

## ¿Qué es R?

[R](https://cloud.r-project.org/) es un lenguaje de programación [interpretado](https://es.wikipedia.org/wiki/Script) diseñado específicamente para el [análisis estadístico](http://relopezbriega.github.io/blog/2015/06/27/probabilidad-y-estadistica-con-python/) y la manipulación de datos. Esta inspirado, y es en su mayor medida compatible, por el lenguaje de programación <a href="https://en.wikipedia.org/wiki/S_(programming_language)">S</a> desarrollado por AT&T. Es ampliamente utilizado en todos los campos donde se deben manipular datos, como ser: los negocios, la industria, el gobierno, la medicina, el ámbito académico, y demás.

## ¿Por qué utilizar R?

[R](https://cloud.r-project.org/) cuenta con varias virtudes, como ser:

* Es una implementación de dominio público del lenguaje estadístico <a href="https://en.wikipedia.org/wiki/S_(programming_language)">S</a>; y la plataforma R/S se ha convertido en el defecto dentro del círculo de los profesionales de la [estadística](http://relopezbriega.github.io/blog/2015/06/27/probabilidad-y-estadistica-con-python/).

* Es comparable, y a menudo superior en funcionalidad a productos comerciales; ya sea en gráficas, variedad de operaciones, y algoritmos implementados.

* Es multiplataforma, se encuentra disponible para los sistemas operativos Windows, Mac y Linux.

* Además de proporcionar operaciones estadísticas, [R](https://cloud.r-project.org/) es un lenguaje de programación de propósito general; es decir, que puede ser utilizado para automatizar análisis y crear nuevas funciones que amplíen las funcionalidades existentes.

* Incorpora características encontradas en la programación [orientados a objetos](https://es.wikipedia.org/wiki/Programaci%C3%B3n_orientada_a_objetos) y [funcional](https://es.wikipedia.org/wiki/Programaci%C3%B3n_funcional).

* El sistema guarda los conjuntos de datos entre sesiones, por lo que no es necesario volver a cargar los datos cada vez que ingresamos. También guarda nuestro historial de comandos, lo que nos ahorra bastante tiempo y mejora la productividad.

* Debido a que [R](https://cloud.r-project.org/) es un software de [código abierto](https://es.wikipedia.org/wiki/C%C3%B3digo_abierto), es fácil obtener ayuda de la comunidad de usuarios. Además, muchas nuevas funciones son aportadas por los usuarios, los cuales son prominentes estadísticos.

Si bien existe una pequeña curva de aprendizaje, ésta es bastante mínima en comparación con otros lenguajes y programas. Asimismo existe una enorme red de colaboradores que constantemente están creando nuevos paquetes que hacen que sea mucho más fácil aplicar todo tipo de técnicas y funciones para manipular y analizar nuestros datos con la ayuda de [R](https://cloud.r-project.org/).

## ¿Cómo obtengo R?

Para descargar [R](https://cloud.r-project.org/), deben dirigirse a [CRAN](https://cran.r-project.org/), la red de archivos de [R](https://cloud.r-project.org/). [CRAN](https://cran.r-project.org/) se compone de un conjunto de servidores distribuidos en todo el mundo y se utiliza para distribuir [R](https://cloud.r-project.org/) junto con sus paquetes.

## RStudio

[RStudio](https://www.rstudio.com/) es un entorno de desarrollo integrado, o [IDE](https://es.wikipedia.org/wiki/Entorno_de_desarrollo_integrado), diseñado específicamente para la programación con [R](https://cloud.r-project.org/). [RStudio](https://www.rstudio.com/) hace que [R](https://cloud.r-project.org/) sea más fácil de usar. Incluye un editor de código, herramientas de depuración y visualización. Si estas dando tus primeros pasos con [R](https://cloud.r-project.org/), [RStudio](https://www.rstudio.com/) hace la experiencia mucho más amigable.

## Librerías para Ciencia de datos

Bien, luego de este paseo por las principales estructuras de datos que podemos encontrar en [R](https://cloud.r-project.org/), llegó el momento de adentrarnos en el fascinante mundo de la ciencia de datos. Algunas de las librerías que se han vuelto sumamente útiles para analizar y manipular datos con [R](https://cloud.r-project.org/), son las siguientes:

### Tidyverse

Una de las tareas más importantes en cualquier proceso de análisis de datos consiste en ordenarlos y darles una estructura. En general recibimos datos en crudo y debemos procesarlos para poder luego utilizarlos en nuestros modelos. Si de explorar, ordenar y analizar datos se trata el paquete [tidiverse](https://cran.r-project.org/web/packages/tidyverse/index.html) es fundamental. Este paquete incluye las librerías ggplot2, tibble, tidyr, readr, purrr, y dplyr; las cuales comparten una filosofía propia y están diseñados para trabajar naturalmente entre ellos.

### Caret

A la hora de simplificar el proceso de [Machine Learning](http://relopezbriega.github.io/blog/2015/10/10/machine-learning-con-python/), el paquete [Caret](https://cran.r-project.org/web/packages/caret/) puede sernos de gran ayuda. Este paquete nos ofrece una serie de herramientas para la construcción de modelos de [Machine Learning](http://relopezbriega.github.io/blog/2015/10/10/machine-learning-con-python/) en [R](https://cloud.r-project.org/). [Caret](https://cran.r-project.org/web/packages/caret/) nos proporciona herramientas esenciales para: la etapa de preparación de los datos, para dividir el conjunto de datos, seleccionar los principales atributos, y para evaluar los modelos.

### Data.table

Si de organizar grandes volúmenes de datos de una manera intuitiva se trata, [data.table](https://cran.r-project.org/web/packages/data.table/index.html) es el paquete indicado. Esta librería nos extiende la estructura de datos del dataFrame para poder trabajar con archivos realmente extensos, y poder realizar operaciones de agregado, agrupado y uniones de una forma más sencilla.

## Otras librerías que deberíamos conocer

### E1071

Si lo que buscamos es trabajar con [Máquinas de vectores de soporte, SVM](https://es.wikipedia.org/wiki/M%C3%A1quinas_de_vectores_de_soporte); o con cualquiera de las principales funciones que podemos encontrar en las clases de probabilidad y estadística; entonces el paquete [E1071](https://cran.r-project.org/web/packages/e1071/) es exactamente lo que necesitamos. 

### randomForest

Para trabajar específicamente con modelos de [Random Forest](https://es.wikipedia.org/wiki/Random_forest) el paquete [randomForest](https://cran.r-project.org/web/packages/randomForest/) puede ser una buena opción; este paquete nos permite crear este tipo de modelos en forma muy sencilla.

### rpart

El paquete [rpart](https://cran.r-project.org/web/packages/rpart/) es una buena alternativa para trabajar con árboles de clasificaciones. Implementa los principales algoritmos para trabajar con este tipo de modelos.

### nnet

Las [redes neuronales](http://relopezbriega.github.io/category/redes-neuronales.html) han recibido mucha atención últimamente por sus habilidades para *aprender* las relaciones entre las variables. Representan una técnica innovadora para la adaptación de los modelo que no se basa en los supuestos convencionales necesarios por el modelado estándar; y que además pueden manejar muy eficazmente los datos multivariantes. Un gran paquete para trabajar con [redes neuronales](http://relopezbriega.github.io/category/redes-neuronales.html) en forma muy sencilla es [nnet](https://cran.r-project.org/web/packages/nnet/).

### igraph

Si lo que necesitamos es analizar y visualizar redes y grafos, el paquete [igraph](https://cran.r-project.org/web/packages/igraph/) es la mejor opción. Este paquete nos proporciona una serie de rutinas altamente eficientes para visualizar y analizar las conexiones de las redes. 

### Outliers

Si lo que necesitamos es encontrar valores atípicos, entonces [outliers](https://cran.r-project.org/web/packages/outliers/index.html) es el paquete que debemos utilizar. Esta librería nos ofrece varias funciones y tests para poder identificar los valores atípicos.   

### Survival

[Survival](https://cran.r-project.org/web/packages/survival/index.html) es un paquete que nos facilita la tarea de realizar [análisis de supervivencia](https://es.wikipedia.org/wiki/An%C3%A1lisis_de_la_supervivencia). 

### Forecast

[Forecast](https://cran.r-project.org/web/packages/forecast/) proporciona métodos y herramientas para mostrar y analizar predicciones univariadas de [series de tiempo](http://relopezbriega.github.io/blog/2016/09/26/series-de-tiempo-con-python/), incluyendo el suavizado exponencial a través de modelos de espacios de estados y el modelado [ARIMA](https://es.wikipedia.org/wiki/Modelo_autorregresivo_integrado_de_media_m%C3%B3vil) automático.
