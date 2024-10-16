# Natural Language Processing (NLP) with Hugging Face

This repository provides a comprehensive guide to using 🤗 Transformers.

## Modules

### Module 1: Fundamentals of 🤗 Transformers: From Basics to Fine-Tuning

- [01. Introduction to Transformers Pipeline](https://github.com/AnkitaMungalpara/HuggingFace-NLP/blob/main/00_Transformers_Pipeline_Introduction.ipynb)
  
- [02. Transformer Pipelines: Behind the Scenes](https://github.com/AnkitaMungalpara/HuggingFace-NLP/blob/main/01_Behind_the_scenes_pipeline.ipynb)
  
- [03. Models and Tokenizers](https://github.com/AnkitaMungalpara/HuggingFace-NLP/blob/main/02_Transformers_Models_and_Tokenizers.ipynb)

- [04. Handling Multiple Sequences](https://github.com/AnkitaMungalpara/HuggingFace-NLP/blob/main/03_Handling_Multiple_Sequences_Transformers.ipynb)

- [05. Processing Large Data](https://github.com/AnkitaMungalpara/HuggingFace-NLP/blob/main/04_Processing_Data_Hugging_Face_Transformers.ipynb)
  
- [06. Full Training with GPU and Accelerator](https://github.com/AnkitaMungalpara/HuggingFace-NLP/blob/main/06_Full_Training_HuggingFace_Transformers.ipynb)

- [07. Datasets in HuggingFace](https://github.com/AnkitaMungalpara/HuggingFace-NLP/blob/main/07_Datasets_in_HuggingFace.ipynb)

### Module 2: Fundamentals of 🤗 Datasets and Tokenizers for NLP

This module covers the foundational concepts of working with 🤗 Datasets and 🤗 Tokenizers, preparing to independently solve common NLP tasks.

- [01. Semantic Search with FAISS](https://github.com/AnkitaMungalpara/HuggingFace-NLP/blob/main/08_Semantic_Search_with_FAISS.ipynb)

  <table>
      <thead>
          <tr>
              <th>Section</th>
              <th>Description</th>
              <th>Links</th>
          </tr>
      </thead>
      <tbody>
          <tr>
              <td>0.1 Using embeddings for semantic search</td>
              <td>Introduction to building a semantic search engine using embeddings.</td>
              <td><a href="https://huggingface.co/docs/transformers/index">Transformers Documentation</a></td>
          </tr>
          <tr>
              <td>0.2 Loading and Preparing Dataset</td>
              <td>Loading the GitHub Issues dataset and filtering out pull requests to focus on issues with comments.</td>
              <td><a href="https://huggingface.co/datasets/github">GitHub Issues Dataset</a></td>
          </tr>
          <tr>
              <td>0.2.1 Dataset Information</td>
              <td>Details about the GitHub Issues dataset, including its name, repository, use cases, domain, and language.</td>
              <td><a href="https://huggingface.co/datasets/github">GitHub Issues Dataset Info</a></td>
          </tr>
          <tr>
              <td>0.3 Creating Text Embeddings</td>
              <td>Using the sentence-transformers library to create embeddings for text data, with a focus on pooling techniques.</td>
              <td><a href="https://www.sbert.net/">Sentence-Transformers Documentation</a></td>
          </tr>
          <tr>
              <td>0.4 Using FAISS for Efficient Similarity Search</td>
              <td>Implementing FAISS to create an index for fast similarity searches on the embeddings and conducting nearest neighbor searches.</td>
              <td><a href="https://faiss.ai/">FAISS Documentation</a></td>
          </tr>
      </tbody>
  </table>
