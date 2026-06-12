# RAG Saturation & Hallucination Analysis

> Final Assignment — Kapita Selekta Sistem Cerdas

## Deskripsi

Proyek ini menganalisis fenomena **saturasi performa** dan **halusinasi sitasi** pada sistem Retrieval-Augmented Generation (RAG) dengan memvariasikan jumlah dokumen konteks (Top-K retrieval).

## Anggota Tim

| Nama | NIM | Peran |
|------|-----|-------|
| Andi Fayza Maharani | [23/516238/PA/22074] | Data & Retrieval |
| Rocky | [NIM] | Generation & Prompting |
| Aza | [NIM] | Evaluation & Analysis |

## Komponen Sistem

| Komponen | Detail |
|----------|--------|
| Dataset | IDK-MRC (rifkiaputri/idk-mrc) |
| Embedding Model | paraphrase-multilingual-MiniLM-L12-v2 |
| Vector Store | FAISS (IndexFlatL2) |
| Generator (LLM) | TBD |
| Nilai K yang diuji | 1, 3, 5, 10 |

## Metrik Evaluasi

- **Answer Quality**: ROUGE, BLEU, BERTScore

- **Citation Accuracy**: Persentase sitasi dokumen yang benar per nilai K

## How to Run

1. Buka masing-masing notebook di Google Colab
2. Run cell secara berurutan dari atas ke bawah
3. Run Data\_Retrieval.ipynb terlebih dahulu
