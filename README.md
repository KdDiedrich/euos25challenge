# euos25challenge

## Naming Convention and Abbreviations

The folders and files in this repository follow a structured naming scheme that encodes the **task**, **model**, and **feature representation** used.
The **task** component may include wavelength indicators (e.g., `t340`, `f340_450`).

**General pattern:**

<task>_<model>_<features>


---

## 1. Task Prefixes

- **`t`** – Absorption prediction task  
- **`f`** – Fluorescence prediction task  

---

## 2. Wavelength Indicators

- **`340`** – Absorption prediction task (340 nm)  
- **`450_679`** – Absorption prediction task (averaged from 450–679 nm)  
- **`340_450`** – Fluorescence prediction task (340/450 nm)  
- **`multi`** – Multi-output fluorescence prediction task  
  *(480/540, 525/598, or 560/610 nm)*

---

## 3. Models

- **`xgb`** – XGBoost classifier (Extreme Gradient Boosting)  
- **`hgb`** – Histogram-based Gradient Boosting classifier  
- **`cb`** – CatBoost classifier  

---

## 4. Molecular Representations / Features

- **`morganfp`** – Morgan fingerprints  
- **`rdkitfp`** – RDKit topological fingerprints  
- **`maccskeys`** – MACCS structural keys  
- **`desc2D`** – 2D molecular descriptors (RDKit)  

Feature names may be combined to indicate concatenated feature sets.

---

## 5. Other Files

- **`euos25-challenge.ipynb`** – Jupyter notebook used for submission for the EUOS25 Challenge
