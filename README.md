El objetivo de este proyecto es presentar la metodología usada para extraer los datos de incidencia de la covid-19 en la Comunidad de Madrid directamente de un mapa de tipo ArcGis. ArcGIS es un completo sistema que permite recopilar, organizar, administrar, analizar, compartir y distribuir información geográfica. En concreto, se trata de el mapa de incidencia por municipios y distritos y el mapa de incidencia por Zona Básica de Salud, ambos disponibles en la página [web](https://www.comunidad.madrid/gobierno/actualidad/datos-coronavirus) de la Comunidad de Madrid:

* [Mapa interactivo de información epidemiológica COVID-19 por municipios y distritos de Madrid](https://comunidadmadrid.maps.arcgis.com/apps/PublicInformation/index.html?appid=cdfb61b3eb3a49c2b990b4fdb41dfcfe)
* [Mapa interactivo de información epidemiológica COVID-19 por Zona Básica de Salud](https://comunidadmadrid.maps.arcgis.com/apps/PublicInformation/index.html?appid=7db220dc2e0a40b4a928df661a89762e)

Se proponen dos cuadernos Jupyter. **argis.ipynb** contiene el código que identifica los elementos internos de ArcGis necesarios para poner realizar la consulta de los datos y almacenarlos en una base de datos. **update_table.ipynb** es una versión simplificada del primero, pensada para añadir de forma rápida los datos más recientes a una tabla con datos antiguos. El resultado final es similar a las tablas disponibles en el [portal de datos abiertos](https://www.comunidad.madrid/gobierno/actualidad/datos-coronavirus) de la Comunidad de Madrid.

La información sobre las variables se puede encontrar [aquí](https://datos.comunidad.madrid/catalogo/dataset/covid19_tia_muni_y_distritos/resource/f22c3f43-c5d0-41a4-96dc-719214d56968) (para tabla de Municipios y Distritos) y [aquí](https://datos.comunidad.madrid/catalogo/dataset/covid19_tia_zonas_basicas_salud/resource/43708c23-2b77-48fd-9986-fa97691a2d59) (para Zonas Básicas de Salud)

El proyecto sirve como excusa para entender el funcionamiento interno de ArcGIS, con el fin de que pueda servir de guía para la extracción de datos en otros mapas del mismo tipo.


