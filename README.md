
# FinRAG: Financial Analysis & Research Assistant 📈🤖

FinRAG is a Retrieval-Augmented Generation (RAG) pipeline designed to act as an AI research assistant for financial analysts. By ingesting complex financial documents (SEC filings, earnings call transcripts, research reports), FinRAG provides accurate, context-aware answers to investment queries without hallucinations.

## 🚀 Features
* **Multi-Source Ingestion:** Automatically fetch and parse 10-Ks, 10-Qs, and earnings transcripts.
* **Contextual Q&A:** Ask complex questions like *"What are the primary risk factors mentioned in Apple's latest 10-K regarding supply chain?"*
* **Source Citations:** Every answer includes direct citations to the source document and page number.
* **Interactive UI:** Built with Streamlit for an easy-to-use chat interface.

## 🛠️ Tech Stack
* **LLM Framework:** [LangChain](https://github.com/langchain-ai/langchain) / [LlamaIndex](https://github.com/run-llama/llama_index)
* **Vector Database:** [ChromaDB](https://www.trychroma.com/) (or FAISS/Pinecone)
* **Embeddings:** OpenAI `text-embedding-3-small` (or open-source alternatives via HuggingFace)
* **UI:** [Streamlit](https://streamlit.io/)
* **Financial Data:** `yfinance`, `sec-edgar-downloader`

## ⚙️ Quick Start

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/samirasonfack/FinRag-Financial-Research-and-Analysis-Assistant.git](https://github.com/samirasonfack/FinRag-Financial-Research-and-Analysis-Assistant.git)
  
