# 📂 DistilBERT Resume Classifier  

## 📌 Project Summary  
The **DistilBERT Resume Classifier** is a machine learning project that automates **resume parsing, segmentation, and classification** using transformer-based NLP models.  

The pipeline extracts resume text (from `.docx`), processes it into structured JSON, and trains a classifier to categorize resume segments (education, skills, projects, experience, etc.).  

This project demonstrates **end-to-end NLP model building** — from dataset preparation and preprocessing to training and evaluation — showcasing modern skills in **data engineering, model fine-tuning, and practical deployment of LLM-powered pipelines**.  
(model building is done as part of other project).
---

## 📁 Repository Structure  

```text
distilbert-resume-classifier/
├── 1_extract_docx_to_txt.ipynb    # Convert resumes from DOCX → plain text
├── 2_send_to_llm_and_save_json.ipynb # Send resumes to LLM, save parsed JSON
├── resume-text/                   # Extracted raw text resumes
├── resume-docs/                   # Original resume DOCX files
├── parsed-json/                   # JSON outputs after LLM parsing
└── README.md
```

---

## 🚀 Features  
- **Resume Parsing:** Converts `.docx` resumes into structured `.txt`.  
- **LLM-Powered Segmentation:** Uses large language models to parse resumes into JSON with labeled sections.  
- **Dataset Creation:** Builds training and validation sets in JSONL format.
  
- - (is performed as a different project and it can be found in my other repo)
- **Transformer Model Training:** Fine-tunes **DistilBERT** on resume sections for classification.
- **Evaluation:** Validates model performance on unseen resumes.  
- **Reusability:** Framework can be extended to other document classification tasks.  

---

## 🛠️ Skills & Upskilling Showcase  

**Technical Skills:**  
- Natural Language Processing (NLP): text extraction, cleaning, sequence classification.  
- Transformers (Hugging Face): fine-tuning DistilBERT for domain-specific tasks.  
- Data Engineering: building structured datasets (JSONL, parsed JSON).  
- Machine Learning Workflow: preprocessing, training, tuning, evaluation.  
- Automation Pipelines: DOCX → TXT → JSON → Model pipeline.  
- Versioning & Reproducibility: organized repo with checkpoints.  

**Soft Skills:**  
- Clear documentation & storytelling in ML projects.  
- End-to-end ownership from raw data to ML model.  
- Applying academic ML concepts to real-world use cases.  

---

## 🏆 Achievements  
- Built an **automated resume segmentation system** using **LLMs + DistilBERT**.  
- Created structured datasets (`train.jsonl`, `val.jsonl`) from unstructured resumes.  
- Implemented a **document-to-model pipeline** with reusable preprocessing steps.  
- Demonstrated **cross-functional AI workflow** (data prep → model training → evaluation).  

---

## 📈 Use Cases  
- **HR Tech:** Automating resume screening & classification.  
- **Recruitment Platforms:** Structuring resumes into searchable databases.  
- **Personal Portfolio:** Showcasing NLP/ML model development skills.  
- **Document Classification:** Extendable to legal, financial, or research papers.  

---

## 👩‍💻 Author  

**Harika Lankalapally**  
📍 Fort Worth, Texas  
📧 pullurishivasai@gmail.com  

🎓 Master of Science, Data Science 
*The University of Texas at Arlington (2023–2025)*  

---

✨ *This repository highlights strong skills in machine learning, NLP, and data science, while showcasing the ability to deliver complete, production-ready AI pipelines.*  
