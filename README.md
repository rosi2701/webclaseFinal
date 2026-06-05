# webclaseFinal

### Primero, para quién:

#### Mainstream

| Preguntas | Respuestas |
|:----------|:-----------|
| Nombre y Rol | Sofía, estudiante universitaria de comunicaciones |
| Demográficos | 22 años, Santiago. Estudiante con ingresos bajos, vive con sus padres. Consume series animadas en plataformas de streaming en su tiempo libre.| 
| Objetivos y Motivaciones | Quiere descubrir qué series animadas son las mejor evaluadas y más populares para decidir qué ver a continuación. Busca una vista rápida y visual que le ayude a comparar series sin tener que leer artículos largos. | 
| Puntos de dolor (Pain points) | Le cuesta encontrar información centralizada sobre series animadas que no sea solo de anime o solo de caricaturas occidentales. Los sitios de recomendación son lentos y están llenos de publicidad. No tiene tiempo para investigar mucho. |


#### Un extremo

| Preguntas | Respuestas |
|:----------|:-----------|
| Nombre y Rol | Eduardo, productor de contenido audiovisual freelance |
| Demográficos | 31 años, Santiago. Ingresos medios-altos. Trabaja de forma independiente creando videos de análisis sobre la industria de la animación para YouTube. | 
| Objetivos y Motivaciones | Necesita datos concretos y comparables sobre tendencias en la industria animada: qué países producen más, qué géneros dominan, cómo evolucionó la popularidad en el tiempo. Busca insights que pueda citar en sus videos. | 
| Puntos de dolor (Pain points) | Los datos de animación están dispersos en múltiples fuentes (IMDb, MyAnimeList, TMDB) y no hay un lugar que los unifique visualmente. Le frustra tener que hacer scraping o cruzar tablas manualmente para obtener estadísticas comparativas. |

#### Otro extremo

| Preguntas | Respuestas |
|:----------|:-----------|
| Nombre y Rol | Marta, profesora de educación básica |
| Demográficos | 48 años, Concepción. Ingresos medios. Usa series animadas como recurso pedagógico en clases. Tiene conocimientos tecnológicos básicos. | 
| Objetivos y Motivaciones | Quiere encontrar series animadas bien evaluadas y apropiadas para diferentes edades, con información clara sobre popularidad y origen. No busca análisis profundos, sino una guía simple y visual. | 
| Puntos de dolor (Pain points) | La mayoría de dashboards de datos son demasiado técnicos o están en inglés. Le cuesta interpretar gráficos complejos. Necesita algo intuitivo que pueda usar en pocos minutos sin formación técnica. |

- - - - - 

### Segundo, con qué:

TMDB API (The Movie Database) 

- - - - - -

### Tercero, qué: 

AnimaStats es un dashboard interactivo que permite explorar y comparar las series animadas mejor evaluadas del mundo. Incluye:
 
- Ranking top 10 de series por rating
- Distribución por país de origen (Japón vs. occidente vs. otros)
- Línea de tiempo de estrenos por año
- Comparativa por idioma original
- Filtro interactivo por rating mínimo y país
- Tarjetas de series con póster, nombre y datos clave

#### Antecedente 1: Base de datos de cartas de JCC 

https://www.pokemon.com/el/jcc-pokemon/cartas-pokemon

<img width="1919" height="970" alt="Captura de pantalla 2026-06-05 003242" src="https://github.com/user-attachments/assets/cf8570de-fb50-4be6-a16d-54ce970dfd95" />

Positivo: Sistema de filtros lateral que actualiza los resultados en tiempo real sin recargar la página. La paleta colorida y lúdica refleja una identidad de marca fuerte, muy alineada con el estilo visual que busca el proyecto.
Negativo: No incluye visualizaciones de datos ni gráficos comparativos, todos los elementos tienen el mismo peso visual.

#### Antecedente 2: Netflix Universe Explorer 

https://dhirengshetty14.github.io/Netflix-Visual-Analytics/

<img width="1919" height="970" alt="Captura de pantalla 2026-06-05 001454" src="https://github.com/user-attachments/assets/577de338-44bb-4b7c-81f9-562e9dfc6c58" />

Positivo: Un aspecto muy positivo de este panel es la excelente variedad de gráficos utilizados, como el *streamgraph*, el mapa de calor y los diagramas de caja, los cuales, al combinarse con un panel de filtros detallado, permiten explorar los datos desde múltiples dimensiones de forma completa.
Negativo: La densidad de información es abrumadora para un usuario casual. Algunos gráficos como el de box plots o el grafo de nodos requieren conocimientos estadísticos para interpretarse correctamente.

#### Antecedente 3: My Anime List

https://myanimelist.net/topanime.php

<img width="1919" height="970" alt="Captura de pantalla 2026-06-04 222352" src="https://github.com/user-attachments/assets/1255cbdc-26d3-4f5e-9a38-111a902c3e2d" />

Positivo: Las pestañas de filtro en la parte superior (All Anime, Top Airing, Top Upcoming, etc) son una solución elegante para cambiar el contexto del ranking sin recargar la página.
Negativo: El diseño es plano y aburrido. No hay visualización de datos, gráficos ni elementos interactivos. Para alguien que llega sin saber qué buscar, no hay nada que lo invite a explorar más allá de hacer scroll.

#### Moodboard de Referentes

En proceso

![Meme](https://cdn.memegenerator.es/imagenes/memes/full/3/36/3367862.jpg)
