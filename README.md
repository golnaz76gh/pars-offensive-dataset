# ParsOffensive Dataset

This repository contains the **ParsOffensive** dataset — a manually labeled collection of Persian Instagram comments, created to support research in **offensive language detection** for the Persian language.

## 📊 Dataset Overview

- Total comments: **8,433**
- Labels: `Offensive` or `Neutral`
- Format: **Excel file (`.xlsx`)**
- Language: **Persian**
- Source: Instagram comments, crawled using Python based on relevant hashtags
- Topics covered: Politics, culture, sports, current events
- Labeling process: Two expert linguists + multi-phase review

## 🧾 File

- `ParsOffensive.xlsx`: The main dataset file (located in the root directory)

## 🧠 Usage Example

You can load the Excel file using `pandas`:

<pre>import pandas as pd
df = pd.read_excel("ParsOffensive.xlsx")
</pre>

## 💡 Purpose

The dataset was developed to help researchers and developers:

- Detect and moderate offensive content in Persian  
- Build and benchmark machine learning models  
- Fill the resource gap in Persian NLP  

## 🔗 Citation

If you use this dataset in your research, please cite:

Ali Nazarizadeh, Minoo Sayyadpour, Omid Ebrahimkhani, Amirmasoud Iravani, Golnaz Ghannadan Shirazi, Mojgan Behravan,  
**"Parsoffensive: Persian Offensive Comments Dataset"**,  
Proceedings of the 11th International Conference on Web Research (ICWR), Apr 2025, pp. 100–104.  
DOI: https://doi.org/10.1109/ICWR65219.2025.11006224.  
ResearchGate: https://www.researchgate.net/publication/391998695_Parsoffensive_Persian_Offensive_Comments_Dataset

**Suggested BibTeX**
```bibtex
@inproceedings{nazarizadeh2025parsoffensive,
  author    = {Ali Nazarizadeh and Minoo Sayyadpour and Omid Ebrahimkhani and Amirmasoud Iravani and Golnaz Ghannadan Shirazi and Mojgan Behravan},
  title     = {Parsoffensive: Persian Offensive Comments Dataset},
  booktitle = {Proceedings of the 11th International Conference on Web Research (ICWR)},
  year      = {2025},
  pages     = {100--104},
  doi       = {10.1109/ICWR65219.2025.11006224},
  url       = {https://doi.org/10.1109/ICWR65219.2025.11006224}
}

