# EEG-ActiveMind
# Development of Deep Learning Models to Assess Psychological States from EEG During Physical Activities

## Overview

This repository contains the code and data used in the research project titled **"Development of Deep Learning Models to Assess Psychological States from EEG During Physical Activities"**. The project focuses on bridging the gap between cognitive and physiological assessments during exercise, leveraging EEG and sensor data. The main contribution of this work is the development of a novel deep learning architecture called the **Temporal-Spatial Activity Encoder (TSAE)**, enhanced by the **Dynamic Activity Fusion Strategy (DAFS)** to improve the classification of psychological states during physical activity.

## Abstract

This study aligns with the growing emphasis on psychophysiological frameworks in physical activity research. Traditional methods for activity recognition from EEG and sensor data often fall short due to their inability to handle noisy, multimodal, and temporally unaligned datasets. To overcome these challenges, we propose the **Temporal-Spatial Activity Encoder (TSAE)**, a deep learning model that integrates both spatial and temporal features to classify psychological states during physical activities more accurately. Additionally, the model is enhanced with **Dynamic Activity Fusion Strategy (DAFS)**, which includes adaptive weighting mechanisms, temporal alignment techniques, and contextual refinement processes. These improvements ensure robust performance in real-world, dynamic environments, even in the presence of noise and variability.

### Keywords:
- EEG
- Physical Activity
- Deep Learning
- Psychophysiology
- Multimodal Fusion

## Features

- **TSAE Architecture**: A novel deep learning model that integrates both temporal and spatial features for classifying psychological states from EEG data during physical activity.
- **DAFS Strategy**: An enhancement to TSAE that allows the model to handle noisy, asynchronous, and multimodal data with improved accuracy.
- **Experimental Results**: The model has been validated on real-world datasets, showing superior performance compared to traditional methods.

## Installation

To use this code, you'll need Python 3.6+ and the following dependencies:

- TensorFlow (or PyTorch, depending on the implementation)
- NumPy
- SciPy
- pandas
- scikit-learn
- mne (for EEG data preprocessing)

You can install the required dependencies using `pip`:

```bash
pip install -r requirements.txt
