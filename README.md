# DNA Sequence Analyzer

An open-source, lightweight Python utility designed to perform fundamental sequence analysis, nucleotide frequency calculations, GC/AT content profiling, and strand complementation for genomics workflows.

---

## 📌 Features
- **Sequence Validation:** Validates input sequences to ensure only standard IUPAC nucleotide characters (A, T, G, C) are processed.
- **Nucleotide Composition:** Computes individual base counts (A, T, G, C) and length metrics.
- **GC/AT Profiling:** Calculates exact GC% and AT% content essential for primer design and melting temperature estimations.
- **Strand Operations:** Rapid generation of complementary and reverse complementary strands.

---

## 🚀 Usage

### Example Code
```python
# Import the sequence functions or run interactively
sequence = "ATGCGATCGATCGATCGTAACGT"

# Validate and compute metrics
print(f"Sequence Length: {len(sequence)}")
print(f"GC Content: {(sequence.count('G') + sequence.count('C')) / len(sequence) * 100:.2f}%")
```
## 🛠 Tech Stack
Language: Python

Environment: Jupyter Notebook / Python scripts

## 👤 Author
- **Sarmitha K** – Undergraduate Student, B.Sc. Biotechnology, PSG College of Arts and Science
- **GitHub:** https://github.com/SarmithaK
- **LinkedIn:** https://www.linkedin.com/in/sarmitha-k-4a9156305
