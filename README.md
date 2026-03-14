📌 Features

📄 PDF Document Processing

🔎 Text Extraction

📊 Table Extraction

🖼 Image Extraction

🧠 Embedding Generation

🗂 Vector Database Storage (ChromaDB)

⚡ Retrieval-Augmented Generation Pipeline

📂 Project Structure
MRAG-Pipeline/
│
├── README.md
├── requirements.txt
├── .gitignore
│
├── notebooks/
│   └── MRAG_Pipeline.ipynb
│
├── data/
│   ├── raw/
│   │   └── attention-is-all-you-need.pdf
│   │
│   └── processed/
│       ├── texts/
│       ├── tables/
│       └── images/
│
├── vector_store/
│   └── chroma_db/
│
├── database/
│   ├── chroma.sqlite3
│   └── document_store.db
│
├── outputs/
│   └── MRAG_Output/
│
└── src/
    ├── ingestion/
    ├── processing/
    ├── embedding/
    ├── retrieval/
    └── pipeline/
⚙️ Installation

Clone the repository:

git clone https://github.com/your-username/MRAG-Pipeline.git
cd MRAG-Pipeline

Install dependencies:

pip install -r requirements.txt
🚀 Usage

Run the pipeline notebook:

notebooks/MRAG_Pipeline.ipynb

Or run the pipeline script (if implemented):

python src/pipeline/mrag_pipeline.py
🧠 Pipeline Workflow

Document Ingestion

Content Extraction

Text

Tables

Images

Chunking & Embedding

Vector Storage (ChromaDB)

Retrieval for LLM Applications

📦 Technologies Used

Python

ChromaDB

LangChain

PyMuPDF / PDF Processing

Vector Embeddings

Retrieval-Augmented Generation

📊 Example Dataset

The project currently demonstrates the pipeline using the research paper:

Attention Is All You Need

🔮 Future Improvements

Multimodal embeddings for images and tables

LLM integration for answering questions

Web interface for document querying

Support for multiple document formats

👨‍💻 Author

Your Name
GitHub: https://github.com/Dinnesh GR
