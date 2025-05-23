![Banner del Repositorio](bannerPortada.jpeg)

# MSC_Big_Data
Temario oficial de la asignatura "Big Data" para la especialidad de Inteligencia Artificial, estructurado en 4 unidades principales

---
## Unidad 1: Fundamentos y Ecosistema de Big Data

**Tema principal:** Introducción estratégica y conceptual al Big Data y su ecosistema tecnológico.

- [1.1. Conceptos y relevancia de Big Data](subtemas/1.1-conceptos-relevancia.md)  
  - [1.1.1. Definición, historia y contexto actual](subtemas/1.1.1-definicion-historia.md)
  - [1.1.2. Impacto en la transformación digital y la toma de decisiones](subtemas/1.1.2-impacto-transformacion.md)
  - [1.1.3. Roles profesionales: Data Engineer, Data Scientist, Data Architect](subtemas/1.1.3-roles-profesionales.md)

- [1.2. Características de los datos masivos (Las 5 V)](subtemas/1.2-caracteristicas-5v.md)  
  - [1.2.1. Volumen, Velocidad, Variedad, Veracidad, Valor](subtemas/1.2.1-5v.md)
  - [1.2.2. Fuentes de datos: IoT, redes sociales, logs empresariales](subtemas/1.2.2-fuentes-datos.md)

