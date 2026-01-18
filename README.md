# 🦠 COVID-19 Cases & Deaths Trend Analysis (USA)

An end-to-end data analytics and forecasting project that examines COVID-19 trends across the United States (2020–2022), combining epidemiological data from the World Health Organization (WHO) with public sentiment extracted from Twitter.  

This project demonstrates how data science can support public-health decision-making by:
- Identifying regional risk hotspots  
- Understanding population sentiment during outbreaks  
- Forecasting future cases and deaths using statistical and ML models  

---

## 📌 Project Objectives

- Perform exploratory data analysis (EDA) on U.S. COVID-19 case and death trends at state and county levels  
- Detect regional risk patterns and abnormal surges  
- Integrate public sentiment data to understand behavioral and emotional responses during waves  
- Compare forecasting approaches:
  - ARIMA (time-series model)
  - Random Forest (machine learning model)
- Evaluate which model better predicts future cases and deaths  
- Generate actionable insights for public-health administrators  

---

## 🗂️ Repository Structure
```
📁 data/
├─ who_covid_data.csv # WHO epidemiological dataset (2020–2022)
├─ twitter_sentiment.csv # Processed Twitter sentiment data
└─ README_sources.md # Data source credits & licenses

📁 notebooks/
├─ 01_EDA_COVID_Trends.ipynb # Cleaning, EDA, visualizations, hotspot analysis
└─ 02_Modeling_Forecasting.ipynb # ARIMA vs RF forecasting + evaluation

📁 docs/
└─ Project_Documentation.pdf # Methodology, findings, limitations

📁 presentation/
└─ COVID_Trend_Analysis_Presentation.pptx
```
---

## 📊 Key Analyses

### Exploratory Data Analysis
- State & county-level trend analysis (2020–2022)
- Daily and cumulative case/death trajectories
- Heatmaps and regional comparisons
- Detection of abnormal surges and risk clusters
- Michigan highlighted as a region with disproportionate increase vs national baseline

### Sentiment Analysis
- Twitter data aggregated by time and region
- Polarity scoring (positive / neutral / negative)
- Correlation between sentiment shifts and outbreak phases
- Behavioral signal interpretation during spikes

### Predictive Modeling
- ARIMA: time-series forecasting of cases & deaths  
- Random Forest: feature-based regression for trend prediction  
- Model comparison using error metrics (RMSE / MAE)  
- Identification of the best-performing model for regional forecasting  

---

## 🛠️ Tech Stack

- Python (Pandas, NumPy, Matplotlib, Seaborn, scikit-learn, statsmodels)
- Time-Series Analysis (ARIMA)
- Machine Learning (Random Forest)
- NLP / Sentiment Processing
- Jupyter Notebooks
- Data Visualization & Storytelling

---

## 📁 Data Sources & Credits

- **WHO COVID-19 Global Data**  
  Source: World Health Organization  
  [https://covid19.who.int](https://data.who.int/dashboards/covid19)  

- **Twitter Sentiment Dataset**  
  Publicly available COVID-19 tweet corpus (processed for research use)

All datasets are used for educational and research purposes only.  
Original ownership and rights remain with the respective data providers.

---

## 📈 Impact

This project demonstrates how large-scale epidemiological data and public sentiment can be combined to:
- Detect emerging risk zones  
- Anticipate outbreak surges  
- Support data-driven public-health strategy

It reflects real-world analytics workflows used in population health, healthcare analytics, and public policy research.

---

## 👩‍💻 Author

**Sarika Vemana**  
M.S. Health Informatics – Grand Valley State University  
LinkedIn: https://linkedin.com/in/sarika-vemana


