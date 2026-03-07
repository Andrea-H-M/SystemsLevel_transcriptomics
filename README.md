# 🌿 Systems-level transcriptomics reveals regulatory network and candidate genes behind postpollination syndrome in vanilla


Repository associated with the manuscript:

Systems-level transcriptomics reveals regulatory network and candidate genes behind post-pollination syndrome in Vanilla planifolia

📄 Manuscript under peer review

## ⭐ Key result

Integration of orthology, differential expression, and co-expression networks identified:

🧬 88 candidate regulatory genes associated with post-pollination syndrome and ovule reactivation in Vanilla planifolia.

## 🌸 Biological system

Species: Vanilla planifolia (Orchidaceae)

Transcriptomic stages analyzed:

Stage	Description


🌱 Pre-pol	Floral bud before anthesis

🌼 Pol	Pollinated flower

🥚 Post-pol	Ovary 25 days after pollination

🌾 Fer	Ovary with fertilized ovules (60 days)



## 🧬 Transcriptome dataset

The analyses use the flower-to-fruit transition (FFT) transcriptome previously generated in:

Hernández-Miranda et al. 2025

### 📦 Dataset available at

https://link.springer.com/article/10.1186/s12870-025-06476-z

https://doi.org/10.5281/zenodo.18765805

⚙️ Methods

## Main analyses:

🧬 Orthology inference — OrthoFinder

📊 Differential expression analysis

🧠 Gene co-expression networks — WGCNA

🔍 Functional enrichment — GO / KEGG / gProfiler

📈 Network visualization — igraph (R)

## Gene prioritization

Candidate regulators were defined by combining:

### Functional labels

🧬 C-Orth (conserved orthologs)

🧠 TF (transcription factors)

🧬 EpiReg (epigenetic regulators)

🌸 stage-specific genes

### Structural labels

📊 DEG (differential expression)

🧩 Hub genes (WGCNA modules)

Genes carrying functional + structural labels were prioritized.

## 📂 Repository structure

📁 C_Orth_label
Conserved ortholog annotations (OrthoFinder).

📁 TF_EpiReg_label
Transcription factor and epigenetic regulator labels.

📁 Supplementary
Gene lists, enrichment results, and supplementary datasets.

## 📦 Generated databases 

Comparative Dataset of Differentially Expressed Genes and Conserved Orthologs During the Flower-to-Fruit Transition in Angiosperms
https://doi.org/10.5281/zenodo.18795437

Transcription Factors and Epigenetic Regulators Dataset
https://doi.org/10.5281/zenodo.18795163

Candidate Gene Dataset for the Post-Pollination Syndrome
https://doi.org/10.5281/zenodo.18795618


⚠️ Note

This repository contains scripts and supplementary materials associated with a manuscript currently under peer review.

## 👩‍🔬 Authors

Olga Andrea Hernández-Miranda, Jorge E Campos, Ulises Rosas, Estela Sandoval-Zapotitla, Ana Sidney Betanzos Ávalos, Juan Alberto Villanueva García, Ma. Concepción Guzmán Ramos, Victor Manuel Salazar-Rojas

<img width="3658" height="1537" alt="image" src="https://github.com/user-attachments/assets/c0803438-1959-472c-8191-46904df2a987" />
