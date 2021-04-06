# ElasticSearch
Es un motor de busqueda que se basa en `Lucene` el cual nos permite realizar busquedas por una gran cantidad de texto especifico. Esta escrito en `Java` y esta bajo la licencia `Apache`.
## Caracteristicas
* **Orientacion a documentos:**
    * Es una base de datos NoSql orientada a documentos `JSON`.
    * Nos permite indexar grandes volumenes de datos, para poderlos consultar posteriormente.
    * ElasticSearch se basa en el modelo NoSql, almacena la informacion de forma desnormalizado.
* **Indexacion:**
    * El proceso de añadir informacion a elasticsearch se llama indexacion.
* **Escalabilidad:**
    * Es una base de datos distribuida que escala de manera dinamica de forma horizontal. (Soporta petabytes).
    * Se organiza mediante nodos, los cuales son alojados dentro de un cluster.
    * Los documentos son particionados mediante tecnicas `sharding` aplica tecnicas de replica.
    * Enruta las peticiones al nodo especifico del cluster el cual contenga la informacion necesaria que se esta buscando.
    * Detecta si hay un nodo que esta fallando, de esta manera es capaz de organizar la informacion y conseguir que los datos esten siempre accecibles.
* **Acceso por API:**
    * Permite acceder a los datos en tiempo real.
    * Posee librerias que nos ofrecen la coneccion.
    * Maneja su propio sistema de `Query Domain Specific Language` (DSL) mediante el cual permite realizar consultar meidnate `JSON`.
## Casos de uso:
* Buscador de texto.
* Gestor de logs.
* Analisis de seguridad.
* Analisis de metricas. 