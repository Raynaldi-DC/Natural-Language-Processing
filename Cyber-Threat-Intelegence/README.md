# TRAM: CTI to MITRE ATT&CK Report Automation using BERT NLP
![Python](https://img.shields.io/badge/Python-3.10-blue.svg)
![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)  
📌 Transform unstructured Cyber Threat Intelligence (CTI) reports into structured MITRE ATT&CK mapping using Natural Language Processing and BERT.

---

## 🧠 Project Overview
Cyber Threat Intelligence (CTI) reports often come in free-text format, making it challenging to extract structured insights. This project leverages **BERT**, a pre-trained language model, to:

- Perform **Named Entity Recognition (NER)** on CTI reports.
- Extract MITRE ATT&CK-relevant entities (tactics, techniques, software, etc.).
- Map them into **MITRE ATT&CK** format automatically.

The result is a structured representation of CTI narratives, useful for threat analysts, SIEM enrichment, or incident response.

## 🚀 How It Works
1. **Preprocessing**: Clean and prepare text.
2. **Model Inference**: Run BERT-based NER tagging.
3. **Entity Mapping**: Match entities to ATT&CK tactics & techniques.
4. **Reporting**: Output structured mappings for security operations.

## 📌 Example
Raw CTI sentence:
> "APT29 used spearphishing emails to target diplomatic personnel."

Mapped Output:
- 🎯 Tactic: **Initial Access**
- 🔧 Technique: **Spearphishing Email (T1566.001)**
- 🧩 Threat Actor: **APT29**

## 📂 Project Structure
```
TRAM/
├── notebook/
│   └── TRAM.ipynb          # Main notebook
├── requirements.txt        # Python dependencies
├── README.md               # Project documentation
```

## 💻 Installation & Usage
1. Clone the repository:
```bash
git clone https://github.com/yourusername/TRAM.git
cd TRAM
```

2. Install the dependencies:
```bash
pip install -r requirements.txt
```

3. Run the notebook:
```bash
jupyter notebook notebook/TRAM.ipynb
```

## 🛠️ Tech Stack

- `transformers` (BERT)
- `scikit-learn`
- `pandas`
- `matplotlib`
- `MITRE ATT&CK Navigator (data mapping)`

---

**Raynaldi Dwi Cahyono**  
📧 raynaldidwicahyono@gmail.com  
🔗 [LinkedIn](https://linkedin.com/in/raynaldidc) | [GitHub](https://github.com/Raynaldi-DC)  
_(This project is licensed under the **MIT License**.)_

---

## Navigation
- [🗣️ Natural Language Processing (NLP)](https://github.com/Raynaldi-DC/Natural-Language-Processing)  
- [🧠 Supervised Learning](https://github.com/Raynaldi-DC/Supervised-Learning)  
- [📊 Unsupervised Learning](https://github.com/Raynaldi-DC/Unsupervised-Learning)  
- [📈 Time Series](https://github.com/Raynaldi-DC/Time-Series)   

[| Main Menu ](https://github.com/Raynaldi-DC)[| Resume ](https://github.com/Raynaldi-DC/Resume)[| Certificates ](https://github.com/Raynaldi-DC/Certificates)[| Portfolio Main Page |](https://github.com/Raynaldi-DC/Portofolio)  
