Summary:Libro online de la comunidad de Inteligencia Artificial Argentina IAAR - Fundamentos - Algebra lineal con python. Escalares, vectores, matrices, tensores, operaciones básicas, sistemas de ecuaciones lineales, programación lineal, librerías de python para algebra lineal, ejemplos en python

# Introducción al Álgebra lineal

<img alt="Algebra lineal" title="Algebra lineal" src="https://relopezbriega.github.io/images/lin-alg.jpg">"

## Introducción

## Introducción

Una de las herramientas matemáticas más utilizadas en [machine learning](https://es.wikipedia.org/wiki/Machine_learning) y [data mining](https://es.wikipedia.org/wiki/Miner%C3%ADa_de_datos) es el [Álgebra lineal](https://es.wikipedia.org/wiki/%C3%81lgebra_lineal); por tanto, si queremos incursionar en el fascinante mundo del aprendizaje automático y el análisis de datos es importante reforzar los conceptos que forman parte de sus cimientos. 

El [Álgebra lineal](https://es.wikipedia.org/wiki/%C3%81lgebra_lineal) es una rama de las [matemáticas](https://es.wikipedia.org/wiki/Matem%C3%A1ticas) que es sumamente utilizada en el estudio de una gran variedad de ciencias, como ser, ingeniería, finanzas, investigación operativa, entre otras. Es una extensión del [álgebra](https://es.wikipedia.org/wiki/%C3%81lgebra) que aprendemos en la escuela secundaria, hacia un mayor número de dimensiones; en lugar de trabajar con incógnitas a nivel de <a href="https://es.wikipedia.org/wiki/Escalar_(matem%C3%A1tica)">escalares</a> comenzamos a trabajar con <a href="https://es.wikipedia.org/wiki/Matriz_(matem%C3%A1ticas)">matrices</a> y [vectores](https://es.wikipedia.org/wiki/Vector).  

El estudio del [Álgebra lineal](https://es.wikipedia.org/wiki/%C3%81lgebra_lineal) implica trabajar con varios objetos matemáticos, como ser:

* **Los <a href="https://es.wikipedia.org/wiki/Escalar_(matem%C3%A1tica)">Escalares</a>**: Un *escalar* es un solo número, en contraste con la mayoría de los otros objetos estudiados en [Álgebra lineal](https://es.wikipedia.org/wiki/%C3%81lgebra_lineal), que son generalmente una colección de múltiples números.

* **Los [Vectores](https://es.wikipedia.org/wiki/Vector)**:Un *vector* es una serie de números. Los números tienen una orden preestablecido, y podemos identificar cada número individual por su índice en ese orden. Podemos pensar en los  *vectores* como la identificación de puntos en el espacio, con cada elemento que da la coordenada a lo largo de un eje diferente. Existen dos tipos de *vectores*, los *vectores de fila* y los *vectores de columna*. Podemos representarlos de la siguiente manera, dónde *f* es un vector de fila y *c* es un vector de columna:
$$f=\begin{bmatrix}0&1&-1\end{bmatrix} ;       c=\begin{bmatrix}0\\\1\\\ -1\end{bmatrix}$$

* **Las <a href="https://es.wikipedia.org/wiki/Matriz_(matem%C3%A1ticas)">Matrices</a>**: Una *matriz* es un arreglo bidimensional de números (llamados entradas de la matriz) ordenados en filas (o renglones) y columnas, donde una fila es cada una de las líneas horizontales de la matriz y una columna es cada una de las líneas verticales. En una *matriz* cada elemento puede ser identificado utilizando dos índices, uno para la fila y otro para la columna en que se encuentra. Las podemos representar de la siguiente manera, *A* es una matriz de 3x2.
$$A=\begin{bmatrix}0 & 1& \\\ -1 & 2 \\\ -2 & 3\end{bmatrix}$$

* **Los [Tensores](https://es.wikipedia.org/wiki/C%C3%A1lculo_tensorial)**:En algunos casos necesitaremos una matriz con más de dos ejes. En general, una serie de números dispuestos en una cuadrícula regular con un número variable de ejes es conocido como un *tensor*.

Sobre estos objetos podemos realizar las operaciones matemáticas básicas, como ser [adición](https://es.wikipedia.org/wiki/Adici%C3%B3n), [multiplicación](https://es.wikipedia.org/wiki/Multiplicaci%C3%B3n), [sustracción](https://es.wikipedia.org/wiki/Sustracci%C3%B3n) y <a href="https://es.wikipedia.org/wiki/Divisi%C3%B3n_(matem%C3%A1tica)" >división</a>, es decir que vamos a poder sumar [vectores](https://es.wikipedia.org/wiki/Vector) con <a href="https://es.wikipedia.org/wiki/Matriz_(matem%C3%A1ticas)">matrices</a>, multiplicar <a href="https://es.wikipedia.org/wiki/Escalar_(matem%C3%A1tica)">escalares</a> a [vectores](https://es.wikipedia.org/wiki/Vector) y demás.

## Librerías de Python para álgebra lineal

Los principales módulos que [Python](https://python.org/) nos ofrece para realizar operaciones de [Álgebra lineal](https://es.wikipedia.org/wiki/%C3%81lgebra_lineal) son los siguientes:

* **[Numpy](https://www.numpy.org/)**: El popular paquete matemático de [Python](https://python.org/), nos va a permitir crear *[vectores](https://es.wikipedia.org/wiki/Vector)*, *<a href="https://es.wikipedia.org/wiki/Matriz_(matem%C3%A1ticas)">matrices</a>* y *[tensores](https://es.wikipedia.org/wiki/C%C3%A1lculo_tensorial)* con suma facilidad.

* **[numpy.linalg](https://docs.scipy.org/doc/numpy/reference/routines.linalg.html)**: Este es un submodulo dentro de [Numpy](https://www.numpy.org/) con un gran número de funciones para resolver ecuaciones de [Álgebra lineal](https://es.wikipedia.org/wiki/%C3%81lgebra_lineal).

* **[scipy.linalg](https://docs.scipy.org/doc/scipy/reference/tutorial/linalg.html)**: Este submodulo del paquete científico [Scipy](https://docs.scipy.org/doc/scipy/reference/index.html) es muy similar al anterior, pero con algunas más funciones y optimaciones.

* **[Sympy](https://www.sympy.org/es/)**: Esta librería nos permite trabajar con matemática simbólica, convierte a [Python](https://python.org/) en un [sistema algebraico computacional](https://es.wikipedia.org/wiki/Sistema_algebraico_computacional). Nos va a permitir trabajar con ecuaciones y fórmulas simbólicamente, en lugar de numéricamente.

* **[CVXOPT](https://cvxopt.org/)**: Este módulo nos permite resolver problemas de optimizaciones de [programación lineal](https://es.wikipedia.org/wiki/Programaci%C3%B3n_lineal). 

* **[PuLP](https://pythonhosted.org//PuLP/)**: Esta librería nos permite crear modelos de [programación lineal](https://es.wikipedia.org/wiki/Programaci%C3%B3n_lineal) en forma muy sencilla con [Python](https://python.org/).

## Operaciones básicas

### Vectores

Un *[vector](https://es.wikipedia.org/wiki/Vector)* de largo `n` es una secuencia (o *array*, o *tupla*) de `n` números. La solemos escribir como $x=(x1,...,xn)$ o $x=[x1,...,xn]$

En [Python](https://python.org/), un *[vector](https://es.wikipedia.org/wiki/Vector)* puede ser representado con una simple *lista*, o con un *array* de [Numpy](https://www.numpy.org/); siendo preferible utilizar esta última opción.

```python
# Vector como lista de Python
v1 = [2, 4, 6]
v1
Out: [2, 4, 6]


# Vectores con numpy
import numpy as np

v2 = np.ones(3) # vector de solo unos.
v2
Out: array([ 1.,  1.,  1.])

v3 = np.array([1, 3, 5]) # pasando una lista a las arrays de numpy
v3
Out: array([1, 3, 5])

v4 = np.arange(1, 8) # utilizando la funcion arange de numpy
v4
Out: array([1, 2, 3, 4, 5, 6, 7])
```

### Representación gráfica

Tradicionalmente, los *[vectores](https://es.wikipedia.org/wiki/Vector)* son representados visualmente como flechas que parten desde el origen hacia un punto.

Por ejemplo, si quisiéramos representar graficamente a los vectores $v1=[2, 4]$, $v2=[-3, 3]$ y $v3=[-4, -3.5]$, podríamos hacerlo de la siguiente manera.
