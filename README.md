# Information Retrieval System from Multiple PDFs 📄🤖 using PaLM2

## Overview
This project allows you to retrieve information from multiple PDF documents using a combination of Python, LangChain, Streamlit, PaLM2, and FAISS. The system processes PDFs to extract text, create embeddings, and enables conversational retrieval of information.
![image](https://github.com/user-attachments/assets/4baa2928-5963-41e2-860f-a5340da3d13f)
![image](https://github.com/user-attachments/assets/8665dd47-1e56-4e8a-b606-46ffa47a301a)


## Features
- Extracts text from multiple PDF files.
- Splits text into manageable chunks.
- Generates embeddings using Google PaLM2.
- Stores embeddings in FAISS for efficient retrieval.
- Provides an interactive Streamlit interface for querying the information.

## Prerequisites
Ensure you have the following installed:
- [Anaconda](https://www.anaconda.com/products/distribution) (for managing the Python environment)
- Python 3.8

## Installation and Setup

### Step 1: Clone the Repository
Clone the project repository from GitHub:
```sh
git clone https://github.com/dwaj-dev/Information-Retrieval-System
cd your-repo-url
```

### Step 2: Create a Conda Environment
Create and activate a new Conda environment:
```sh
conda create -n llmapp python=3.8 -y
conda activate llmapp
```
### Step 3: Install Requirements
Install the required Python packages:
```sh
pip install -r requirements.txt
```
### Step 4: Set Up API Key
Create a .env file in the root directory of the project and add your Google API key:
```sh
GOOGLE_API_KEY=your_google_api_key
```
### Step 5: Run the Application
Start the Streamlit application:
```sh
streamlit run app.py
```
### Access the Application
Open your web browser and go to:
```sh
http://localhost:8501
```
### Tech Stack
- Python: Programming language used for scripting and data processing.
- LangChain: Framework for managing and chaining LLMs (Large Language Models).
- Streamlit: Web framework for creating interactive web applications.
- PaLM2: Google’s language model used for generating embeddings.
- FAISS: Library for efficient similarity search and clustering of dense vectors.

