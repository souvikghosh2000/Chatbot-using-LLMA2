# Medical Chatbot using LLMA2

This project aims to develop a medical chatbot trained on a dataset to answer questions about medical information extracted from PDFs or Word files.

## Objective

The main objective of this project is to leverage the LLMA2 model to create a chatbot capable of answering medical-related questions based on the provided dataset.

## Steps

1. **LLMA2 Model Usage**:
   The LLMA2 model is utilized locally for training and inference tasks. LLMA2 provides state-of-the-art language understanding capabilities essential for developing an effective medical chatbot.

2. **Word Embedding**:
 Sentence transformers with the MiniLM architecture (all-MiniLM-L6-v2) generate word embeddings. This helps enhance the model's understanding of medical terminology and context, improving the accuracy of responses.

3. **Vector Database using FAAIS**:
   FAAIS (or any suitable vector database) is employed to select word embeddings, enhancing the model's understanding of medical terminology and context. This enriches the vocabulary and semantic representation of the chatbot.

4. **Model Pipeline Creation with Langhain**:
   Langhain is crucial in creating a robust pipeline for the LLMA2 model. It facilitates the integration of preprocessing, model execution, and post-processing steps, ensuring the smooth operation of the chatbot.

5. **Deployment with Streamlit**:
   The chatbot is deployed using Streamlit, a user-friendly framework for building interactive web applications. Deploying the chatbot with Streamlit makes it easily accessible to users, providing a seamless experience for asking medical questions and receiving relevant responses.
