# Satellite Imagery–Based Property Valuation (CDC Open Project)

## 📌 Project Overview
This project aims to build a **property valuation model** by combining
traditional **tabular real estate data** with **satellite imagery–derived
features** to capture neighborhood context such as land use, accessibility,
and environmental characteristics.

The current implementation focuses on establishing a **baseline regression
model using tabular data**, which will later be extended with multimodal
features extracted from satellite imagery.

---

## 🧠 Motivation
Traditional property valuation models rely heavily on structured attributes
(area, location, price history) but often fail to capture **visual and spatial
signals** such as:
- Green cover
- Road density
- Urban layout
- Surrounding infrastructure

Satellite imagery provides this missing context and can significantly improve
valuation accuracy.

---

## 📂 Repository Structure
├── baselinemodel (only tabular data).ipynb
├── final_model.ipynb
├── preprocessing.ipynb
├── data_fetcher.ipynb
├── train.csv
├── test.csv
├── requirements.txt
└── README.md

## 🚀 How to Run

### 1️⃣ Clone the repository
```bash
git clone https://github.com/Sohan-iitr/Satellite-Imagery-Based-Property-Valuation-cdc-open-project.git
cd Satellite-Imagery-Based-Property-Valuation-cdc-open-project
### 2️⃣ Install dependencies
pip install -r requirements.txt

### 3️⃣ Launch Jupyter Notebook
jupyter notebook

👤 Author
Sohan Awate
