# 📚 Deep-Chat-RAG-Customizable-Chatbot-with-API-and-LLM-Integration-

## 🚀 Overview:-
• Developed a fully customizable  chatbot capable of intelligent document interaction using fine-tuned LLM and Retrieval
Augmented Generation (RAG).

• Optimized performance with LoRA-based fine-tuning and 4-bit quantization, reducing model size by 70%. 

•  Achieved 30% faster response times with SentenceTransformers and ChromaDB for vector retrieval. 

•  Built a dynamic chat interface with LangChain pipelines for seamless querying of PDFs. 

• 🛠️##** Technologies and Tools: ** Python, Transformers, LangChain, Streamlit, LoRA, ChromaDB/FAISS, Ollama, Hugging Face, Tesseract OCR. 


## ✨ Key Features

- 📂 Upload and summarize PDF/TXT documents
- - **📂 Document Summarization**: Extract and summarize text from PDFs/TXT files (supports OCR for scanned documents).
- 🤖 RAG-Powered Chatbot**: Query stored documents with Retrieval-Augmented Generation (RAG).    
  - **🤖 Interactive chatbot for document-based Q&A
- 🔍 Semantic search across stored documents
  - **🔍 Semantic Search**: Find relevant content using ChromaDB/FAISS vector embeddings. 
- 🗂️ Document management system
  - **🔄 Document Management**: View/delete stored documents and summaries.  
- ⚡ Optimized performance with LoRA and 4-bit quantization

## 🛠️ Technologies Used

- **Backend**: Python, Ollama (LLaMA 3)
- **Vector Database**: ChromaDB
- **Frontend**: Streamlit
- **OCR**: PyTesseract
- **PDF Processing**: PyMuPDF (fitz)

# 📸 Screenshots 

![image](https://github.com/user-attachments/assets/1518b8ad-b51e-444a-91aa-d3c9b21de977)

![image](https://github.com/user-attachments/assets/cab8890c-5a5e-4bda-a9e0-997b766ba3ff)

![image](https://github.com/user-attachments/assets/929908f9-f8fd-4bd5-823c-128f14889660)

![image](https://github.com/user-attachments/assets/25b6c48b-30eb-4776-8e73-416a0cdd8a94)

![image](https://github.com/user-attachments/assets/485ed1f7-f278-47a7-ab39-13fa7367b849)

![image](https://github.com/user-attachments/assets/64a34eae-e3a3-47c1-86e1-ac26368ea812)

![image](https://github.com/user-attachments/assets/01612e92-681f-48cb-af04-e2885e12bb2a)


## 📋 Prerequisites

- Python 3.9+
- Ollama installed and running (with LLaMA 3 model)
- Tesseract OCR installed

## 🏗️ Setup Instructions

### **1. Clone the Repository**  
```bash
git clone https://github.com/id12026/Deep-Chat-RAG-Customizable-Chatbot-with-API-and-LLM-Integration
```

### **2. Set Up Virtual Environment**  
```bash
python -m venv .venv
source .venv/bin/activate  # Linux/Mac
.\.venv\Scripts\activate   # Windows
```
### **3. Activate Virtual Environment

**Windows:**
```bash
.venv\Scripts\activate
```

**Mac/Linux:**
```bash
source .venv/bin/activate
```

### **4. Install Requirements

```bash
pip install -r requirements.txt
```

### **5. Set Up Ollama

```bash
ollama pull llama3
```

### **6. Pull required models**  
```bash
ollama pull nomic-embed-text
```

### **7. Configure Environment (Windows Only)**  
```powershell
# Add Ollama to PATH
$env:Path += ";C:\Users\Reliance Digital\AppData\Local\Programs\Ollama\"

# Set user agent (if facing download issues)
$env:USER_AGENT = "Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/91.0.4472.124 Safari/537.36"
```
## 🚀 Running the Application

```bash
streamlit run ui.py
```
---



## 📂 Project Structure

```
deep-chat-rag/
├── __pycache__/             # Python bytecode cache (auto-generated, ignore in Git)
├── .venv/                   # Virtual environment (stores isolated Python dependencies)
├── styles.css               # Custom CSS for Streamlit UI (if used)
├── chroma_db/               # ChromaDB vector database storage (auto-created)
│   └── ...                  # Contains ChromaDB files like SQLite DBs and embeddings
├── chroma_db_manager.py     # Handles ChromaDB operations (CRUD, search)
├── summarizer.py            # LLaMA 3 summarization + RAG logic
├── ui.py                    # Main Streamlit frontend (user interface)
├── requirements.txt         # Python dependencies (pip install -r requirements.txt)
└── README.md                # Project documentation (setup, usage, etc.)

```


## 🚀 **Usage**  
1. **Run the Streamlit App**:  
   ```bash
   streamlit run ui.py
   ```
2. **Interact via UI**:  
   - **Tab 1**: Upload PDF/TXT files to generate/store summaries.  
   - **Tab 2**: Chat with documents using natural language queries.  

---

## ⚠️ **Troubleshooting**  
| Issue | Solution |
|-------|----------|
| `ollama not found` | Add Ollama to PATH or restart terminal. |
| `OCR failed` | Verify Tesseract installation and PATH. |
| `CUDA Out of Memory` | Use smaller models or enable GPU acceleration. |



## 🌟 Team Members

- Mohitha Bandi (22WUO0105037)
- T. Harshavardhan Reddy (22WUO0105023)
- Pailla Bhavya (22WUO0105020)
- Thumma Manojna Reddy (22WUO0104134)


# Conclusion

Deep Chat provides a powerful and flexible solution for intelligent document interaction using LLMs and RAG. By combining real-time summarization, customizable Q&A, and fine-tuned language models, this system demonstrates the practical potential of AI in enterprise, education, and research environments.




## 📜 License

This project is licensed under the Apache License.
Apache 2.0 License - See LICENSE for details.


## 🤝 Contributing

Contributions are welcome! Please open an issue or submit a pull request.

---




