# John Fung

I build data pipelines and ML systems — mostly on AWS, mostly in Python.

Currently focused on data engineering: moving data from messy to clean to useful.

---

## Things I've built

### Olist E-Commerce Pipeline
Took a Kaggle dataset of 100k Brazilian e-commerce orders and built a proper 
cloud pipeline around it. Raw CSVs go in, clean Parquet comes out, 
dashboard at the end.

**What I used:** AWS S3 · Glue (PySpark) · Athena · Streamlit

[![GitHub](https://img.shields.io/badge/GitHub-Repository-black?logo=github)](https://github.com/jonjonfung/olist-ecommerce-pipeline)
[![Live Demo](https://img.shields.io/badge/Streamlit-Live%20Demo-red?logo=streamlit)](your_streamlit_url_here)

---

### Delivery Time Predictor
Turns out where you live in Brazil explains 49% of how long your order takes 
to arrive. Built a Random Forest model to predict delivery times — 
trained on 96k orders, deployed as a live app.

**What I used:** AWS Athena · Scikit-learn · Pandas · Streamlit · S3

[![GitHub](https://img.shields.io/badge/GitHub-Repository-black?logo=github)](https://github.com/jonjonfung/olist-delivery-prediction)
[![Live Demo](https://img.shields.io/badge/Streamlit-Live%20Demo-red?logo=streamlit)](https://olist-delivery-prediction-bulkpjycmxq7mtulcq2dre.streamlit.app/)

---

### Stock Data Pipeline
Pulls Apple, Google, Microsoft, Amazon and Meta stock prices every morning 
at 9am without me doing anything. EventBridge → Step Functions → Lambda → S3. 
Dataset grows a little every day.

**What I used:** AWS EventBridge · Step Functions · Lambda · S3 · Athena

[![GitHub](https://img.shields.io/badge/GitHub-Repository-black?logo=github)](https://github.com/jonjonfung/stock-data-pipeline)

---

## Stack
```
Cloud     → AWS (S3, Glue, Athena, Lambda, Step Functions, EventBridge)
Languages → Python, SQL
DE tools  → PySpark, Pandas, Parquet
ML        → Scikit-learn, Random Forest
CI/CD     → GitHub Actions
Dashboards→ Streamlit
```

---

## GitHub Stats

![John's GitHub stats](https://github-readme-stats.vercel.app/api?username=jonjonfung&show_icons=true&theme=default)

---

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?logo=linkedin)](your_linkedin_url_here)
