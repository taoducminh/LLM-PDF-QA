# LLM PDF QA with RAG and ChatUI

This repository contains a Jupyter Notebook that implements a Question-Answering (QA) system using a large language model (LLM), Retrieval-Augmented Generation (RAG), and a Chat User Interface (ChatUI). The system is designed to handle questions related to PDF documents.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [File Structure](#file-structure)
- [Contributing](#contributing)
- [License](#license)

## Introduction

This notebook demonstrates how to create a QA system that leverages the power of large language models and retrieval-augmented generation. The system is particularly suited for answering questions based on the content of PDF documents.

## Features

- **Large Language Model (LLM)**: Utilizes advanced language models for understanding and generating human-like text.
- **Retrieval-Augmented Generation (RAG)**: Combines the strengths of information retrieval and generative models to provide accurate and contextually relevant answers.
- **Chat User Interface (ChatUI)**: Provides an interactive interface for users to ask questions and receive answers in real-time.
- **PDF Document Handling**: Specifically designed to process and answer questions related to the content of PDF documents.

## Requirements

To run the notebook, you need the following dependencies:

- Python 3.8+
- Jupyter Notebook
- pandas
- numpy
- PyMuPDF (fitz)
- transformers
- faiss-cpu
- torch
- langchain

## Installation

1. Clone the repository:

    ```sh
    git clone https://github.com/taoducminh/LLM_PDF_QA_RAG_With_ChatUI.git
    cd LLM_PDF_QA_RAG_With_ChatUI
    ```

2. Install the required Python packages:

    ```sh
    pip install -r requirements.txt
    ```

3. (Optional) Install Jupyter Notebook if you don't have it:

    ```sh
    pip install notebook
    ```

## Usage

1. Start Jupyter Notebook:

    ```sh
    jupyter notebook
    ```

2. Open the `LLM_PDF_QA_RAG_With_ChatUI.ipynb` notebook and run the cells to initialize the QA system.

3. Upload your PDF documents as instructed in the notebook and start asking questions via the provided ChatUI.

## File Structure

- `LLM_PDF_QA_RAG_With_ChatUI.ipynb`: The main notebook file implementing the QA system.
- `requirements.txt`: List of required Python packages.
- `README.md`: This readme file providing an overview and instructions.

## Contributing

We welcome contributions to improve this project! Please follow these steps to contribute:

1. Fork the repository.
2. Create a new branch: `git checkout -b feature-branch-name`.
3. Make your changes and commit them: `git commit -m 'Add some feature'`.
4. Push to the branch: `git push origin feature-branch-name`.
5. Submit a pull request.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

