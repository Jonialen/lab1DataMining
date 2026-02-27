# Laboratorio 1: Análisis Exploratorio

**CC3074 - Minería de Datos** **Semestre 1-2026** **Universidad del Valle de Guatemala** 

---

## Introducción

El estudio **CineVision Studios**, especializado en la producción y distribución global de películas, busca mejorar su toma de decisiones basada en datos para maximizar la rentabilidad y satisfacer al público. En un mercado competitivo, enfrentan desafíos como identificar tendencias de popularidad, optimizar presupuestos y atraer al mejor talento. El análisis de datos les permitirá comprender el rendimiento histórico y anticipar el impacto de futuras decisiones.

### Propósitos del Análisis

1. 
**Optimizar la selección de directores y elenco:** Evaluar el impacto de la popularidad de los actores y determinar qué directores generan mayores ingresos y calificaciones.


2. 
**Expandir mercados y audiencias:** Detectar patrones en países de producción, analizar tendencias de idioma y géneros populares.


3. 
**Decisiones estratégicas en marketing:** Evaluar la relación entre videos promocionales y la popularidad.


4. 
**Fomentar la diversidad:** Analizar la representación de género en los elencos e identificar oportunidades para enfoques inclusivos.



---

## Descripción del Dataset

El conjunto de datos contiene información de **19,883 películas** obtenidas de "The movie DB".

### Variables Principales

* 
**id:** Identificador de la película.


* 
**popularity:** Índice de popularidad semanal.


* 
**budget:** Presupuesto de la película.


* 
**revenue:** Ingresos generados.


* 
**originalTitle / title:** Título original y traducido al inglés.


* 
**runtime:** Duración en minutos.


* 
**genres / genresAmount:** Género y cantidad de géneros.


* 
**releaseDate / releaseYear:** Fecha y año de lanzamiento.


* 
**voteCount / voteAvg:** Cantidad y promedio de votos.


* 
**Cast Info:** Popularidad del elenco, cantidad de actores, y desglose por género (hombres/mujeres).



> 
> **Nota:** Algunos datos como la recaudación (`revenue`) no están disponibles para todos los años.
> 
> 

---

## Ejercicios

### 1. Exploración Inicial (3 pts)

Realice un resumen del conjunto de datos para una exploración rápida.

### 2. Clasificación de Variables (5 pts)

Identifique el tipo de cada variable: cualitativa (ordinal o nominal) o cuantitativa (continua o discreta).

### 3. Análisis Estadístico (6 pts)

Investigue si las variables cuantitativas siguen una **distribución normal** y genere tablas de frecuencia para las cualitativas, explicando los resultados.

### 4. Preguntas de Negocio

Responda a las siguientes interrogantes apoyándose en explicaciones y gráficos:

* 
**4.1 - 4.2:** Top 10 de películas con más presupuesto y más ingresos.


* 
**4.3 - 4.4:** Película con más votos y la peor calificada por los usuarios.


* 
**4.5:** Cantidad de películas por año y año con mayor producción (Gráfico de barras).


* 
**4.6:** Género principal de las 20 más recientes, género predominante en el dataset (Gráfico) y género de las películas más largas.


* 
**4.7:** Género principal con mayores ganancias.


* 
**4.8:** Influencia de la cantidad de actores en los ingresos y evolución del tamaño del elenco en años recientes.


* 
**4.9:** Relación entre la proporción de hombres/mujeres en el reparto con la popularidad e ingresos.


* 
**4.10:** Directores de las 20 películas mejor calificadas.


* 
**4.11:** Correlación entre presupuesto e ingresos (Histograma y diagrama de dispersión).


* 
**4.12:** Meses con mejores ingresos y promedio de lanzamientos mensuales.


* 
**4.13:** Correlación entre calificaciones y éxito comercial.


* 
**4.14:** Asociación de meses de lanzamiento con mejores ingresos.


* 
**4.15:** Correlación entre la popularidad del elenco y el éxito de taquilla.


* 
**4.16:** Efectividad de estrategias de marketing (videos, páginas oficiales).



### 5. Preguntas Adicionales (10 pts extra)

Genere y responda **seis preguntas originales** que permitan realizar nuevas exploraciones de los datos.

---

## Material a Entregar

1. 
**Informe (Google Docs):** Debe incluir el enunciado, la explicación detallada y el gráfico de soporte para cada respuesta.


2. 
**Código:** Script en **R o Python** utilizado para el análisis.


3. 
**Repositorio:** Vínculo a GitHub mostrando los aportes del equipo.

