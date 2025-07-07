# 📚 Business FAQ RAG Bot

A lightweight Retrieval-Augmented Generation (RAG) bot for answering business-related queries using free tools — Hugging Face, Pinecone, and Gradio.

---

## 🚀 Features

- ✅ Semantic search using `all-MiniLM-L6-v2` (sentence-transformers)
- ✅ Fast retrieval with Pinecone vector DB
- ✅ Answer generation via `flan-t5-base` (Hugging Face, no API key required)
- ✅ Gradio UI for smooth interaction
- ✅ No OpenAI key or billing needed

---

## 🛠️ Tech Stack

| Component        | Tool Used               |
|------------------|-------------------------|
| Embeddings       | `sentence-transformers` |
| Vector Database  | `pinecone` (v3+)        |
| LLM (Answering)  | `flan-t5-base` (HF)     |
| UI               | `gradio`                |
| Language         | Python                  |

---

## 🔧 Setup Instructions

1. **Install requirements:**

```bash
pip install sentence-transformers pinecone transformers gradio

Run the app:
# In your notebook or .py file
interface.launch(share=True)

Ask Questions:
"What are your business hours?"
"How can I reset my password?"

📦 Folder Structure
business-faq-rag-bot/
│
├── doc/                                    # Your business FAQ docs (optional)
├── business-fag-rag-bot.ipynb              # Main Colab notebook
├── README.md                               # Project readme

✨ Demo
🔗 Try Live on Gradio (if deployed)

📄 License
This project is free and open-source under the MIT License.

🙋‍♀️ Author
Built with ❤️ by Sara Mamatha
