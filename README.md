# Análisis de calidad de aire en Ciudad de Buenos Aires

Este proyecto tiene como objetivo aplicar conocimientos en data science a una base de datos simple.
En el mismo se pretende generar una visualización de los principales aspectos analizados a partir de una previa limpieza y estructuración de la información diaria de los niveles medios de monóxido de carbono, dióxido de nitrógeno y material particulado respirable menor a 10 micrones medidos en las estaciones de La Boca, Cordoba, Palermo y Parque Centenario.
Estos últimos han sido obtenidos de la Agencia de Protección Ambiental (APrA). Secretaría de Ambiente. Jefatura de Gobierno, Nación Argentina
cuya página oficial se encuentra disponible en el siguiente [link](https://data.buenosaires.gob.ar/dataset/calidad-aire3).

## Archivos

El repositorio cuenta principalmente con: 
1. Una carpeta denominada DATASETS donde están disponibles las tablas utilizadas
2. El archivo "EDA.ipynb" que contiene el análisis exploratorio de los datos
3. El archivo "ETL.ipynb" que contiene la limpieza y estructuración de los datos para cargarlos en MySQL
4. El archivo "Calidad de aire Ciudad de Buenos Aires.pbix" donde se encuentra el dashboard interactivo.

Dashboard (muestra)
![Muestra del dashboard generado](https://github.com/lexio7/Calidad-del-aire-Buenos-Aires-2009-2023/blob/main/muestra%20dashb.jpg)

Diagrama estructural de los datos
![Diagrama MySQL](https://github.com/lexio7/Calidad-del-aire-Buenos-Aires-2009-2023/blob/main/Ilustraci%C3%B3n.jpg)

## Tecnologías
Python
MySQL
Power Bi
Excel

## Instalación

1. Clona el repositorio: `git clone https://github.com/tu-usuario/tu-proyecto.git`
2. Entra al directorio del proyecto: `cd tu-proyecto`
3. Instala las dependencias: `npm install`

## Contribuir

Si quieres contribuir a este proyecto, por favor sigue estos pasos:

1. Crea un fork del proyecto
2. Crea una nueva rama: `git checkout -b feature/nueva-caracteristica`
3. Haz tus cambios y haz commit: `git commit -m 'Agrega una nueva característica'`
4. Sube tus cambios: `git push origin feature/nueva-caracteristica`
5. Abre un pull request en GitHub

