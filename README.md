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

python
Copy code
# In your notebook or .py file
interface.launch(share=True)
Ask Questions:

"What are your business hours?"

"How can I reset my password?"

📦 Folder Structure
graphql
Copy code
business-faq-rag-bot/
│
├── data/                  # Your business FAQ docs (optional)
├── app.ipynb              # Main Colab notebook
├── README.md              # Project readme
✨ Demo
🔗 Try Live on Gradio (if deployed)

📄 License
This project is free and open-source under the MIT License.

🙋‍♀️ Author
Built with ❤️ by [Your Name]

markdown
Copy code

---

### ✅ To Use:
1. Create a file called `README.md` in your repo.
2. Paste the entire content above into it.
3. Replace `[Your Name]` with your actual name.
4. (Optional) Add a `LICENSE` file if you want to mention open-source usage.

Let me know if you want a downloadable `.md` file or want help writing a `requirements.txt` or `LICENSE`.

2/2







You said:
only giev content at once topaste diractly


ChatGPT said:
Sure! Here's the complete README.md content you can copy and paste directly:

markdown
Copy code
# 📚 Business FAQ RAG Bot

A lightweight Retrieval-Augmented Generation (RAG) bot for answering business-related queries using free tools — Hugging Face, Pinecone, and Gradio.

## 🚀 Features

- ✅ Semantic search using `all-MiniLM-L6-v2` (sentence-transformers)
- ✅ Fast retrieval with Pinecone vector DB
- ✅ Answer generation via `flan-t5-base` (Hugging Face, no API key required)
- ✅ Gradio UI for smooth interaction
- ✅ No OpenAI key or billing needed

## 🛠️ Tech Stack

- Sentence Transformers (`all-MiniLM-L6-v2`)
- Pinecone (Vector DB)
- Hugging Face Transformers (`flan-t5-base`)
- Gradio (UI)
- Python

## 🔧 Setup Instructions

1. **Install requirements:**

```bash
pip install sentence-transformers pinecone transformers gradio
Run the app:

python
Copy code
interface.launch(share=True)
Ask Questions like:

"What are your business hours?"

"How can I reset my password?"

"How do I cancel my subscription?"

📁 Folder Structure
bash
Copy code
business-faq-rag-bot/
├── app.ipynb              # Main notebook
├── README.md              # Project readme
└── data/                  # (Optional) FAQ data files
✨ Demo
🔗 Try live on Gradio (if deployed): https://gradio.live

📄 License
This project is free and open-source under the MIT License.

🙋‍♀️ Author
Built with ❤️ by Sara Mamatha
