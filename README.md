# SkimMed

SkimMed is an AI-powered application for parsing and analyzing **medical documents**.  
It extracts structured information from uploaded medical PDFs, splits them into manageable chunks, and allows users to query them in natural language using a Hugging Face-hosted LLM.

## ✨ Features
- 📄 **Upload PDF documents** for instant processing.
- ✂️ **Smart text chunking** for better context handling.
- 🤗 **Hugging Face model integration** for decision-making.
- 🖱️ Click-to-view reasoning (keeps the UI clean).
- 🌐 Built with **Gradio** for a simple, interactive interface.

## 🛠️ Tech Stack
- **Python**
- **Gradio** – UI framework
- **PyMuPDF (`fitz`)** – PDF text extraction
- **Sentence Transformers** – text embeddings
- **Hugging Face Hub** – model hosting and inference
- **NumPy** – array operations
- **python-dotenv** – environment variable handling


## 🚀 Getting Started

### 1️⃣ Clone the repo
```bash
git clone https://github.com/your-username/SkimMed.git
cd SkimMed
```

### 3️⃣ Add your Hugging Face API token
Create a .env file:

```env
HF_TOKEN=your_huggingface_token_here
```

Live Demo has been hosted to HuggingFace Spaces: https://huggingface.co/spaces/Kaiyeee/SkimMed

⚠️Note: The account hosting the demo has run out of current month's free token usage limits so the demo run will give an error. Please refer to the SkimMed.ipynb for usage purposes.
