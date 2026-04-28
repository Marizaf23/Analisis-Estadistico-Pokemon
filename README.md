# Análisis Estadístico Pokémon
## Proyecto Académico Colaborativo: Estadística I

<div align="justify">

### Planteamiento del Problema
#### Contexto del Problema

Según portales oficiales como Wikidex, las estadísticas base de un Pokémon son cualidades naturales fijas que determinan su potencial de ataque o defensa. Aunque estas son inalterables por nivel, funcionan como el parámetro fundamental para calcular el valor real de cada estadística en combate y permiten a los jugadores mejorar su estrategia competitiva.

El problema radica en que, a pesar de la experiencia de los jugadores, existe una falta de análisis cuantitativo sobre cómo estas características han evolucionado a lo largo de las nueve generaciones. Comprender estos comportamientos permite establecer mejores estrategias en combates generacionales e identificar patrones de efectividad que no son evidentes a simple vista.

### Objetivos

* Analizar la relación entre las estadísticas base de los Pokémon y su generación para identificar tendencias de crecimiento o equilibrio en los datos.

* Describir el comportamiento de cada ítem estadístico (Salud, Ataque, Defensa, Ataque Especial, Defensa Especial y Velocidad) mediante medidas de tendencia central y dispersión.

* Investigar la correlación entre los atributos de ataque y defensa para entender el balance de diseño entre los roles ofensivos y defensivos en cada etapa de la franquicia.

### Fuente de Datos

La fuente utilizada para este análisis proviene de una base de datos de 1017 Pokémon suministrados en formato CSV (Pokemons G4.csv), que incluye información detallada desde la Generación 1 hasta la Generación 9.

### Herramientas / Librerías

Para el desarrollo de este análisis se utilizaron las siguientes herramientas y librerías de R:

* Lenguajes: R, LaTeX (vía TinyTeX).

* Manipulación de Datos: tidyverse, dplyr, readr.

* Visualización: ggplot2, gridExtra.

* Análisis Estadístico: moments (asimetría), modeest (cálculo de modas), knitr.

* Reporte: rmarkdown para la generación de documentos PDF dinámicos.

### Método Estadístico

Para cumplir con los objetivos planteados, se aplicaron las siguientes técnicas:

* Limpieza y Normalización: Filtrado de variables no relevantes y traducción de categorías (Rango y Generación) del inglés al español.

* Análisis Descriptivo Univariante: Cálculo de promedios, medianas, modas, cuartiles, varianza y coeficientes de variación para cada estadística base.

* Visualización Comparativa: Creación de diagramas de caja (Boxplots) agrupados por generación para identificar datos atípicos y estabilidad.

* Análisis Bivariante: Cálculo de coeficientes de correlación de Pearson y gráficos de dispersión con líneas de regresión para analizar la relación entre Ataque/Defensa y   Ataque Especial/Defensa Especial.

### Notas de los Autores

"Escoger a un Pokémon tomando en cuenta estas observaciones otorga una ventaja táctica; sin embargo, es la implementación de estrategias basadas en datos lo que asegura la victoria en el ámbito competitivo." — David Bermúdez y María Ruiz.

</div>
