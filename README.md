# Multimodal RAG for PDF Ingestion and Text Image Output

This project implements a **Multimodal Retrieval-Augmented Generation (RAG)** system that ingests PDF documents and generates outputs containing both **text** and **images** extracted or referenced from the PDFs.

The project leverages two frameworks for document processing, retrieval, and multimodal representation:

* **LangChain**: Provides document processing and PDF ingestion capabilities, with support for structured document workflows and multimodal retrieval.
* **LlamaIndex**: Uses CLIP-based embeddings to enable multimodal representation and improve connections between textual and visual content.

<img width="1462" height="745" alt="Multimodel Rag" src="https://github.com/user-attachments/assets/e6c2f4f8-a1b4-48f9-b5b2-7516ed467a7d" />

## Features

* Ingests PDF files and processes both textual and visual content.
* Generates outputs containing relevant **text and images** from the source documents.
* Supports **multimodal querying** using Retrieval-Augmented Generation.
* Provides modular implementations using **LangChain** and **LlamaIndex**.
* Supports different embedding, retrieval, and generation strategies.

## Working

### `main.ipynb`

A complete implementation of the **Multimodal RAG** pipeline using text and image extraction logic.

The notebook can be used to test the complete workflow end-to-end.

### `tutorials/`

The `tutorials/` folder contains two independent implementations:

* `langchain/`

  * Demonstrates PDF ingestion and document processing using LangChain.
  * Shows multimodal retrieval workflows.
  * Includes examples of integrating models such as **Mistral** for generation.

* `llamaindex/`

  * Demonstrates multimodal retrieval using LlamaIndex.
  * Uses **CLIP-based embeddings** to connect textual and visual content from PDFs.
  * Provides an alternative implementation of the multimodal RAG workflow.
