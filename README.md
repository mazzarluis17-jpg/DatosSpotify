# HitSignal

Detección de Hidden Gems y búsqueda de similitud acústica utilizando PySpark y datos de Spotify.

## Descripción

HitSignal es un proyecto de análisis de datos masivos que busca identificar canciones poco populares con alto potencial acústico.

El sistema utiliza PySpark para:

- Limpieza de datos
- Análisis exploratorio
- Construcción de un score acústico
- Enriquecimiento con datos de artistas
- Detección de Hidden Gems
- Búsqueda de similitud mediante LSH

## Dataset

- tracks.csv
- artists.csv

Más de 586,000 canciones y 1.1 millones de artistas.

## Tecnologías

- Python
- PySpark
- Spark MLlib
- Parquet

## Resultados

- 11,613 Hidden Gems detectadas
- Similaridad acústica mediante distancia euclidiana
- Escalamiento usando LSH

## Autor

Luis Alfredo Ramírez Maza
