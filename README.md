# Personal_Assistant
A Retrieval-Augmented Generation (RAG) chatbot powered by Groq’s LLaMA-3.3-70B, ChromaDB, and Gradio UI. It combines your personal knowledge base (PDFs + notes) with live web search (SerpAPI) to provide accurate, context-aware, and real-time answers.

Perfect 🚀 Since you’re using **Google Colab**, here’s a ready-to-use **README.md** file for your project:

---

````markdown
# 🤖 Personal RAG Chatbot with Web Search (Google Colab)

This project is a **Retrieval-Augmented Generation (RAG) chatbot** built to run on **Google Colab**.  
It uses **Groq’s LLaMA-3.3-70B** for reasoning, **ChromaDB** for local vector storage, and **SerpAPI** for real-time web search.  
The chatbot answers from your **personal knowledge base (PDFs + notes)** first, and falls back to **live web search** when needed.  
Everything is wrapped in a simple **Gradio UI**.

---

## ✨ Features
- 📂 Upload PDFs into a **local knowledge base**.  
- 📝 Add your own custom notes.  
- 📊 Persistent **ChromaDB** storage (auto-created in Colab runtime).  
- 🌐 **Web Search with SerpAPI** for up-to-date information.  
- ⚡ Powered by **Groq LLaMA-3.3-70B** for fast inference.  
- 💻 **Gradio Chat UI** with separate tabs for chatting & knowledge upload.  

---

## 📦 Setup in Google Colab

1. Open the notebook in **Google Colab**.  

2. Install dependencies:
   ```python
   !pip install langchain langchain-groq chromadb gradio sentence-transformers serpapi
````

3. Set your **API keys**:

   ```python
   GROQ_API_KEY = "your_groq_api_key"
   SERPAPI_API_KEY = "your_serpapi_api_key"
   ```

4. Create a `data/` folder in Colab for storing your PDFs:

   ```python
   import os
   os.makedirs("data", exist_ok=True)
   ```

5. Run the script (`app.py` or directly in Colab cells).

---

## ▶️ Running the App

```python
!pip install all requirements

run all cells that you want
```

Gradio will provide a **shareable public link** in Colab output.



---

Would you like me to also add a **ready-to-run Colab badge** at the top of the README (so you can click and open it directly in Colab)?
```
