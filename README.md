# Mental_Distress_Detection_ML_NLP_LLM_AI
# Thesis Implementation Documentation

The whole implementation code files and artifacts can be found at: https://drive.google.com/drive/folders/1SJ3ps2Sufe-z_-EdVhQ6DUIKpy7ZNhhs?usp=sharing

In total, around 32 models have been trained with various configurations and categories. It includes ML models (DT, SVM, RF, LR), NN model (CNN, RNN, LSTM) followed by DL models(BERT, Distil_BERT RoBERTA, Mental_BERT).
ML and NN models are trained on all 4 feature representation techniques that includes TF-IDF, Word2Vec, GloVe and BERT_Embeddings.

My Best Fine Tuned Language Model can also be found at: https://huggingface.co/slimshady07/Mental_BERT 

## Overview
This document explains the folder structure and implementation details of the thesis project, along with instructions for reproducibility.

## Getting Started

### Reproducibility Steps
1. Extract the zipped folder
2. Open Command Prompt (CMD):
   - Start the command prompt from the Start menu or by typing `cmd` in the Windows search bar
3. Navigate to the Project Folder:
   - Use the `cd` command to navigate to the root directory "Thesis"
   - Example: `cd C:\Users\shahb\Thesis` (Include quotes if your path contains spaces)
4. Launch Jupyter Notebook:
   - Execute command: `jupyter notebook`

## Project Structure

The project follows this hierarchical structure:

```
Thesis (Root folder)
└── Modelling (Main directory)
```

### Modelling Directory Contents

The Modelling directory contains 12 specialized folders, each serving a specific purpose in the thesis implementation:

#### 1. raw_dataset
- Contains the original dataset in both zip and .csv formats

#### 2. cleaned_dataset
- Contains Jupyter notebook Python script
- Outputs two cleaned and differently preprocessed datasets

#### 3. exploratory_data_analysis
- Contains Jupyter notebook with EDA analysis
- All analysis outputs are embedded within the notebook

#### 4. tfidf_vect
- Jupyter notebook implementing TF-IDF vectorization
- End-to-end training of various ML and NN models
- Contains:
  - TF-IDF vectorization file
  - Final trained model files
  - Model outputs within the notebook

#### 5. word2vec_vect
- Jupyter notebook implementing Word2Vec vectorization
- End-to-end training of various ML and NN models
- Contains:
  - Word2Vec vectorization file
  - Final trained model files
  - Model outputs within the notebook

#### 6. glove_vect
- Jupyter notebook implementing GloVe vectorization
- End-to-end training of various ML and NN models
- Contains:
  - GloVe vectorization file
  - Final trained model files
  - Model outputs within the notebook

#### 7. bert_embeddings
- Jupyter notebook implementing BERT embeddings vectorization
- End-to-end training of various ML and NN models
- Contains:
  - BERT embeddings vectorization file
  - Final trained model files
  - Model outputs within the notebook

#### 8. bert_models
- Jupyter notebook for BERT transformer family models
- End-to-end fine-tuning and modeling
- Contains final trained model files
- Results embedded within the notebook

#### 9. interpretability
- Jupyter notebook for model interpretability analysis
- Contains:
  - Decision tree visualization PDF
  - Additional required files
  - Analysis results within the notebook

#### 10. validation
- Jupyter notebook for external validation analysis
- Contains:
  - Two external datasets
  - Validation results on unseen data
  - Analysis outputs within the notebook

#### 11. visualizations
- Jupyter notebook recreating best model implementations
- Generates documentation visualizations
- Includes:
  - Comparative analysis of different models
  - Model category comparisons
  - Preprocessing technique impact analysis

#### 12. artifacts
- Contains:
  - Methodology diagram
  - Comparative analysis charts (SVG format)
