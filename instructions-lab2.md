Aquí tienes el archivo en formato Markdown (MD) basado en el documento proporcionado :

---

# Laboratorio 2

## Algoritmos de Aprendizaje No Supervisado

**Universidad del Valle de Guatemala**
Facultad de Ingeniería
Departamento de Ciencias de la Computación
CC3074 – Minería de Datos
Semestre I – 2026

---

## INSTRUCCIONES

El estudio *CineVision Studios* está complacido con lo que descubrió en el análisis exploratorio que su equipo le entregó. Sin embargo, le han surgido nuevas interrogantes. En la conformación de su equipo de Data Science, uno de los candidatos comentó que existen algoritmos que permiten detectar patrones no evidentes en los datos y reducir dimensionalidad agrupando variables.

Se le ha pedido profundizar en los datos y extraer información interesante.

---

## Descripción de la consultoría

### 1. Aplicación de algoritmos de Clustering

* Aplicar varios algoritmos de agrupamiento.
* Seleccionar el que tenga mejor calidad para interpretar los grupos.

### 2. Reglas de Asociación

* Aplicar un algoritmo de reglas de asociación.
* Extraer las reglas más interesantes.

### 3. Análisis de Componentes Principales (PCA)

* Reducir la dimensionalidad considerando la gran cantidad de variables.
* Identificar las variables con mayor variabilidad.

### 4. Otros algoritmos de Aprendizaje No Supervisado

Aplicar uno de los siguientes algoritmos:

* SVD (Singular Value Decomposition)
* t-SNE (t-Distributed Stochastic Neighbor Embedding)
* UMAP (Uniform Manifold Approximation and Projection)
* ICA (Independent Component Analysis)

Debe:

* Explicar por qué fue seleccionado.
* Interpretar los resultados obtenidos.

---

## Resultados Esperados

CineVision Studios busca obtener *insights* que permitan explotar mercados no descubiertos por la competencia.

---

## Presentación de resultados

Se debe entregar:

* Informe detallado con hallazgos.
* Explicaciones claras apoyadas con gráficos.
* Código en R o Python.
* Evidencia de aportes del equipo en repositorio GitHub.

---

# DESCRIPCIÓN DEL DATASET

El dataset contiene **19,883 películas** obtenidas de *The Movie DB*.

## Variables

* `id`: Identificador de la película
* `popularity`: Índice de popularidad semanal
* `budget`: Presupuesto
* `revenue`: Ingresos
* `originalTitle`: Título original
* `originalLanguage`: Idioma original
* `title`: Título en inglés
* `homePage`: Página web
* `video`: Indicador de videos promocionales
* `director`: Director
* `runtime`: Duración en minutos
* `genres`: Géneros
* `genresAmount`: Cantidad de géneros
* `productionCompany`: Compañías productoras
* `productionCoAmount`: Cantidad de productoras
* `productionCompanyCountry`: País de productoras
* `productionCountry`: País de producción
* `productionCountriesAmount`: Cantidad de países
* `releaseDate`: Fecha de lanzamiento
* `voteCount`: Número de votos
* `voteAvg`: Promedio de votos
* `actors`: Actores
* `actorsPopularity`: Popularidad del elenco
* `actorsCharacter`: Personajes
* `actorsAmount`: Cantidad de actores
* `castWomenAmount`: Cantidad de actrices
* `castMenAmount`: Cantidad de actores hombres
* `releaseYear`: Año de lanzamiento

---

# ACTIVIDADES

---

## 1. Clustering

### 1.1 Preprocesamiento

* Justificar qué variables no aportan información.
* Definir variables usadas para agrupamiento.

### 1.2 Tendencia al agrupamiento

* Estadístico de Hopkins.
* VAT (si es posible).
* Discusión de resultados.

### 1.3 Determinar número de grupos

* Método del codo.
* Justificación con gráficas.

### 1.4 Algoritmos

* k-means.
* Clustering jerárquico.
* Comparación de resultados.

### 1.5 Calidad del agrupamiento

* Método de la silueta.
* Discusión de resultados.

### 1.6 Interpretación

* Medidas de tendencia central.
* Tablas de frecuencia.
* Hallazgos interesantes.
* Aplicaciones prácticas.

---

## 2. Reglas de Asociación

### 2.1 Algoritmo A Priori

* Discretizar variables numéricas.
* Probar diferentes niveles de soporte y confianza.
* Eliminar variables muy frecuentes si es necesario.
* Discusión de reglas más interesantes.

---

## 3. Análisis de Componentes Principales (PCA)

### 3.1 Transformación de variables categóricas

* Evaluar si vale la pena incluirlas.

### 3.2 Evaluación de viabilidad

* Índice KMO.
* Test de esfericidad de Bartlett.

### 3.3 Aplicación de PCA

* Interpretar componentes.
* Determinar cuántos seleccionar.

---

## 4. Otros Algoritmos

### 4.1 Selección

* Elegir uno de los algoritmos sugeridos.
* Justificar elección.

### 4.2 Interpretación

* Analizar resultados.
* Determinar relevancia de hallazgos.

---

# EVALUACIÓN

## (30 pts) Clustering

* Determinación de número de clusters (5 pts)
* Aplicación y comparación de algoritmos (10 pts)
* Interpretación de grupos (15 pts)

## (20 pts) PCA

* Matriz de correlación
* Pruebas KMO y Bartlett
* Selección e interpretación de componentes

## (15 pts) Reglas de Asociación

* Construcción de reglas
* Ajuste de soporte y confianza
* Discusión de reglas interesantes

## (10 pts) Otros algoritmos

* Aplicación
* Justificación
* Interpretación

## (25 pts) Hallazgos y conclusiones

* Resumen de clustering
* Conclusiones PCA
* Reglas más interesantes
* Resultados de otros algoritmos
* Sugerencias para CineVision Studios

---

# MATERIAL A ENTREGAR

* Archivo `.rmd`, `.ipynb` o Google Docs con informe
* Script de R o Python organizado y comentado
* HTML generado (si aplica)
* Enlace a repositorio

---

# FECHAS DE ENTREGA

### 📌 Lunes 23 de febrero de 2026 – 17:20

**[PASAPORTE] Clustering y PCA**

### 📌 Viernes 27 de febrero de 2026 – 23:59

Documento completo

---

# NOTAS IMPORTANTES

* No se calificará avance fuera de tiempo.
* Miembros ausentes no reciben nota.
* Gráficos y tablas deben estar explicados.
* Se evaluarán contribuciones individuales.

---

Si quieres, puedo prepararte también:

* ✅ Una plantilla lista para `.ipynb`
* ✅ Una plantilla en `.rmd`
* ✅ Una estructura de reporte profesional lista para entregar
* ✅ Un checklist para asegurarte los 100 puntos
