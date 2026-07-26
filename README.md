# Symptoms-Based-Disease-Prediction

An end-to-end Natural Language Processing (NLP) deep learning system that analyzes unstructured, conversational patient symptom descriptions and predicts likely diagnoses across 1,082 unique disease categories.

Specifically, it aims to:

1. Analyze Free-Text Patient Descriptions: Allow users or patients to input symptoms in natural, conversational English (e.g., "I have a high fever, sweating, and severe chills along with a headache") rather than forcing rigid, structured checklists.  

2. Multi-Class Healthcare Classification: Map complex, noisy patient symptom narratives to over 1,082 distinct disease categories with high precision.


What Has Been Used in It?

1. DistilBERT (distilbert-base-uncased): A lightweight, fast transformer language model trained via Knowledge Distillation to understand complex bidirectional language semantics.  

2. PyTorch (torch): Deep learning framework for tensor calculations, GPU memory management, and model execution.  

3. Hugging Face (transformers, datasets): Used to load pre-trained DistilBERT models/tokenizers, handle data collators (DataCollatorWithPadding), and download datasets.  Scikit-Learn (sklearn): Used for dataset splitting (train_test_split), categorical encoding (LabelEncoder), and evaluation metrics (accuracy_score, classification_report, confusion_matrix).
