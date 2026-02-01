[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](
https://colab.research.google.com/github/beingrahull/LLM-Based-Multi-URL-Question-Answering-System-RAG-/blob/main/llm_url_qa.ipynb
)


# LLM URL Question Answering (Colab Project)

This project is an LLM-based question answering system that reads
content from multiple URLs and answers user questions using only
the extracted webpage content.

The implementation is done in a Google Colab notebook.

## What this notebook does
- Loads webpage content from given URLs
- Cleans and splits the text into chunks
- Uses LangChain with HuggingFace models
- Answers questions using strictly retrieved context
- Helps reduce hallucinations

## How to run
1. Open the notebook in Google Colab
2. Install required libraries
3. Run cells from top to bottom
4. Enter URLs and a question

## Technologies used
- Python
- Google Colab
- LangChain
- HuggingFace Transformers

## Dependencies
This project lists only the primary dependencies required to run the notebook.
Some libraries (e.g., tokenizers, sentencepiece, unstructured sub-dependencies)
are installed automatically as transitive dependencies.


