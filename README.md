🧬 LUCPROT: Protein Sequence Classification using Lucas Number Encoding

🔍 Overview

This repository contains the complete implementation of the LUCPROT framework proposed for protein sequence classification and COVID-19 variant identification.
The method combines Lucas sequence–based amino acid encoding with classical machine learning and deep learning algorithms.

All models are trained and evaluated using protein sequences retrieved directly from NCBI Protein database via the Entrez API.

⚙️ Installation

1️⃣ Clone the repository

```
git clone https://github.com/burakalakuss/LUCPROT-COVID-19Variations.git
cd LUCPROT-COVID-19Variations
```
2️⃣ Install dependencies

```
pip install -r requirements.txt
```
🌐 Data Source

```
from Bio import Entrez
Entrez.email = "your_email@example.com"
Entrez.esearch(db="protein", term="SARS-CoV-2[Organism] AND variant[Title]")
```





