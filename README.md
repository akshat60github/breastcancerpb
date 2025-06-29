# 🧬 Tumor Suppressor Mutation Analysis in Breast Cancer

This project focuses on the analysis of **tumor suppressor gene mutations** (especially **BRCA2**) and their impact on breast cancer development across diverse populations. We used publicly available datasets like **COSMIC**, **UniProt**, and **ChEMBL** to uncover mutation patterns, investigate functional consequences, and build meaningful visualizations to better understand how these mutations correlate with patient age, ethnicity, and cancer progression.

> 📍 [📗 View the Interactive Colab Notebook](https://colab.research.google.com/drive/1w2IO2YbfzSYzj1d0Fbag8gl6ZSQ8cfR_?usp=sharing)

---

## 🧠 Problem Statement

> To analyze somatic mutations in tumor suppressor genes (e.g., **BRCA2**, **TP53**) associated with breast cancer, compare their prevalence across populations, and evaluate their potential functional impact on protein structure, biological pathways, and disease progression.

---

## 🔍 Key Analyses & Findings

### ✅ Mutation Frequency Analysis
- Mutation counts plotted across all genomic positions revealed **non-uniform distributions**, indicating **mutation hotspots**.
- Top mutations were mostly **missense**, **frameshift**, and **nonsense mutations** in **BRCA2**.

### ✅ Deep Dive into BRCA2
- The most frequent BRCA2 mutation caused a **frameshift at position 2560**, leading to a **premature stop codon**.
- Protein structure (UniProt: [7BDX](https://cancer.sanger.ac.uk/cosmic3d/protein/BRCA2?pdb=7BDX)) was analyzed for spatial mutation impact.

### ✅ Population & Age-based Trends
- Positive correlation (**r = 0.43**) between **patient age** and **number of mutations**.
- Mutation accumulation patterns **varied across ethnicities**, suggesting environmental or genetic factors.

### ✅ LOWESS Trend Analysis
- Smoothed mutation frequency curve showed **low but consistent mutation levels**, with small peaks at specific positions.

---

## 📊 Visualizations & Figures

- 📈 Mutation vs Frequency Histogram  
- 🧬 BRCA2 Mutation Distribution & Substitution Types  
- 🧪 Age vs Mutation Scatter Plot  
- 🌍 Ethnicity vs Mutation Heatmap  
- 📉 LOWESS Smoothing on Mutation Trends  

(All visuals generated using Python: `matplotlib`, `seaborn`, `pandas`)

---

## 🧰 Tools & Technologies Used

- **Python**, **Pandas**, **NumPy**, **Matplotlib**, **Seaborn**  
- **Google Colab**  
- **ChEMBL**, **UniProt**, **COSMIC** (databases)  
- **BLAST**, **Biopython**, **PyMOL** for structural/protein analysis  

---

## 👨‍👩‍👧‍👦 Team Members

- **Aditi Aryan** (2023037)  
- **Akshat Kumar** (2023060)  
- **Asher Ul Haque** (2023151)  
- **Bhuvika Mehta** (2023172)  
- **Simar Ahi** (2023527)  
- **Sree Sravya Uppalapati** (2023534)  
- **Varsha Ganesh** (2023583)

📌 All members contributed equally across Python coding, analysis, research, and presentation.

---

## 📄 References

- COSMIC: https://cancer.sanger.ac.uk/cosmic  
- UniProt: https://www.uniprot.org  
- ChEMBL: https://www.ebi.ac.uk/chembl  
- Ensembl: https://asia.ensembl.org  
- Springer: [Link](https://link.springer.com/article/10.1007/s12609-024-00567-w)  
- PubMed: [PMID: 14681210](https://pubmed.ncbi.nlm.nih.gov/14681210/), [PMID: 24598993](https://pubmed.ncbi.nlm.nih.gov/24598993/)

---

## 💡 Future Work

- Predictive modeling of deleterious mutation impact (SIFT, PolyPhen)  
- Integration with drug discovery pipelines (QSAR, docking)  
- Expanding dataset to include additional tumor suppressors

---

## 📬 Contact

For questions or collaborations, feel free to reach out to any of the team members or open an issue on this repository.

---

