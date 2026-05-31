# GC% and Nucleotide Count of 10 Bacterial 16S rRNA Genomic Data

The aim of this project was to fetch, parse, and analyze the structural composition of 10 bacterial 16S Ribosomal RNA (rRNA) genes.

---

## Project Overview
The 16S rRNA gene serves as a highly conserved molecular barcode used globally to classify and identify bacteria. This project explores the chemical composition (specifically **GC Content**) of this structurally identical gene.

### What I did
1. Programmatically queried the NCBI RefSeq database via Biopython (`Entrez`) using targeted Accession IDs.
2. Streamed network data directly into a structured local FASTA file format.
3. Extracted sequence lengths and dynamic base-pair counts (`A`, `T`, `C`, `G`) using `Bio.SeqIO`.
4. Processed, calculated GC% content, sequence length and nucleotide count and normalized the output into a clean `Pandas` DataFrame.
5. Visualized the insights


## 🛠️ Tech Stack & Libraries
* **Language:** Python (Jupyter Notebook and Google Colab)
* **Bioinformatics Domain:** Biopython (`Bio.Entrez`, `Bio.SeqIO`)
* **Data Manipulation:** Pandas, NumPy
* **Data Visualization:** Seaborn, Matplotlib 

---
