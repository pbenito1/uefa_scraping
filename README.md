# UEFA Scraping
Scraper de datos estadísticos de uefa.com. 
Práctica 1 de la asignatura *"Tipología y ciclo de vida de los datos"* del Master en Ciencia de Datos de la UOC

# Autores

* Pablo Benito
* Miquel Rived Martínez

# Contexto
Explicar en qué contexto se ha recolectado la información. Explique por qué el sitio web elegido proporciona dicha información.

# Definir un título para el dataset
Elegir un título que sea descriptivo.

# Descripción del dataset
Desarrollar una descripción breve del conjunto de datos que se ha extraído (es necesario que esta descripción tenga sentido con el título
elegido).

# Representación gráfica
Presentar esquema o diagrama que identifique el dataset visualmente y el proyecto elegido

# Contenido
Explicar los campos que incluye el dataset, el periodo de tiempo de
los datos y cómo se ha recogido.
# Agradecimientos
Presentar al propietario del conjunto de datos. Es necesario
incluir citas de análisis anteriores o, en caso de no haberlas, justificar esta
búsqueda con análisis similares.
# Inspiración
Explique por qué es interesante este conjunto de datos y qué
preguntas se pretenden responder. Es necesario comparar con los análisis
anteriores presentados en el apartado 6.

# Licencia
Seleccione una de estas licencias para su dataset y explique el motivo
de su selección:
- Released Under CC0: Public Domain License
- Released Under CC BY-NC-SA 4.0 License
- Released Under CC BY-SA 4.0 License
- Database released under Open Database License, individual contents
under Database Contents License
- Other (specified above)
- Unknown License
# Código
Adjuntar el código con el que se ha generado el dataset, preferiblemente en Python o, alternativamente, en R.

## URLS
Datos de jugadores: 
https://www.uefa.com/uefachampionsleague/season=2021/statistics/round=2001252/players/
La página a su vez carga esta otra URL con los datos de los jugadores:
https://www.uefa.com/statistics/uefachampionsleague/season=2021/statistics/round=2001252/players/_loadRemaining.html

Esta segunda página resulta muy sencilla de parsear


Información detallada de jugador:
https://www.uefa.com/uefachampionsleague/clubs/players/250103758--erling-haaland/
La información del jugador está en el cuerpo del HTML: 



----
Otras fuentes de información:

https://towardsdatascience.com/web-scraping-advanced-football-statistics-11cace1d863a

En esta URL se explica bastante bien como extraer información a partir de https://understat.com/. En esta web existen estadísticas de varias temporadas y de las grandes ligas de europa.

https://github.com/Urbistondo/sofa-score-scraper

Esta última es un ejemplo de web scrapping a partir de sofa-score. Lo veo demasiado complejo para lo que queremos hacer, pero podemos sacar los links de aquí. A continuación dejo un link de ejemplo de como están los datos para extraerlos:
https://www.sofascore.com/team/football/real-madrid/2829

Ejemplo de como extraer datos a partir de transfermarkt 
https://dev.to/lisandramelo/extracting-data-from-transfermarkt-an-introduction-to-webscraping-2i1c

Web de estadísticas de las grandes ligas:
https://es.whoscored.com/Statistics

Otro ejemplo de Web Scrapping a partir de los equipos de la liga española y de esta web https://fbref.com/en/
https://www.jorgelopezperez.com/posts/estad%C3%ADsticas-f%C3%BAtbol-fbrefcon-rvest-polite-purrr/



# Dataset
Publicación del dataset en formato CSV en Zenodo (obtención del DOI) con una breve descripción.

# 
