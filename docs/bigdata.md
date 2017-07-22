Summary:Libro online de la comunidad de Inteligencia Artificial Argentina IAAR - Introducción a la Big Data. ¿Qué es la Big Data?. Bases de datos NoSQL. Hadoop. Spark. Otras herramientas de Big data. Kafka. Storm.

# Introducción a la Big Data

<center><img alt="Big Data" title="Big Data" src="https://iaarbook.github.io/img/big_data.png" width="60%" height="60%"></center>

Actualmente estamos viviendo la ***Era de los datos***, con el enorme crecimiento en el uso de herramientas digitales como internet y los dispositivos móviles, estamos generando datos constantemente, con cada movimiento que damos navegando en internet o interactuando en las redes sociales como Facebook o Twitter, estamos dejando una huella permanente que queda almacenada en algún [Data Center](http://es.wikipedia.org/wiki/Data_center). El volumen de información que estamos generando a cada segundo es enorme.

Este gran crecimiento en el volumen de datos, ha obligado a rever la forma en la que diseñamos nuestros sistemas, y es así, como el concepto de [Big Data](http://es.wikipedia.org/wiki/Big_data) y la nueva disciplina de los [cientificos de datos](https://iaarbook.github.io/datascience/#cientifico-de-datos) ha surgido.

## ¿Qué es la Big Data?

La [Big Data](http://es.wikipedia.org/wiki/Big_data) es la rama de las [Teconlogías de la información](http://es.wikipedia.org/wiki/Tecnolog%C3%ADas_de_la_informaci%C3%B3n_y_la_comunicaci%C3%B3n) que estudia las dificultades inherentes a la manipulación de grandes [conjuntos de datos](http://es.wikipedia.org/wiki/Conjunto_de_datos). El verdadero poder de la [Big Data](http://es.wikipedia.org/wiki/Big_data) reside en que se trata sobre el comportamiento de la gente, y no sobre sus datos, consiste en encontrar los patrones de relaciones y comportamientos en el caos de los grandes volúmenes de datos que producimos. Los datos son tantos, que todos se vuelven estadístacamente significativos, lo que significa, que los métodos tradicionales que utilizamos para analizarlos se han vuelto obsoletos.

Para hacer frente a los nuevos desafíos que provoca la [Big Data](http://es.wikipedia.org/wiki/Big_data), nuevas herramientas informáticas han aparecido, sobre todo en el mundo del software [open source](http://es.wikipedia.org/wiki/C%C3%B3digo_abierto); es así, como el movimiento de [NoSQL](http://es.wikipedia.org/wiki/NoSQL) y proyectos como el de [Apache Hadoop](http://hadoop.apache.org/), han ganando popularidad.

## Bases de datos NoSQL

El movimiento [NoSQL](http://es.wikipedia.org/wiki/NoSQL) hace referencia a una serie de nuevos sistemas de gestión de datos, que se alejan del tradicional modelo relacional que tienen las populares bases de datos actuales ([Oracle](http://www.oracle.com/us/products/database/overview/index.html), [DB2](http://www-01.ibm.com/software/data/db2/), [MsSQL](http://www.microsoft.com/sqlserver/en/us/default.aspx), [MySQL](http://www.mysql.com/), [PostgreSQL](http://www.postgresql.org/), etc); la principal diferencia que caracteriza a estas nuevas bases de datos es que no poseen un esquema estructurado (tablas y sus relaciones) y no utilizan el lenguaje [SQL](http://es.wikipedia.org/wiki/SQL) para realizar sus consultas. Las bases de datos [NoSQL](http://es.wikipedia.org/wiki/NoSQL) surgieron principalmente para hacer frente al tratamiento de datos que los sistemas tradicionales de [RDBMS](http://es.wikipedia.org/wiki/Sistema_de_gesti%C3%B3n_de_bases_de_datos_relacionales) no podían manejar del todo bien (como ser toda la nueva información que surge del uso de las redes sociales). Se suelen agrupar en tres grandes grupos:

* **Bases de Datos Documentales:** Donde la información se va almacenando en diferentes documentos, estos documentos son un conjunto ordenado de claves con valores asociados. El principal exponente de este tipo de base de datos [NoSQL](http://es.wikipedia.org/wiki/NoSQL) es [MongoDB](http://www.mongodb.org/).
* **Bases de Datos clave-valor:**  Donde los datos se van almacenando en pares (clave-valor). Un ejemplo de este tipo de bases es [Redis](http://redis.io/).
* **Big Tables:** Grandes tablas de estructura tabular que se caracterizan por ser [distribuidas](http://es.wikipedia.org/wiki/Computaci%C3%B3n_distribuida) y de alta eficiencia. Las principales exponentes de este grupo son [Cassandra](http://cassandra.apache.org/) y [HBase](http://hbase.apache.org/).

## Hadoop

El proyecto [Apache Hadoop](http://hadoop.apache.org/) es un [framework de software](http://es.wikipedia.org/wiki/Framework), desarrollado en el lenguaje de programación <a href="http://es.wikipedia.org/wiki/Java_(lenguaje_de_programaci%C3%B3n)">Java</a>, que permite el procesamiento distribuido de grandes [conjuntos de datos](http://es.wikipedia.org/wiki/Conjunto_de_datos) a través de [clusters](http://es.wikipedia.org/wiki/Cluster_%28inform%C3%A1tica%29) de computadoras utilizando simples modelos de programación. La verdadera utilidad de [Hadoop](http://hadoop.apache.org/) radica en su capacidad para escalar fácilmente de uno a miles de [servidores distribuidos](http://es.wikipedia.org/wiki/Computaci%C3%B3n_distribuida), cada uno aportando su poder de computación y su capacidad de almacenamiento.

Los módulos que forman parte del framework [Hadoop](http://hadoop.apache.org/) son:

* **Hadoop common:** que incluye un conjunto de componentes e interfaces para el [sistema de archivos](http://es.wikipedia.org/wiki/Sistema_de_archivos) distribuido que implementa [Hadoop](http://hadoop.apache.org/). Son las herramientas comunes que se utilizan en todos los módulos.
* **Hadoop Distributed File System (HDFS):** Una de las herramientas principales del framework, el [sistema de archivos](http://es.wikipedia.org/wiki/Sistema_de_archivos) distribuido que corre entre los [clusters](http://es.wikipedia.org/wiki/Cluster_%28inform%C3%A1tica%29) de computadoras y que brinda el acceso a los datos para las aplicaciones.
* **Hadoop YARN(Yet Another Resource Negotiator):** Es un sistema general de gestión de trabajos para correr aplicaciones [distribuidas](http://es.wikipedia.org/wiki/Computaci%C3%B3n_distribuida).
* **Hadoop MapReduce:** La herramienta principal del framework, y a la que [Hadoop](http://hadoop.apache.org/) debe su gran popularidad. Consiste en un modelo de procesamiento de datos [distribuidos](http://es.wikipedia.org/wiki/Computaci%C3%B3n_distribuida) que corre en forma paralela entre los [clusters](http://es.wikipedia.org/wiki/Cluster_%28inform%C3%A1tica%29) de computadoras que constituyen la arquitectura del framework [Hadoop](http://hadoop.apache.org/). [MapReduce](https://es.wikipedia.org/wiki/MapReduce) es todo un modelo de programación para el procesamientos de datos distribuidos. 

[Hadoop](http://hadoop.apache.org/) ha cambiado la economía y la dinámica de la computación a gran escala. Su impacto puede sintetizarse en cuatro características principales.


**[Hadoop](http://hadoop.apache.org/) posibilita una solución informática que es:**

* **Redimensionable:** Pueden agregarse tantos nuevos nodos como sea necesario, y agregarse sin tener que cambiar el formato de los datos, la forma en
 que se cargan los datos, la forma en que se escriben los procesos o las aplicaciones que están encima.
* **Rentable:** [Hadoop](http://hadoop.apache.org/) incorpora masivamente la computación paralela a los servidores básicos. El resultado de esto es una marcada reducción del costo por terabyte de almacenamiento, que a su vez abarata el modelado de sus datos.

* **Flexible:** [Hadoop](http://hadoop.apache.org/) funciona sin esquema y puede absorber cualquier tipo de datos, estructurados o no, provenientes de un número cualquiera de fuentes. Los datos de diversas fuentes pueden agruparse de manera arbitraria y así permitir análisis más profundos que los proporcionados por cualquier otro sistema.

* **Tolerante a fallas:** Si usted pierde un nodo, el sistema redirige el trabajo a otra localización de los datos y continúa procesando sin perder el ritmo.

[Hadoop](http://hadoop.apache.org/) es la herramienta que grandes empresas como Facebook, Yahoo, Linkedin y Twitter han elegido para almacenar todos los datos de sus usuarios y saberlo todo sobre ellos. 

## Spark

[Apache Spark](http://spark.apache.org/) es una de las nuevas estrellas en el [análisis de datos](http://relopezbriega.github.io/category/analisis-de-datos.html) masivos. Desarrollado en [Scala](http://www.scala-lang.org/), [Apache Spark](http://spark.apache.org/) es una plataforma de computación de código abierto para el análisis y procesamiento de grandes volúmenes de datos. 

Algunas de las ventajas que nos ofrece [Apache Spark](http://spark.apache.org/) sobre otros [frameworks](http://es.wikipedia.org/wiki/Framework), son:

* **Velocidad:** Sin dudas la velocidad es una de las principales fortalezas de [Apache Spark](http://spark.apache.org/), como esta diseñado para soportar el [procesameinto en memoria](http://en.wikipedia.org/wiki/In-Memory_Processing), puede alcanzar una performance sorprendente en análisis avanzados de datos. Algunos programas escritos utilizando [Apache Spark](http://spark.apache.org/), pueden correr hasta 100x más rápido que utilizando [Hadoop](http://hadoop.apache.org/).

* **Fácil de usar:** Podemos escribir programas en [Python](http://python.org/), [Scala](http://www.scala-lang.org/) o [Java](http://java.com/en/) que hagan uso de las herramientas que ofrece [Apache Spark](http://spark.apache.org/); asimismo nos permite trabajar en forma interactiva (con [Python](http://python.org/) o con [Scala](http://www.scala-lang.org/)) y su [API](http://es.wikipedia.org/wiki/Interfaz_de_programaci%C3%B3n_de_aplicaciones) es muy fácil de aprender. 

* **Generalismo:** El mundo del análisis de datos incluye muchos subgrupos de distinta índole, están los que hacen un análisis investigativo, los que que realizan análisis exploratorios, los que construyen sistemas de procesamientos de datos, etc. Los usuarios de cada uno de esos subgrupos, al tener objetivos distintos, suelen utilizar una gran variedad de herramientas totalmente diferentes. [Apache Spark](http://spark.apache.org/) nos proporciona un gran número de herramientas de alto nivel como [Spark SQL](http://spark.apache.org/sql/), [MLlib](http://spark.apache.org/mllib/) para [machine learning](https://iaarbook.github.io/machine-learning/), [GraphX](http://spark.apache.org/graphx/), y [Spark Streaming](http://spark.apache.org/streaming/); las cuales pueden ser combinadas para crear aplicaciones multipropósito que ataquen los diferentes dominios del análisis de datos.

## Otras herramientas de Big data

### Kafka
[Kafka](https://kafka.apache.org/) Es una plataforma distribuida de [streaming](https://es.wikipedia.org/wiki/Streaming). Es decir, que tiene tres capacidades clave:

* Permite publicar y suscribirse a flujos de registros. A este respecto, es similar a una cola de mensajes o un sistema de mensajería empresarial.
* Permite almacenar flujos de registros de forma tolerante a fallos.
* Permite procesar flujos de registros a medida que ocurren.

**¿Para qué sirve [Kafka](https://kafka.apache.org/)?**

Se utiliza para dos clases de aplicación:

* Creación de flujos de datos que fluyen en tiempo real entre distintos sistemas o aplicaciones.
* Creación de aplicaciones de streaming en tiempo real que transforman o reaccionan a los flujos de datos.


### Storm
[Storm](http://storm.apache.org/) es una sistema de computación distribuida en tiempo real y de código abierto. Permite el procesamiento sencillo y fiable de grandes volúmenes de datos en analítica (por ejemplo para el estudio de información de modalidad continua procedente de redes sociales), [RPC distribuida](http://storm.apache.org/releases/current/Distributed-RPC.html), [procesos de ETL](https://es.wikipedia.org/wiki/Extract,_transform_and_load). 

Mientras que [Hadoop](http://hadoop.apache.org/) se encarga del procesamiento de datos por lotes, [Storm](http://storm.apache.org/) se encarga de hacerlo en tiempo real. 


Si bien la [Big Data](http://es.wikipedia.org/wiki/Big_data) trae muchas oportunidades, también abre muchas interrogantes, como ser: ¿Cuán ética es esta recolección de datos silenciosa que realizan las grandes empresas sobre nuestros datos?; ¿Quienes son los verdaderos dueños de esos datos?¿Qué pueden hacer las empresas con ellos?, el debate esta abierto…
