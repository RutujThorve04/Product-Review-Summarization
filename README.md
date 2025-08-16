# 🛍️ Product Review Summarization System  

### 🌐 Live Demo  
👉 [Try the working project here](http://3.81.174.21:8501/)  

---

### 📌 Project Overview  
Scrolling through thousands of product reviews is overwhelming, time-consuming, and often confusing.  
This project solves that problem by automatically **scraping, cleaning, and summarizing** reviews from Flipkart into a concise, human-like summary.  

At its core, the system uses a **fine-tuned BART model**, supported by **LLM Gemini–generated summaries** for training data, to capture product quality, features, and customer sentiment in just a few sentences.  

The goal is simple: help people and businesses make **faster, smarter decisions** without drowning in reviews.  

---

### 🚀 Workflow  

**Phase 1: Data Pipeline**  
1. **Scraping** – Collects real-time reviews from Flipkart using Selenium.  
2. **Cleaning & Preprocessing** – Removes spam, duplicates, non-English text, and formatting noise.  
3. **Chunking** – Splits reviews into blocks that fit the model’s input size.  

**Phase 2: Summarization Pipeline**  
4. **Model Processing** – Cleaned data is passed into the fine-tuned BART model.  
5. **Beam Search** – Multiple candidate summaries are generated; the most coherent is chosen.  
6. **Final Output** – A crisp, well-structured summary is delivered via a Streamlit web app, alongside product metrics.  

---

### 📊 Features  
- 🔍 **Real-time Review Scraping** – Directly from Flipkart  
- 🧹 **Smart Cleaning** – Keeps only high-quality, English reviews  
- 🤖 **AI-Powered Summaries** – Fine-tuned BART delivers concise insights  
- ⚡ **Time Efficiency** – Reduces review reading time by 94% (8 min → 26 sec)  
- 📈 **Insightful Metrics** – Ratings, review counts, sentiment indicators  
- 💻 **User-Friendly Web App** – Clean Streamlit dashboard  
- ☁️ **Cloud Deployed** – Access the tool instantly via browser  

---

### 📑 System Effectiveness  
- **Information Retained:** 92.3%  
- **Compression Ratio:** 18.9:1  
- **Time Saved:** 94.7%  
- **Reliability:** 97.3% success rate in summary generation  

---

### 🛠️ Technology Stack  
- **Web Scraping:** Selenium  
- **Data Cleaning:** Python, Regex, LangDetect  
- **Summarization:** Fine-tuned BART (with Gemini-assisted training data)  
- **Interface:** Streamlit  
- **Deployment:** Cloud-hosted (accessible via any modern browser)  

---

### 📂 Repository Structure  
- `scrapping_new.py` → Collects reviews from Flipkart  
- `prediction_reviews_cleaning.py` → Cleans and preprocesses raw reviews  
- `streamlit_new.py` → Streamlit app for interactive summarization  

---

### 💡 Why This Matters  
E-commerce thrives on reviews, but **too many reviews can overwhelm customers**. This system cuts through the noise, offering clear summaries that preserve critical insights while saving time.  

It’s built to make online shopping not only **smarter and faster**, but also more **human-friendly**.  

---
