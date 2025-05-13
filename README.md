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

```python
import pandas as pd

df = pd.read_excel("ParsOffensive.xlsx")
