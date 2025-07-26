# Speaker Identification using CNNs

## Overview

Speaker Identification (SID) is the task of identifying the speaker of a given speech audio sample from a set of known speakers. This project involves building a SID system using Convolutional Neural Networks (CNNs).

## Dataset

The dataset consists of a corpus of speech data, where:
- Each folder corresponds to a unique speaker.
- Each folder contains three long-duration WAV audio files of the speaker reading a passage.

## Methodology

1. **Data Preprocessing**: Speech audio is preprocessed to extract meaningful features suitable for model training.
2. **Model Building**: CNN-based classifiers are developed to learn speaker-specific patterns from the audio data.

## Evaluation

- Multiple models are trained and evaluated.
- Performance is assessed using visual plots and comparative analysis.

## Structure

- **Section 2**: Details the implementation methodology.
- **Section 3**: Presents evaluation results using plots.
- **Section 4**: Provides a summary and conclusions.

## How to Execute

Simply open the `speaker_identification.ipynb` file and run all cells.