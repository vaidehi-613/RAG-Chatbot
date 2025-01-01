# Dr. Bot: Your Personalized Medical Guide

Dr. Bot is a domain-specific chatbot designed to assist users with medical questions by providing reliable information from the **Gale Encyclopedia of Medicine**. It uses a **Retrieval-Augmented Generation (RAG)** pipeline to ensure accurate and context-aware responses.

---

## Features

- **Medical Expertise**: Answers questions about medical conditions, treatments, and potential diagnoses.
- **RAG Architecture**: Combines data retrieval with large language models for precise and relevant answers.
- **User-Friendly Interface**: Deployed via Gradio for an intuitive user experience.

---

## Project Goals

1. Build a chatbot capable of answering complex medical questions.
2. Ensure accuracy by using the Gale Encyclopedia of Medicine.
3. Utilize state-of-the-art machine learning techniques to enhance performance.

---

## How It Works

### Retrieval-Augmented Generation (RAG)
1. **Data Ingestion**: Index medical documents into a vector database.
2. **Retrieval**: Fetch relevant context from the indexed data based on user queries.
3. **Answer Generation**: Use an LLM to generate responses based on retrieved context.

### Libraries and Tools

- **LangChain**: For document ingestion, chunking, and RAG pipeline implementation.
- **Chroma**: A vector database for storing and retrieving embeddings.
- **SentenceTransformerEmbeddings**: Maps text to vector space for efficient retrieval.
- **Ollama**: Integrates the Mistral LLM for local execution of queries.
- **Gradio**: Provides an interactive chatbot interface.

---

## Project Workflow

1. **Requirement Analysis**: Define project goals and scope.
2. **Document Preparation**: Extract and preprocess text from academic sources.
3. **Chunking**: Divide text into manageable sections for embedding.
4. **Embedding**: Generate vector representations of text and store them in a database.
5. **Pipeline Setup**: Integrate LLM, vector retriever, and custom prompts into a functional RAG pipeline.
6. **Evaluation**: Test the chatbot with sample queries to ensure accuracy.
7. **Deployment**: Deploy the chatbot using Gradio for end-user interaction.

---

## Credits

- **Team Members**: Carlos Lopez, Vaidehi Pawar, & Bibianca Baarh
- **Core Libraries**: LangChain, Chroma, Gradio
- **Special Thanks**: Gale Encyclopedia of Medicine for providing the knowledge base.

