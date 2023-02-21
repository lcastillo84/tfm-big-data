# Diseño e implementación de arquitectura de analítica de datos en la nube para aplicación IoT
### TFM para Master en Big Data y Business Analytics - IMF Business Schoo.
### Autor: Luis Castillo

## Resumen
En este trabajo se presenta el diseño de una arquitectura de ingesta, almacenamiento y presentación de datos, provenientes de sensores IoT en un entorno industrial. Los sensores utilizan el protocolo LoRaWAN para la transmisión de los datos. La implementación de la aplicación se realiza en su totalidad usando los servicios de un proveedor en la nube, Amazon Web Services. Los datos de las mediciones de los sensores son almacenados en una base de datos optimizada para series temporales, y los mensajes crudos en formato JSON se guardan en un sistema de almacenamiento de objetos. Para la presentación de los datos se utilizan cuadros de mando implementados en un servidor Grafana. Así mismo, la arquitectura permite el acceso a los datos mediante consultas SQL y Jupyter Notebooks. La arquitectura implementada cumple con los objetivos fijados de escalabilidad, tolerancia a fallos, flexibilidad y eficiencia de costos.

