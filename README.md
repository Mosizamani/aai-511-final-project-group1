# Classical Composer Classification Using Deep Learning

This project was developed for **AAI-511: Deep Learning** in the **Applied Artificial Intelligence Program** at the **University of San Diego (USD)**.

## Project Status

**In Progress**

## Project Overview

The objective of this project is to develop deep learning models capable of identifying the composer of a musical score from MIDI data. The project compares the performance of three deep learning architectures:

* Long Short-Term Memory (LSTM)
* Convolutional Neural Network (CNN)
* Transformer

Each model classifies a musical composition into one of the following composers:

* Johann Sebastian Bach
* Ludwig van Beethoven
* Frédéric Chopin
* Wolfgang Amadeus Mozart

## Project Objectives

* Collect and prepare MIDI data for deep learning.
* Preprocess the MIDI files and perform feature extraction.
* Develop LSTM, CNN, and Transformer models for composer classification.
* Compare the performance of the three models.
* Evaluate each model using classification metrics.
* Optimize model performance through hyperparameter tuning.

## Team Members

* Nisun Alade
* Dina Othman
* Mostafa Zamaniturk

## Project Methodology

The project follows the methodology outlined in the course instructions:

1. Data Collection
2. Data Preprocessing
3. Feature Extraction
4. Model Building
5. Model Training
6. Model Evaluation
7. Model Optimization

## Project Components

### Data Preparation

* Dataset collection
* Data preprocessing
* Data augmentation
* Exploratory Data Analysis (EDA)

### Feature Extraction

* MIDI processing
* Note extraction
* Chord extraction
* Tempo extraction
* Piano-roll representation

### Deep Learning Models

* Long Short-Term Memory (LSTM)
* Convolutional Neural Network (CNN)
* Transformer

### Model Evaluation

* Accuracy
* Precision
* Recall
* Hyperparameter tuning
* Performance comparison

## Technologies

* Python
* TensorFlow / Keras
* PrettyMIDI
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Jupyter Notebook

## Dataset

The project uses a collection of classical music MIDI files obtained from Kaggle. The classification task includes only the following composers:

* Bach
* Beethoven
* Chopin
* Mozart

Additional MIDI files may be incorporated only for these four composers if needed to address class imbalance, with proper citation of the data source.

## Deliverables

* Jupyter Notebook containing the complete implementation
* APA 7 Project Report

## References

Blanderbuss. (2022). *MIDI Classical Music Dataset*. Kaggle. https://www.kaggle.com/datasets/blanderbuss/midi-classic-music

## License

This repository is intended for academic use as part of the University of San Diego MS in Applied Artificial Intelligence program.
