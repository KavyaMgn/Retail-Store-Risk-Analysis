# 🏬 Retail Store Risk Analysis  

Predicting Walmart & Target store closure risks using ML + NLP on 1.5M+ Yelp reviews.  

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white) 
![scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white) 
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white) 
![NLP](https://img.shields.io/badge/NLP-Modeling-00A591?style=for-the-badge)

---

## Problem  
U.S. retailers face costly last-minute closures due to lagging indicators (revenue decline, lease expiry, low traffic).  
**Goal:** Predict at-risk Walmart & Target stores early using customer review data.

---

## Method  
- **Data:** Yelp reviews (1.5M rows, 275 stores across U.S.)  
- **EDA:** Review length, unique words, sentiment distribution  
- **Models:** Logistic Regression, Naïve Bayes, SVM, Random Forest (hypertuned)  
- **NLP:** Sentiment analysis, BERT topic modeling, zero-shot validation  
- **Business Analysis:** ROI/NPV estimation for proactive interventions  

---

## Results  
- **Random Forest (Target):** 96.7% accuracy  
- **Random Forest (Walmart):** 94.0% accuracy  
- Sentiment split: Target (77% positive), Walmart (60% negative)  
- BERT topics: inventory issues, checkout delays, staff quality, cleanliness, security  
- **Financial impact:** $1.25B potential savings; ROI > 1400%:contentReference[oaicite:6]{index=6}  

---

## Business Insights  
- **Walmart:** Higher closure risk, negative sentiment on service, stock, and online orders.  
- **Target:** Stronger brand sentiment, but pain points in parking, cleanliness, and service.  
- **Recommendations:** Improve service training, inventory management, cleanliness, and security.  

---

## Future Work  
- Extend analysis to multi-retailer datasets  
- Incorporate external data (leases, traffic, economic indicators)  
- Deploy early warning dashboards for proactive monitoring  

---

📂 Includes:  
- `final_project_code.ipynb` → Data + ML + NLP pipeline  
- `Presentation.pdf` → Deck with visuals, word clouds, and ROI analysis
