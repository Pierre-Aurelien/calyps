# Saniia Assignment

This repository contains the solution to the two main tasks:

1. **Unsupervised Text Classification** (Huffington Post articles)  
2. **Biomedical Named Entity Recognition (MACCROBAT Simplified)**

---

## Project Structure


- **env.yaml**: Conda environment specification.  
- **data**:  
  - `Huffnews/news.jsonl`: HuffPost dataset.  
  - `MACCROBAT_Simplified/`: TXT + ANN patient files.  
- **saniia**: Modular Python package for data loading, text preprocessing, clustering, evaluation, and biomedical NER.  
- **notebooks**: Contains the jupyter notebooks to train and evaluate the models. 

---

## Installation & Environment Setup

1. Install [Miniconda or Anaconda](https://docs.conda.io/en/latest/miniconda.html).  
2. Create and activate the environment:
   ```bash
   conda env create -f env.yaml
   conda activate saniia
   pip install -e .



