# HitSignal

Hidden Gem Detection and Acoustic Similarity Search using PySpark and Spotify Data

## Overview

HitSignal is a Big Data project developed with PySpark to identify low-popularity songs with high acoustic potential. The project combines audio features, artist metadata, and similarity search techniques to discover songs that may have been overlooked despite sharing characteristics with successful tracks.

The system processes Spotify datasets, enriches track information with artist data, computes an acoustic score, and identifies "Hidden Gems" based on popularity, recency, artist exposure, and acoustic similarity.

## Features

* Large-scale data processing with PySpark
* Data cleaning and exploratory data analysis (EDA)
* Artist enrichment through dataset joins
* Acoustic scoring system
* Hidden Gem detection pipeline
* Exact similarity search
* Approximate similarity search using LSH
* Reproducible ETL workflow

## Dataset

The project uses:

* Spotify Tracks Dataset
* Spotify Artists Dataset

Processed data includes more than:

* 586,000 tracks
* 1.1 million artists

## Technologies

* Python
* PySpark
* Spark SQL
* Spark MLlib
* Parquet
* Jupyter Notebook

## Methodology

1. Clean and validate track records.
2. Perform exploratory data analysis.
3. Build a weighted acoustic score.
4. Enrich tracks using artist metadata.
5. Apply Hidden Gem filters.
6. Remove duplicates.
7. Perform similarity search against popular tracks.

## Results

* 11,613 Hidden Gems identified
* Acoustic similarity matching against hit songs
* Exact and approximate nearest-neighbor search implemented

## Repository Structure

├── notebooks/
├── docs/
├── Archivos/
└── README.md

## Author

Luis Alfredo Ramírez Maza
