# 🏥 Vezeeta Data Analysis & Scraping

This project focuses on scraping and analyzing **Vezeeta** (a healthcare services platform) orthopedist data and providing insights using data science methods.

---

## 📌 Project Description

- Scrape data of orthopedist doctors from Vezeeta (name, speciality, rating, location, etc.)  
- Clean & preprocess the scraped dataset  
- Perform exploratory data analysis (EDA)  
- Derive insights: e.g. distribution by location, ratings, specialties  
- (Optional) Build a simple predictive model or clustering on doctor features  

---

## 📁 Repository Structure

```
vezeeta/
├── data/                   
├── notebooks/              
│   └── vezeeta orthopedists scrapping.ipynb
├── src/                    
├── images/                 
├── output/                 
│   └── vezeeta orthopedists.csv
├── requirements.txt        
└── README.md

```

---

## 🔍 Data Source / Scraping

- The data was scraped from Vezeeta’s website (Orthopedist listings)  
- Fields collected include:
  - Doctor name  
  - Specialty  
  - Location / Clinic area  
  - Rating  
  - Number of reviews  
  - Hospital / Clinic name  

---

## 🔎 Exploratory Data Analysis (EDA)

In the notebook `notebooks/vezeeta orthopedists scrapping.ipynb`, we perform:
- Data cleaning: removing duplicates, handling missing values  
- Descriptive statistics  
- Distribution plots (histograms, bar charts)  
- Geographical mapping (if location data available)  
- Rating / specialty comparisons  

Example chart:  
![Ratings by Specialty](./images/ratings_specialty.png)

---

## 📊 Insights & Findings

- Some specialties have significantly higher average ratings  
- Clinics / locations with more doctors tend to have more reviews  
- Rating distribution is skewed (most doctors have high ratings)  
- (If implemented) Clustering doctors by features shows patterns in specialties / location

---

## ⚙️ How to Run / Reproduce

```bash
# Clone the repo
git clone https://github.com/Omayma-ali/vezeeta.git
cd vezeeta

# Install dependencies
pip install -r requirements.txt

# Open the Jupyter notebook
jupyter notebook notebooks/vezeeta\ orthopedists\ scrapping.ipynb
```

If you have a scraper script in `src/`, you can run, e.g.:
```bash
python src/scrape_orthopedists.py
```

---

## 🔮 Future Work

- Expand scraping to all specialties, not just orthopedists  
- Add mapping visualizations (plots on maps)  
- Sentiment analysis on reviews  
- Prediction or recommendation model (e.g. doctors with rating above threshold)  
- Build a dashboard or web app to display insights  

---

## 👩‍💻 Author / Contact

**Omayma Ali** — Data Scientist / Data Analyst  
- [GitHub](https://github.com/Omayma-ali)
- [LinkedIn](www.linkedin.com/in/omayma-ali)  
- [Fiverr](https://www.fiverr.com/users/omaymaaa)
- [Khamsat](https://khamsat.com/user/omayma_ali) 
