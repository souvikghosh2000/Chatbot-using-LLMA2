# Medical Chatbot using LLMA2

This project aims to develop a medical chatbot trained on a dataset to answer questions related to medical information extracted from documents such as PDFs or Word files.

## Objective

The main objective of this project is to leverage the LLMA2 model to create a chatbot capable of answering medical-related questions based on the provided dataset.

## Steps

1. **LLMA2 Model Usage**:
   The LLMA2 model is utilized locally for training and inference tasks. LLMA2 provides state-of-the-art language understanding capabilities, which are essential for developing an effective medical chatbot.

2. **Word Embeddings from FAAIS**:
   FAAIS (or any suitable vector database) is employed to select word embeddings, enhancing the model's understanding of medical terminology and context. This enriches the vocabulary and semantic representation of the chatbot.

3. **Model Pipeline Creation with Langhain**:
   Langhain plays a crucial role in creating a robust pipeline for the LLMA2 model. It facilitates the integration of preprocessing, model execution, and post-processing steps, ensuring smooth operation of the chatbot.

4. **Deployment with Streamlit**:
   The chatbot is deployed using Streamlit, a user-friendly framework for building interactive web applications. By deploying the chatbot with Streamlit, it becomes easily accessible to users, providing a seamless experience for asking medical questions and receiving relevant responses.
