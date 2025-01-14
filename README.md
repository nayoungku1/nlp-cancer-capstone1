# nlp-cancer-capstone1: 🧬 Context-Based Cancer Diagnosis with Genomic NLP  
Welcome to the repository for my Fall 2024 Capstone Project!  

This project explores how principles from Natural Language Processing (NLP) can be applied to genomics to diagnose cancer. Using embeddings generated from ProtBERT, a pre-trained protein language model, and leveraging deep learning architectures like LSTM, CNN, Transformer, and Attention, this project treats genomic data as a "language" to uncover new biological insights. 🚀  

The repository is under **construction** as I finalize the files and documentation. Stay tuned for updates!

---

## 💡 Key Features  
- **NLP for Genomics**: Applying contextual embeddings to genomic sequences, treating genes as words and sequences as sentences.  
- **Deep Learning Models**:
  - **LSTM**: Captures sequential dependencies in genomic data.  
  - **CNN**: Extracts local patterns in genomic embeddings.  
  - **Transformer Encoder**: Leverages global context using attention mechanisms.  
  - **Multi-Head Attention**: Simplifies the Transformer structure while retaining key relationships.  
- **Dataset**: Processed RNA-seq data translated into amino acid sequences and embedded using ProtBERT.  

---

## 📂 Repository Structure (Planned)  
Once the repository is fully committed, it will be structured as follows:  
- **`data/`**: Processed genomic datasets (in `.npz` format).  
- **`models/`**: PyTorch implementations of LSTM, CNN, Transformer, and Attention-based models.  
- **`results/`**:  
  - AUC-ROC curves, confusion matrices, and performance comparisons across datasets.  
  - Screenshots of key visualizations.  
- **`notebooks/`**: Jupyter notebooks for preprocessing, embedding generation, and training pipelines.  
- **`README.md`**: This file, detailing project goals, setup instructions, and future directions.

---

## 🛠️ Setup Instructions  
### Clone the Repository:  
```bash
git clone <repository-url>
cd cancer-genomics-nlp
```

### Set Up Environment:
Install and activate the environment using Conda:

```bash
conda env create -f environment.yaml
conda activate genomics-nlp
```
### Run the Models:
Training scripts for each model will be in the `notebooks/` directory.
Results (AUC-ROC curves and confusion matrices) will be stored in `results/`.
## 🧠 Project Overview
### Purpose:
To explore how NLP concepts, particularly contextual embeddings, can be applied to genomic data for cancer diagnosis.

### Objectives:
1. Preprocess RNA-seq data into gene-level sequences.
2. Generate ProtBERT embeddings for amino acid sequences.
3. Develop and evaluate deep learning models for binary classification of cancerous vs. normal samples.
4. Compare model performance to identify the best approach.
### Key Results (LSTM Model):
* Train AUC: 0.9543
* Validation AUC: 0.8089
* Test AUC: 0.7067
## 🚀 Future Improvements
* Expand the dataset to include more diverse samples for better generalization.
* Optimize Transformer and Attention models to improve long-range dependency capture.
* Experiment with ensemble methods combining multiple architectures.
## 🤝 Acknowledgments
* Professor Ahn and his lab crew: For supporting datasets and access to amazing servers throughout the capstone project.
* OpenAI: For making this research possible with ProtBERT embeddings.
## 📅 Timeline
* Project Start: September 2024
* Expected Completion: December 2024
* Repository Updates: Ongoing
