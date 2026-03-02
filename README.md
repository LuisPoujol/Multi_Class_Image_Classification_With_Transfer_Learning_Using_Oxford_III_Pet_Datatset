# Multi-Class Pet Breed Classification

This project implements a multi-class image classification model to identify 37 different breeds of cats and dogs using the Oxford-IIIT Pet Dataset.

## Project Overview
* **Objective:** Build a robust image classification model to categorize pet breeds.
* **Model:** Utilizes a **Vision Transformer (ViT)** via transfer learning.
* **Performance:** The model achieved high performance with an accuracy of >93%.
* **Interpretability:** Integrated **LIME** (Local Interpretable Model-agnostic Explanations) to visualize and validate the features the model uses for classification.

## Contents
* **Jupyter Notebook:** Contains the data preprocessing, ViT model implementation, training, and LIME interpretability analysis.
* **Report:** A detailed PDF report covering the methodology, performance evaluation, and interpretability insights.

## Methodology
The project leverages transfer learning, using a pre-trained Vision Transformer model to save training resources and time. The model’s decision-making process was analyzed using LIME, which highlighted that the ViT successfully attended to recognizable breed-specific features like face and body shape.
