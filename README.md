# 🚀 LangChain Models Playground

A hands-on project exploring **LangChain**, **Hugging Face Models**, and **OpenAI Embeddings**. This repository contains implementations for local LLM inference, embeddings, document similarity, and chat models using modern AI frameworks.

---

## 📌 Features

- 🤖 Local LLM Inference using TinyLlama
- 🌐 Hugging Face Inference API Integration
- 🔍 OpenAI Embeddings
- 📄 Document Similarity Search
- 💬 LangChain Chat Models
- 🔐 Environment Variable Management
- 🧠 Semantic Search & Embeddings

---

## 📂 Project Structure

```bash
Langchain-Models/
│
├── ChatModels/
│   ├── hf_api.py
│   └── hf_local.py
│
├── EmbeddedModels/
│   ├── document_similarity.py
│   ├── hf_query.py
│   └── openai_query.py
│
├── .env
├── requirements.txt
└── README.md
```

---

## ⚙️ Installation

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/langchain-models.git
cd langchain-models
```

### 2️⃣ Create Virtual Environment

```bash
python -m venv myvenv
```

### 3️⃣ Activate Virtual Environment

#### Windows

```bash
myvenv\Scripts\activate
```

#### Linux / macOS

```bash
source myvenv/bin/activate
```

### 4️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

## 🔑 Environment Variables

Create a `.env` file in the project root:

```env
HUGGINGFACEHUB_API_TOKEN=your_huggingface_token
OPENAI_API_KEY=your_openai_api_key
```

---

## 🤖 Local LLM using TinyLlama

Run TinyLlama locally through LangChain and Hugging Face Transformers.

```bash
python ChatModels/hf_local.py
```

Example:

---

```text
What is the capital of India?
→ New Delhi
```

---

## 🌐 Hugging Face Endpoint

Use Hugging Face hosted models through the Inference API.

```bash
python ChatModels/hf_api.py
```

---

## 🔍 OpenAI Embeddings

Generate embeddings using OpenAI models.

```bash
python EmbeddedModels/openai_query.py
```
## 🧠 Hugging Face Embeddings

Generate vector embeddings using Hugging Face models.

```bash
python EmbeddedModels/hf_query.py
```

---

## 📄 Document Similarity

Compare documents using vector embeddings and cosine similarity.

```bash
python EmbeddedModels/document_similarity.py
```

---

## 🛠️ Technologies Used

| Technology | Purpose |
|------------|----------|
| LangChain | LLM Framework |
| Hugging Face | Models & Inference |
| Transformers | Model Loading |
| OpenAI API | Embeddings |
| Python | Development |
| Scikit-Learn | Similarity Computation |
| python-dotenv | Environment Variables |

---

## 📈 Future Enhancements

- Retrieval Augmented Generation (RAG)
- FAISS Vector Database
- ChromaDB Integration
- LangGraph Agents
- PDF Question Answering
- Multi-Model Comparison
- Conversational Memory

---

## 👨‍💻 Author

**Yashashvi Srivastava**

AI & Machine Learning Enthusiast | Exploring LLMs, LangChain, RAG, and Generative AI

---

## ⭐ Support

If you found this project useful, consider giving it a ⭐ on GitHub.

---

## 📜 License

This project is licensed under the MIT License.
