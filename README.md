# DeFine_Dataset
We present a high-quality, hierarchically decomposed, and fine-grained annotated dataset specifically designed for long-form article generation (LFAG). It addresses key challenges such as maintaining logical consistency, comprehensive topic coverage, and narrative coherence across extended articles. The dataset includes detailed annotations at three main stages of long-form article generation: outline creation, reference retrieval and extraction, and question-answer data generation.

## Dataset Overview
DeFine consists of three main types of data:

**Outline Data**: Hierarchical outlines extracted from high-quality articles, providing a structured framework for article generation.

**Summary Data**: Summarized content from references, helping models generate concise summaries.

**RAG Data**: Includes question-answer pairs generated from references, ensuring the content is both informative and contextually accurate.

## Key Features
**Multi-agent collaboration pipeline**: Four specialized agents contribute to dataset creation, including Data Miner, Cite Retriever, Q&A Annotator, and Data Cleaner.

**Multi-language Support**: The dataset includes both Chinese and English articles across various domains such as science, humanities, history, geography, and more.

**High-quality annotations**: Each data type is meticulously annotated to support the generation of coherent and accurate long-form articles.

## Usage   
This dataset can be used to fine-tune models for long-form article generation tasks, improve citation reliability, and enhance the accuracy of content generation models. It provides structured data that supports multi-step decomposition for improved content synthesis.
## Dataset Files    
The dataset is organized into the following categories:

outline_data/

summary_data/

rag_data/

