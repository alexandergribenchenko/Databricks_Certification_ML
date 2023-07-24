# Databricks certification

# Apache Spark Overview

- Objetivo de Spark: Procesamiento distribuido.
- Built in aPIs in SQL, Python, Scala, R y Java.
- En nuestro caso permitira hacer distribuited machine learning.

- Arquitectura básica de Spark: One driver - Many Workers (Executors), donde cada worker ejecuta un JVM (Java Virtual Machine) process.
- Basicamante lo que hace Spark es crear un Optimized logicalplan para distribuir a cada uno de los workers que deberian hacer para que la consulta (SQL query) sea la mas eficiente.

- Cuando usar Spark? Cuando la dat aes demasiado grande para procesarla en una sigle machine en la que se estan obteniendo por ello comunmnete out-of-memory errors. O tambien cuando el procesamiento esta resultando muy lento y queremos incrementar esta velocidad de procesamiento con la distribución.

- Tipos de estrucuras de datos mas comunes: RDD (2011), DataFrame (2013) y Dataset(2015)
