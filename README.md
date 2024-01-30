# Music Genre Classification with MFCC and K-Nearest Neighbors

## Table of Contents

- Introduction
-  Project Overview
- Prerequisites
- Usage
- Dataset
- Code Explanation
- Results
   
## Introduction

This project focuses on classifying music genres using the Mel Frequency Cep-
stral Coefficients (MFCC) feature extraction technique and the K-Nearest Neigh-
bors (KNN) algorithm. Music genre classification is a fundamental task in music
analysis, and this project serves as an example of how to perform this task using
Python.

## Project Overview

- MFCC Features: The project utilizes the MFCC features of audio files
to extract relevant characteristics from music tracks.
- K-Nearest Neighbors: KNN is used as the classification algorithm to
predict the genre of a music track based on its extracted features.
- Dataset: The project assumes the availability of a pre-processed dataset
containing audio features. It includes a script to load this dataset and
classify music genres.

## Prerequisites

- Python 3.x
- Required Python packages (install using pip):
- python speech features
- scipy
- numpy
- librosa

## Usage

- Load the dataset: Run the loadDataset function to load your pre-
processed dataset into memory.
- Feature Extraction and Classification:
- Provide the path to your audio file in the wav.read line.
- Adjust the parameters for MFCC feature extraction, such as winlen
and appendEnergy, in the mfcc feat line.
- Set the number of neighbors (k) in the getNeighbors function.
- Run the script to classify the music genre.
   
## Dataset

This project assumes you have a dataset of pre-processed audio features. The
dataset should contain MFCC features and genre labels for training and testing.

## Code Explanation
For a detailed explanation of the code, including how the distance calculation,
neighbor selection, and genre prediction work, please refer to the video file.

## Results

The code provides classification results for the given audio file based on the
trained KNN model. The predicted genre label is output as a result.

