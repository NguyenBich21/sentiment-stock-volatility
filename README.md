# 📊 Sentiment & Stock Price Volatility Analysis

📌 **Academic Project – Data Analyst Course**  
👥 Team project (4 members) | This repository contains **my individual contribution**

---

## 📖 Project Overview
This project investigates the relationship between **financial news sentiment** and **stock price volatility** in Vietnam’s banking and financial sector (41 institutions).  

Key steps in the full project:
1. Collecting financial news & stock data  
2. Manually labeling ~5,000 news headlines by sentiment  
3. Training and evaluating sentiment classification models  
4. Using the best-performing model to classify the remaining unlabeled data  
5. Building a **Power BI dashboard** to visualize sentiment–volatility dynamics  
6. Deploying results on a web application  

📌 This repository only includes the parts I was directly responsible for:  
- **Data collection** (web scraping with Selenium)  
- **Sentiment classification modeling** (imbalanced dataset handling)  
- **Dashboard development in Power BI**  

---

## 🛠️ Tools & Technologies
- **Python** – Data collection & Machine Learning (scikit-learn, pandas, matplotlib)  
- **Selenium** – Automated web scraping of financial news  
- **Jupyter Notebook** – Model training and evaluation  
- **Power BI** – Interactive dashboard for sentiment–volatility analysis  
- **Excel** – Data preparation and storage  

---

## 📂 Repository Structure
📄 `Phân_lớp_tin_tức_Imbalance_data.ipynb` – Machine learning notebook (handling imbalanced dataset, training & evaluating sentiment classification models)  
📄 `FINAL DASHBOARD.pbix` – Power BI dashboard illustrating sentiment–volatility relationship  
📄 `News.xlsx` – Sample labeled financial news dataset  
📄 `Fill_News.xlsx` – Extended dataset with additional processed entries  
📄 `Stocks.xlsx` – Stock price dataset used in analysis  

> Other `.ipynb` files (e.g., `VIB.ipynb`, `SHB.ipynb`, `HSBC.ipynb`, `MBBank.ipynb`, `VPBank.ipynb`) contain  
> **web scraping scripts using Selenium** to collect financial news data for different banks.

---

## 📊 Key Features
- **Data Collection**: Automated scraping of financial news headlines from CafeF using Selenium  
- **Data Preparation**: Cleaned, organized, and merged news & stock data into analysis-ready format  
- **Machine Learning**: Built and evaluated sentiment classification model on ~5,000 labeled entries, addressing class imbalance  
- **Dashboard Development**: Designed interactive Power BI report (`FINAL DASHBOARD.pbix`) to visualize how sentiment affects stock volatility  

---

## 👤 My Contribution
- Collected and prepared financial news dataset using Selenium & Excel  
- Built and evaluated machine learning sentiment classification model (`Phân_lớp_tin_tức_Imbalance_data.ipynb`)  
- Designed **Power BI dashboard** (`FINAL DASHBOARD.pbix`)  
- Generated insights on the relationship between sentiment and stock price volatility  

---

## 🙏 Acknowledgment
This repository contains only **my individual contribution** from a **team project (4 members)**,  
completed as part of the **Data Analyst academic course**.
