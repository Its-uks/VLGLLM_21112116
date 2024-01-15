LLM - Detecting AI-Generated Text

This repository comprises code designed to identify AI-generated essays through machine learning methodologies. The model undergoes training using a dataset of essays that are explicitly labeled as either human-written or AI-generated.

Overview

The proliferation of AI-generated content presents challenges across various domains, including essays. This project's objective is to discern AI-generated essays by leveraging a Support Vector Machine (SVM) model trained on a dataset of essays with clear labels.

Dataset

The dataset, accessible in the data directory, encompasses essays classified as either human-written (class 0) or AI-generated (class 1). The dataset is logically divided into training and testing subsets.

Prerequisites

• Python 3
• Jupyter Notebook (for interactive code execution)

Installation

Clone the repository:

git clone https://github.com/yourusername/essay-generator-detection.git
cd essay-generator-detection

Install the necessary dependencies:

pip install -r requirements.txt

Usage

Execute the Jupyter Notebook "Essay_Generator_Detection.ipynb" for both model training and evaluation.
The trained model will be saved, allowing you to utilize it for predicting whether a given essay is AI-generated.

Results

• The model demonstrates high accuracy in identifying AI-generated essays; refer to the ROC curve in the notebook for comprehensive insights.
• The submission file ("submission.csv") contains the predicted probabilities for AI-generated essays within the test set.
