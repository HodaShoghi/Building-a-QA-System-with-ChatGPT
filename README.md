# Question Answering System with ChatGPT

## Overview
This project develops a sophisticated Question Answering System leveraging the capabilities of ChatGPT. It aims to provide answers to user queries based on personal data, integrating a streamlined workflow and advanced natural language processing techniques.

## Detailed Process
In building our question-answering system, the process begins with the user's query, which the system refines to create a well-crafted prompt. This refinement involves using vector search techniques to search through our vector database, created from our data file, for the most relevant text passages or documents that align with the user's query. By combining these relevant pieces with the original query, the system constructs a context-rich prompt for ChatGPT. This approach not only incorporates the user's input but also adds relevant context, guiding ChatGPT to generate a response that is both accurate and contextually relevant. Essentially, the system excels at finding an improved query, merging the user's intent with related information, thus enhancing the overall quality and relevance of ChatGPT's responses.

## Features

- **Download the following**: PDF: https://arxiv.org/pdf/2310.02263.pdf
- **PDF Text Extraction**: Extracts text from PDFs for data processing.
- **Langchain Library Utilization**: Employs Langchain for efficient language-related task handling.
- **ChatGPT Integration**: Leverages ChatGPT for generating human-like, contextually relevant responses.

## Getting Started
### Prerequisites
- Python 3.x
- Libraries: requests, PyPDF2, Langchain, OpenAI

## Usage
- **Text Extraction**: Use the `extract_text_from_pdf` function to extract text from a PDF.
- **Embedding Generation**: Langchain converts text into numerical embeddings for processing.
- **Vector Database Storage**: Stores embeddings for optimized retrieval.
- **Query Processing and Response Generation**: Transforms user queries into embeddings and utilizes ChatGPT for generating responses.

## Workflow Overview
1. Embedding Generation
2. Vector Database Storage
3. Query Processing
4. Similarity Search
5. Prompt Crafting
6. Response Generation

## Contributing
Feel free to fork this repository and submit pull requests. For major changes, please open an issue first to discuss what you would like to change.

