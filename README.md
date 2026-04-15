# residuos-municipales-peru
Este repositorio contiene notebooks de ETL y análisis exploratorio sobre la generación de residuos municipales en el Perú durante el periodo 2014 - 2024.

Los datos fueron obtenidos de la Plataforma de Datos Abiertos del Gobierno del Perú:
https://www.datosabiertos.gob.pe/dataset/residuos-municipales-generados-anualmente

📊 Descripción del dataset

El dataset presenta información sobre la generación de residuos municipales a nivel de:

Departamento
Provincia
Distrito

Esto permite realizar análisis detallados y comparativos sobre el comportamiento de la generación de residuos en distintas regiones del país.

🌎 Enriquecimiento de datos

Con el objetivo de habilitar análisis geoespaciales, el dataset principal fue complementado con información geográfica (latitud y longitud por ubigeo), obtenida de:
https://inkamaps.com/

Esto permite la visualización de los datos en mapas y facilita la identificación de patrones territoriales.

🧹 Procesos de limpieza y transformación

Durante el desarrollo del ETL se abordaron diversos desafíos, entre ellos:

Normalización de nombres de distritos no homologados
Estandarización de formatos de fecha inconsistentes
Validación de tipos de datos
Corrección y validación de códigos de ubigeo (longitud y estructura)
📈 Análisis realizado

A partir de los datos procesados, se desarrollaron los siguientes análisis:

Evolución temporal de la generación de residuos municipales
Identificación de distritos con mayor y menor generación de residuos por habitante
Generación de mapas de calor a nivel distrital para el año 2024
Análisis comparativo entre regiones
🛠️ Tecnologías utilizadas
Python
Pandas
Jupyter Notebook
Herramientas de visualización (matplotlib, seaborn o similares)
📌 Posibles mejoras
Incorporar datos poblacionales actualizados para mejorar el cálculo per cápita
Integrar dashboards interactivos (Power BI, Tableau o similares)
Automatizar el pipeline ETL
