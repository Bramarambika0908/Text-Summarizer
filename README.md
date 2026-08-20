# 📝 Text Summarizer

An AI-powered **Text Summarization application** that uses a fine-tuned **T5 (Text-to-Text Transfer Transformer)** model to generate concise summaries from dialogue or text.

*The main objective of this project is to demonstrate how **Transformer-based Natural Language Processing models** can be integrated into a practical web application for automatic text summarization.
* It combines **Deep Learning, NLP, Transformers, FastAPI, and Hugging Face** to create an end-to-end AI application.

* The trained model is hosted separately on Hugging Face rather than being stored directly in this GitHub repository.
---

## 🚀 Features

-  AI-based text/dialogue or convo summarization
- 🧠 **Fine-tuned T5 Transformer model**
-  FastAPI REST API
-  Simple web interface
-  **NLP Text preprocessing and cleaning** 
-  Automatic text truncation for long inputs
-  Beam search-based summary generation
- **Model hosted on Hugging Face**

##🛠️ Technologies Used &📦 Requirements

* Python 3.7+ 
* Required Python packages (listed in requirements.txt)

## Installation

1. Clone the repository
2. 2. Install the required packages:
[**pip install -r requirements.txt**]

### Model
The application loads the fine-tuned T5 model and tokenizer from Hugging Face.
**Hugging Face Model:**
`vadluriBramarambika/text-summarizer-model`

The application loads the model from the `saved_summary_model` subfolder and the tokenizer from the `saved_summary_tokenizer` subfolder.

## ☁️ Deployment

**Usage**
-Run the application:
- The application will be available at: 
```text
http://127.0.0.1:8000
```
**LINK**
[TEXT_Summary](http://127.0.0.1:8000/)
