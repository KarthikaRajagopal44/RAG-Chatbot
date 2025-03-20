# RAG-Chatbot

# RAG Chatbot Demo 🚀

This repository contains a **Retrieval-Augmented Generation (RAG) Chatbot** using FAISS for efficient document retrieval and LLM-based response generation.

🔗 **[Live Demo](https://huggingface.co/spaces/KarthikaRajagopal/RAG_Chatbot)**  
*(Click the link above to try the chatbot!)*

---

## **🛠 How It Works**
1. **Embedding Model:** [`mixedbread-ai/mxbai-embed-large-v1`](https://huggingface.co/mixedbread-ai/mxbai-embed-large-v1)  
   - Converts text into dense vector embeddings.
  
2. **Dataset:** [`KarthikaRajagopal/wikipedia-2`](https://huggingface.co/datasets/KarthikaRajagopal/wikipedia-2)  
   - Wikipedia-based dataset used for retrieval.

3. **FAISS Indexing:** [FAISS Documentation](https://huggingface.co/docs/datasets/v2.18.0/en/package_reference/main_classes#datasets.Dataset.add_faiss_index)  
   - Speeds up similarity search for document retrieval.

4. **Chatbot Model:** [`Meta-Llama-3-8B-Instruct`](https://huggingface.co/meta-llama/Meta-Llama-3-8B-Instruct)  
   - Generates responses based on retrieved documents.

---

## **🚀 Running the Chatbot Locally**
Clone this repository and install dependencies:

```sh
git clone https://github.com/KarthikaRajagopal44/RAG-Chatbot.git
cd RAG_Chatbot
pip install -r requirements.txt
