# Document Retrieval System

This project demonstrates a simple yet powerful document retrieval system using the Sentence Transformers library. It aims to efficiently find and display sections from a set of pre-defined text segments that best match given queries. This is particularly useful for extracting insights from large documents based on specific user queries.

## Project Overview

The system takes a series of predefined queries and finds the most relevant section from a document. It utilizes the `sentence_transformers` library to generate semantic embeddings for text, which are then used to compute cosine similarities and retrieve the most relevant document section for each query.

### Key Features

- **Semantic Text Matching**: Leverages advanced NLP models to understand the meaning behind texts.
- **Query Based Retrieval**: Finds and displays document sections that best match the user's query.
- **Scalable**: Easily adaptable to handle larger documents or multiple text sources.
