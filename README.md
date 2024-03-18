# RAG-a-Thon

## What is RAG-a-Thon?

A RAG-a-Thon is a hackathon focused on RAG (Retrieval-Augmented Generation) use cases. A RAG application is inherently complex due to its multifaceted nature. It requires integrating various components and infrastructure to create a cohesive application. Tuning and optimizing the performance of RAG models is essential for improving their effectiveness in real-world applications.


## What you get?

During the RAG-a-Thon, participants will be given turnkey access to the following:

1. Embedding and Text-generation models from Hugging Face hosted on Nvidia Triton LLM inference server.
   1. Embedding Models:
   2. Text-generation models: meta-llama/Llama-2-7b-chat-hf and NousResearch/Llama-2-7b-chat-hf from Hugging Face. You need a Hugging Face token to download the models.
2. Vector database for storing embeddings - Milvus, and Qdrant.
3. Jupyter Notebook with Python environment for development
4. Access to Rafay's environment manager to provision the infrastructure.

## Getting Started

### Documentation
1. RAG-a-Thon github repository with sample notebook to get started.
2. Environment Manager

### Steps
1. Create an account on our RAG-a-Thon webpage -. You will receive an email once the environment is provisioned.
2. Click on the link to your Environment Manager instance. <TBD>
3. Open Jupyter notebook from your Environment Manager console. Check out the documents from the RAG-a-Thon repository - https://github.com/RafaySystems/Ragathon-2024/. 
4. Refer the sample notebook for a simple RAG pipeline built using Llama 2 model.
5. Evaluate the model using Ragas library, we evaluate the model based on four metrics. Context precision, recall, faithfulness and answer relevancy. Please learn more about these metrics @ [Ragas Metrics](https://docs.ragas.io/en/stable/concepts/metrics/index.html).
6. Take screenshot of your metrics and share with us. Please use these metrics as a reference to iterate and improve your RAG pipeline.
7. Finally email the metrics along with the Jupyter notebook with your implementation to ragathon@rafay.ai

