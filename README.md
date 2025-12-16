# Search-Behavior-Driven-Skill-Demand-Analysis-Using-Analytics-NLP-and-RAG


# 📊 Search Behavior–Driven Skill Demand Intelligence System

An end-to-end data science project that analyzes online search behavior to anticipate future-relevant technical skills and support student decision-making. The system integrates analytics, NLP, and a Retrieval-Augmented Generation (RAG) pipeline to provide explainable, data-driven insights through an interactive interface.

---

## 🚀 Project Motivation

Students often rely on anecdotal advice or outdated reports when choosing which skills to learn. This project explores whether **Google search behavior**, when combined with analytical validation and NLP techniques, can act as an early indicator of future skill demand.

---

## 🎯 Problem Statement

**How can online search behavior be analyzed to anticipate future skill demand and help students make informed decisions about which technologies to learn?**

---

## 🧠 Solution Overview

This project builds a **decision support system** that:

* Analyzes Google Trends data for technical skills
* Quantifies growth, volatility, and saturation patterns
* Validates trends using job demand indicators
* Identifies regional adoption behavior
* Groups skills using NLP-based semantic clustering
* Answers natural language questions using a RAG framework

---

## 🗂️ Project Workflow

1. **Data Acquisition**

   * Google Trends data collected using PyTrends
   * Fixed time window for consistent comparisons

2. **Exploratory & Explanatory Analysis**

   * Time-series trend analysis
   * Growth rate and volatility computation
   * Growth vs stability classification

3. **Job Market Validation**

   * Comparison of search growth with job demand scores
   * Identification of hype-driven vs sustainable skills

4. **Region-Wise Analysis**

   * Country-level interest analysis
   * Normalized comparisons and heatmap visualization

5. **NLP-Based Skill Clustering**

   * Sentence embeddings using transformer models
   * Semantic similarity and hierarchical clustering

6. **RAG-Based Question Answering**

   * Analytical insights stored as knowledge documents
   * FAISS vector database for retrieval
   * Lightweight transformer model for grounded summarization

7. **Interactive Interface**

   * Gradio-based UI for user queries
   * Optional query flagging for feedback analysis

---

## 🛠️ Technologies Used

* **Python**
* **Google Trends (PyTrends)**
* **Pandas, NumPy**
* **Matplotlib, Seaborn**
* **Sentence Transformers (all-MiniLM-L6-v2)**
* **FAISS**
* **Hugging Face Transformers (T5)**
* **Gradio**

---

## 📌 Key Insights

* Data & AI and Cloud skills show sustained growth and strong demand
* Core programming languages are stable but saturated
* Certain skills exhibit hype-driven volatility
* Regional analysis highlights early adoption in tech-centric regions
* NLP clustering reveals natural groupings of skills and learning paths

---


## ⚠️ Limitations

* Google Trends provides relative, not absolute, search values
* Search intent may not always indicate learning intent
* Job demand scores are proxies and not scraped in real time
* LLM outputs depend on retrieved analytical context

---

## 🔮 Future Improvements

* Integrate real job posting data
* Add time-series forecasting models
* Expand skill coverage
* Deploy on Hugging Face Spaces
* Personalize recommendations by user profile

---

## 📄 License

This project is intended for academic and educational purposes.

---

## 🙌 Acknowledgements

* Google Trends
* Hugging Face
* FAISS
* Open-source Python community