- [1.3. Arquitectura y ecosistema Big Data](subtemas/1.3-arquitectura-ecosistema.md)  
  - [1.3.1. Modelos de arquitectura: Lambda, Kappa](subtemas/1.3.1-modelos-arquitectura.md)
  - [1.3.2. Componentes: almacenamiento, procesamiento, análisis, visualización](subtemas/1.3.2-componentes.md)
  - 1.3.3. Tecnologías clave: 
    - [Apache Hadoop](https://hadoop.apache.org)
    - [Apache Spark](https://spark.apache.org)
    - [Apache Kafka](https://kafka.apache.org)
    - [HDFS](https://hadoop.apache.org/docs/stable/hadoop-project-dist/hadoop-hdfs/HdfsUserGuide.html)
    - [Apache Hive](https://hive.apache.org)
    - [Apache Airflow](https://airflow.apache.org)

---

## Unidad 2: Adquisición, Ingesta y Procesamiento de Datos

**Tema principal:** Técnicas y herramientas para la recolección, ingesta y procesamiento eficiente de grandes volúmenes de datos.

- [2.1. Métodos de adquisición e ingesta de datos](subtemas/2.1-adquisicion-ingesta.md)  
  - [2.1.1. Web scraping (BeautifulSoup, Selenium)](subtemas/2.1.1-web-scraping.md)
    - [BeautifulSoup](https://www.crummy.com/software/BeautifulSoup/)
    - [Selenium](https://www.selenium.dev/)
  - [2.1.2. APIs y conectores (REST, Twitter API, Google Maps API)](subtemas/2.1.2-apis-conectores.md)
    - [Twitter API](https://developer.twitter.com/en/docs)
    - [Google Maps API](https://developers.google.com/maps/documentation)
  - [2.1.3. Ingesta en tiempo real (Kafka, Flume, NiFi)](subtemas/2.1.3-ingesta-tiempo-real.md)
    - [Apache Kafka](https://kafka.apache.org)
    - [Apache Flume](https://flume.apache.org)
    - [Apache NiFi](https://nifi.apache.org)

- [2.2. Procesamiento distribuido](subtemas/2.2-procesamiento-distribuido.md)  
  - [2.2.1. Paradigma MapReduce](subtemas/2.2.1-mapreduce.md)
  - [2.2.2. Procesamiento batch vs. streaming](subtemas/2.2.2-batch-streaming.md)
  - [2.2.3. Frameworks: Apache Spark, Apache Flink, Storm](subtemas/2.2.3-frameworks.md)
    - [Apache Spark](https://spark.apache.org)
    - [Apache Flink](https://flink.apache.org)
    - [Apache Storm](https://storm.apache.org)

- [2.3. Limpieza y transformación de datos](subtemas/2.3-limpieza-transformacion.md)  
  - [2.3.1. Preprocesamiento: normalización, imputación, detección de outliers](subtemas/2.3.1-preprocesamiento.md)
  - [2.3.2. Herramientas: Python (pandas, NumPy), R, PySpark](subtemas/2.3.2-herramientas.md)
    - [Python](https://www.python.org)
    - [pandas](https://pandas.pydata.org/)
    - [NumPy](https://numpy.org/)
    - [R](https://www.r-project.org)
    - [PySpark](https://spark.apache.org/docs/latest/api/python/)

---

## Unidad 3: Almacenamiento y Gestión Escalable de Datos

**Tema principal:** Soluciones y estrategias para el almacenamiento, consulta y gestión eficiente de grandes volúmenes de datos.

- [3.1. Almacenamiento distribuido y sistemas de archivos](subtemas/3.1-almacenamiento-distribuido.md)  
  - [3.1.1. HDFS, Amazon S3, Google Cloud Storage](subtemas/3.1.1-hdfs-s3-gcs.md)
    - [HDFS](https://hadoop.apache.org/docs/stable/hadoop-project-dist/hadoop-hdfs/HdfsUserGuide.html)
    - [Amazon S3](https://aws.amazon.com/s3/)
    - [Google Cloud Storage](https://cloud.google.com/storage)
  - [3.1.2. Redundancia y tolerancia a fallos](subtemas/3.1.2-redundancia-tolerancia.md)

- [3.2. Bases de datos NoSQL y NewSQL](subtemas/3.2-bases-nosql-newsql.md)  
  - [3.2.1. Tipos: clave-valor (Redis), documento (MongoDB), columnares (Cassandra, HBase), grafos (Neo4j)](subtemas/3.2.1-tipos-nosql.md)
    - [Redis](https://redis.io)
    - [MongoDB](https://www.mongodb.com)
    - [Apache Cassandra](https://cassandra.apache.org)
    - [Apache HBase](https://hbase.apache.org)
    - [Neo4j](https://neo4j.com)
  - [3.2.2. Comparación con bases relacionales (SQL, PostgreSQL)](subtemas/3.2.2-comparacion-sql.md)
    - [SQL](https://www.sql.org)
    - [PostgreSQL](https://www.postgresql.org)

- [3.3. Estrategias de almacenamiento y recuperación](subtemas/3.3-estrategias-almacenamiento.md)  
  - [3.3.1. Indexación, particionamiento, replicación](subtemas/3.3.1-indexacion-particionamiento.md)
  - [3.3.2. Consistencia, disponibilidad y tolerancia a particiones (CAP theorem)](subtemas/3.3.2-cap-theorem.md)
  - [3.3.3. Orquestación y automatización (Airflow, Kubernetes)](subtemas/3.3.3-orquestacion-automatizacion.md)
    - [Apache Airflow](https://airflow.apache.org)
    - [Kubernetes](https://kubernetes.io)

---

## Unidad 4: Análisis, Modelado y Machine Learning en Big Data

**Tema principal:** Técnicas de análisis, modelado predictivo y aprendizaje automático aplicadas a grandes conjuntos de datos.

- [4.1. Análisis exploratorio y descriptivo](subtemas/4.1-analisis-exploratorio.md)  
  - [4.1.1. Estadística descriptiva, correlación, visualización inicial](subtemas/4.1.1-estadistica-correlacion.md)
  - [4.1.2. Herramientas: Python (pandas, matplotlib, seaborn), R](subtemas/4.1.2-herramientas.md)
    - [Python](https://www.python.org)
    - [pandas](https://pandas.pydata.org/)
    - [matplotlib](https://matplotlib.org)
    - [seaborn](https://seaborn.pydata.org)
    - [R](https://www.r-project.org)

- [4.2. Modelado predictivo y machine learning](subtemas/4.2-modelado-ml.md)  
  - [4.2.1. Algoritmos escalables: regresión, clasificación, clustering (Spark MLlib, scikit-learn)](subtemas/4.2.1-algoritmos-escalables.md)
    - [Spark MLlib](https://spark.apache.org/mllib/)
    - [scikit-learn](https://scikit-learn.org)
  - [4.2.2. Validación y evaluación de modelos](subtemas/4.2.2-validacion-evaluacion.md)
  - [4.2.3. Integración de modelos en pipelines de datos](subtemas/4.2.3-integracion-pipelines.md)

- [4.3. Procesamiento distribuido para ML](subtemas/4.3-ml-distribuido.md)  
  - [4.3.1. Spark MLlib, TensorFlow, H2O.ai](subtemas/4.3.1-spark-tensorflow-h2o.md)
    - [Spark MLlib](https://spark.apache.org/mllib/)
    - [TensorFlow](https://www.tensorflow.org)
    - [H2O.ai](https://www.h2o.ai)
  - [4.3.2. Ejecución de modelos en clústeres](subtemas/4.3.2-ejecucion-cluster.md)

---

## Unidad 5: Visualización, Implementación y Proyectos de Big Data

**Tema principal:** Visualización avanzada, despliegue de soluciones y desarrollo de proyectos integradores.

- [5.1. Visualización de grandes volúmenes de datos](subtemas/5.1-visualizacion.md)  
  - [5.1.1. Herramientas: Tableau, Power BI, D3.js, matplotlib](subtemas/5.1.1-herramientas-visualizacion.md)
    - [Tableau](https://www.tableau.com)
    - [Power BI](https://powerbi.microsoft.com)
    - [D3.js](https://d3js.org)
    - [matplotlib](https://matplotlib.org)
  - [5.1.2. Dashboards interactivos y reporting](subtemas/5.1.2-dashboards-reporting.md)
  - [5.1.3. Mejores prácticas de visualización](subtemas/5.1.3-mejores-practicas.md)

- [5.2. Implementación y despliegue de soluciones Big Data](subtemas/5.2-despliegue.md)  
  - [5.2.1. Integración en pipelines empresariales](subtemas/5.2.1-integracion-pipelines.md)
  - [5.2.2. Orquestación con Airflow/Kubernetes](subtemas/5.2.2-orquestacion.md)
    - [Apache Airflow](https://airflow.apache.org)
    - [Kubernetes](https://kubernetes.io)
  - [5.2.3. Monitoreo y mantenimiento](subtemas/5.2.3-monitoreo-mantenimiento.md)

- [5.3. Proyecto integrador y casos de estudio](subtemas/5.3-proyecto-integrador.md)  
  - [5.3.1. Aplicaciones en industria, salud, finanzas, IoT](subtemas/5.3.1-aplicaciones.md)
  - [5.3.2. Desarrollo de un proyecto de principio a fin](subtemas/5.3.2-proyecto-fin.md)

---

## Tecnologías y Herramientas Clave

- **Lenguajes:** [Python](https://www.python.org), [R](https://www.r-project.org), [SQL](https://www.sql.org), [Scala](https://www.scala-lang.org)
- **Frameworks:** [Apache Hadoop](https://hadoop.apache.org), [Apache Spark](https://spark.apache.org), [Apache Flink](https://flink.apache.org), [Apache Storm](https://storm.apache.org)
- **Bases de datos:** [MongoDB](https://www.mongodb.com), [Apache Cassandra](https://cassandra.apache.org), [Apache HBase](https://hbase.apache.org), [Neo4j](https://neo4j.com), [PostgreSQL](https://www.postgresql.org)
- **Herramientas de ingesta:** [Apache Kafka](https://kafka.apache.org), [Apache Flume](https://flume.apache.org), [Apache NiFi](https://nifi.apache.org)
- **Orquestación:** [Apache Airflow](https://airflow.apache.org), [Kubernetes](https://kubernetes.io)
- **Visualización:** [Tableau](https://www.tableau.com), [Power BI](https://powerbi.microsoft.com), [matplotlib](https://matplotlib.org), [seaborn](https://seaborn.pydata.org), [D3.js](https://d3js.org)
- **Cloud:** [Amazon Web Services (AWS)](https://aws.amazon.com), [Google Cloud Platform (GCP)](https://cloud.google.com), [Microsoft Azure](https://azure.microsoft.com)

---

## Tecnologías:
[![Apple](https://img.shields.io/badge/iOS-999999?style=for-the-badge&logo=apple&logoColor=white&labelColor=101010)]()
[![Swift](https://img.shields.io/badge/Swift-FA7343?style=for-the-badge&logo=swift&logoColor=white&labelColor=101010)]()
[![Xcode](https://img.shields.io/badge/Xcode-1575F9?style=for-the-badge&logo=xcode&logoColor=white&labelColor=101010)]()
</br>
[![Android](https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=white&labelColor=101010)]()
[![Kotlin](https://img.shields.io/badge/Kotlin-0095D5?style=for-the-badge&logo=kotlin&logoColor=white&labelColor=101010)]()
[![Android_Studio](https://img.shields.io/badge/Android_Studio-3DDC84?style=for-the-badge&logo=android-studio&logoColor=white&labelColor=101010)]()
</br>
[![Python](https://img.shields.io/badge/Python-yellow?style=for-the-badge&logo=python&logoColor=white&labelColor=101010)]()
[![Java](https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=java&logoColor=white&labelColor=101010)]()
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=white&labelColor=101010)]()
[![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white&labelColor=101010)]()
[![Google_Cloud](https://img.shields.io/badge/Google_Cloud-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white&labelColor=101010)]()
</br>
[![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=white&labelColor=101010)]()
[![Node.JS](https://img.shields.io/badge/Node.JS-339933?style=for-the-badge&logo=node.js&logoColor=white&labelColor=101010)]()
[![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white&labelColor=101010)]()
[![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white&labelColor=101010)]()
</br>
Y alguna más...
