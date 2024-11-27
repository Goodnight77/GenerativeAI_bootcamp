### 2. [Introduction to Retrieval-Augmented Generation (RAG)](02-into-to-RAG/)


## Overview

This workshop provides a gentle introduction to Retrieval-Augmented Generation (RAG) systems using an open-source model, specifically Llama 3.1. Participants will learn how to create a simple RAG application that answers questions from a PDF document.

## Objectives

By the end of this workshop, participants will be able to:

- Understand the concept of Retrieval-Augmented Generation.
- Set up a Python environment with the necessary libraries.
- Load and preprocess a PDF document.
- Split the document into manageable chunks.
- Store these chunks in a vector store.
- Retrieve information based on user queries.

## Requirements

Participants should have:

- Basic knowledge of Python programming.
- Anaconda or Miniconda installed.
- Familiarity with Jupyter Notebooks.

## Setup Instructions

1. **Clone the Repository**
   ```bash
   git clone https://github.com/Goodnight77/GenerativeAI_bootcamp.git
   cd 02-into-to-RAG
2. **Create a Conda Environment**
  ```bash
  conda create -n rag python=3.10
  conda activate rag
3. **Install Required Libraries**
  ```bash
  pip install torch transformers langchain-community langchain-huggingface   faiss-cpu
4. **Run the Jupyter Notebook**
  ```bash
  jupyter notebook
5. **Open the notebook RAG.ipynb**

