# Bhutan IMF Report Analysis Using LLMs

## Project Overview
This project analyses Bhutan's 2025–2026 IMF Country Report using Large Language Models (LLMs). It extracts financial indicators, summarises economic information, identifies financial risks and presents the findings in a four-panel dashboard.
 
**Country:** Bhutan  
**IMF Report:** Country Report No. 26/019

## Tools and Models
- **Platform:** Google Colab (NVIDIA A100 GPU)
- **Language Model:** Qwen3-14B
- **Evaluation Model:** Mistral NeMo 12B Instruct
- **Embedding Model:** Qwen3-Embedding-0.6B
- **Libraries:** Python, PyMuPDF, Transformers, FAISS, Pandas, Matplotlib

## Project Features
- PDF text extraction and token-aware chunking
- Eight section summaries and executive summary
- Financial indicator extraction in JSON format
- Seven financial stability themes
- Economic strengths and vulnerabilities
- FAISS-based RAG question answering
- Independent LLM evaluation
- Four-panel financial dashboard

## How to Run
1. Open the notebook in Google Colab.
2. Select an A100 GPU runtime.
3. Upload the Bhutan IMF PDF when prompted.
4. Run all notebook cells sequentially.
5. View the generated JSON, CSV and dashboard outputs.

## Results
The project processed 216 text chunks, generated four RAG answers and completed 18 LLM evaluations. All 17 automated project validation checks passed.

## Data Source
International Monetary Fund (2026). *Bhutan: 2025 Article IV Consultation—Press Release; and Staff Report*. IMF Country Report No. 26/019.
