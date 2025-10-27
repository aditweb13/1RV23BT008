# 🧬 DNA Sequence Comparison and Online BLAST Search

This project demonstrates how to **compare DNA sequences locally** and perform an **online BLAST (Basic Local Alignment Search Tool)** search using Biopython.  

It has two main parts:
1. **Local FASTA Reading & Comparison** — reads local FASTA files, aligns two sequences character-by-character, and calculates a simple similarity score.  
2. **Online BLAST Search** — submits sequences to the NCBI BLAST database and retrieves possible matching genes or organisms.

---

## 🚀 Features

- Read and parse DNA sequences from FASTA files.  
- Perform simple local sequence comparison with match, mismatch, and gap penalties.  
- Perform online **nucleotide BLAST (blastn)** using Biopython’s `NCBIWWW.qblast()`.  
- Parse and display key BLAST hit details such as:
  - Alignment titles  
  - E-values and scores  
  - Query/subject ranges  
  - Sequence identity and gaps  

---

## 📁 Project Structure


---

## 🧰 Requirements

- **Python 3.8+**
- **Biopython** library (for BLAST)
- Internet connection (for online BLAST)

### Install Dependencies

```bash
pip install biopython
python dna_blast_tool.py
Sequence 1: ATGCGTACGTAC
Sequence 2: ATGCGTAGCTACAG
Alignment Score: -2
sequence_ids = ["AB021961.1", "OR523692.1"]

---

Would you like me to make this README **more concise** (for a GitHub repo) or **more detailed** (for a lab/project report submission)?
