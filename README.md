# Multimodal Pet Re-Identification

<p align="center">
<img src="project_pipeline.png" width="600">
</p>

A computer vision system designed to identify individual pets using multimodal visual features.

This project explores how deep learning models can recognize animals using **facial landmarks, region-based embeddings, and transformer-based feature fusion**.



# Problem

Lost pets are difficult to identify when sightings occur in different locations.

Traditional identification methods rely on:

- microchips
- collars
- manual recognition

However, these approaches fail when visual confirmation is needed.

Computer vision can enable **automatic pet identification from images**, helping reconnect lost pets with their owners.



# Proposed Approach

The system uses **multimodal feature extraction** to identify pets based on their visual characteristics.

Key steps:

1. detect facial landmarks
2. extract key facial regions
3. generate embeddings using deep neural networks
4. compare embeddings to identify the same animal

This approach enables **re-identification rather than simple classification**.



# Project Pipeline

<p align="center">
<img src="project_pipeline.png" width="550">
</p>

The overall workflow includes:

1. input image of animal
2. facial landmark detection
3. region extraction
4. feature embedding generation
5. similarity matching

The model learns unique visual patterns for each individual animal.



# Dataset Preparation

<p align="center">
<img src="dataset_pipeline.png" width="500">
</p>

Datasets used include several pet and animal datasets containing images of dogs and cats.

Key preprocessing steps:

- facial landmark detection
- region extraction (eyes, nose, ears)
- image normalization
- dataset splitting

Region extraction improves identification accuracy by focusing on distinctive facial patterns.



# Model Architecture

<p align="center">
<img src="architecture_model.png" width="550">
</p>

The system uses a deep learning architecture combining:

- convolutional feature extraction
- transformer-based embeddings
- feature fusion layers
- similarity matching

This design allows the model to capture fine-grained visual differences between animals.



# Technologies Used

| Component | Technology |
|||
| Programming | Python |
| Deep Learning | PyTorch |
| Vision Models | CNN / Transformer architectures |
| Data Processing | OpenCV |
| Development Environment | Jupyter Notebook |



# Results

<p align="center">
<img src="results_overview.png" width="500">
</p>

The model was evaluated on pet image datasets to measure identification performance.

Key observations:

- region-based features improved identification accuracy
- transformer embeddings improved feature representation
- multimodal feature fusion improved matching performance

The results demonstrate the feasibility of **AI-based pet identification systems**.



# Applications

Potential real-world applications include:

- lost pet recovery
- animal shelter identification
- wildlife monitoring
- animal research datasets



# Future Work

Future improvements could include:

- larger training datasets
- real-time mobile deployment
- multimodal inputs such as text descriptions
- improved transformer architectures



# Author

**Vennela Mangala Venkatesha**  
Master of Artificial Intelligence  
University of Auckland
