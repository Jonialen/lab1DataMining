# Tarea 2 — Otros algoritmos de aprendizaje no supervisado

Universidad del Valle de Guatemala
Facultad de Ingenieria
Departamento de Ciencias de la Computacion
CC3074 — Mineria de Datos
Semestre I — 2026

## Integrantes

- 23837 Jonathan Diaz
- 23234 Martin Perez
- 23692 Karen Toledo

## Descripcion

Implementacion y analisis de cuatro algoritmos de aprendizaje no supervisado aplicados a conjuntos de datos reales y sinteticos.

## Algoritmos implementados

| Algoritmo | Dataset |
|-----------|---------|
| SVD (Singular Value Decomposition) | MovieLens 100k |
| t-SNE (t-Distributed Stochastic Neighbor Embedding) | Breast Cancer Wisconsin |
| UMAP (Uniform Manifold Approximation and Projection) | Breast Cancer Wisconsin |
| ICA (Independent Component Analysis) | Senales sinteticas |

## Estructura del proyecto

```
tarea2/
├── TAREA2.Rmd       # Documento principal (R Markdown)
├── TAREA2.html      # Informe renderizado
├── breastcancer.csv # Dataset Breast Cancer Wisconsin (UCI)
├── ratings.csv      # Dataset MovieLens 100k
└── figure/          # Graficos generados por knitr
```

## Dependencias

R 4.0 o superior con las siguientes librerias:

```r
install.packages(c("dplyr", "Matrix", "irlba", "Rtsne", "ggplot2", "umap", "fastICA"))
```

## Reproduccion

```r
rmarkdown::render("TAREA2.Rmd")
```

## Datasets

- **MovieLens 100k**: https://grouplens.org/datasets/movielens/100k/
- **Breast Cancer Wisconsin**: https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+(Diagnostic)
