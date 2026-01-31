# Vector Database in Python

This repository demonstrates how to build a **vector database** in Python for **semantic search**. Text is converted into vector embeddings using a pre-trained **SentenceTransformer** model and stored in **ChromaDB**. Queries return the most semantically similar documents instead of relying on exact keywords.

## Features

* Convert text into vector embeddings
* Store embeddings in a lightweight vector database (ChromaDB)
* Perform semantic search based on meaning

## Requirements

* Python 3.6+
* `sentence-transformers`
* `chromadb`

Install dependencies with:

```bash
pip install sentence-transformers chromadb
```

## Usage

See the included Python scripts for examples of:

* Loading a pre-trained model
* Adding documents to the database
* Performing semantic search
