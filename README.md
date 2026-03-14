A Multimodal Retrieval-Augmented Generation (MRAG) Pipeline for extracting and retrieving information from research documents such as PDFs.
The pipeline processes text, tables, and images, stores embeddings in a vector database, and enables efficient retrieval for downstream AI applications.

📌 Features

📄 PDF Document Processing

🔎 Text Extraction

📊 Table Extraction

🖼 Image Extraction

🧠 Embedding Generation

🗂 Vector Database Storage (ChromaDB)

⚡ Retrieval-Augmented Generation Pipeline

⚙️ Installation

Clone the repository:

git clone https://github.com/your-Dinnesh G R/MRAG-Pipeline.git
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
GitHub: https://github.com/Dinnesh G R
