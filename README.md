
# Naukri Data Analyst Job Scraper – Task 10 (Final Version)

This project scrapes **Data Analyst job listings from Naukri.com** using Python, processes the data, and generates insights like **top locations** and **top skills**.

## 🔍 Features
- Multi‑page scraping using `requests` + `BeautifulSoup`
- Extracts:
  - Job Title  
  - Company  
  - Location  
  - Salary  
  - Experience  
  - Skills  
- Cleans and stores output in a CSV file
- Generates charts:
  - Top job locations  
  - Most in‑demand skills  

## 📁 Project Structure
```
task10_naukri_final/
│── main.py
│── README.md
│── requirements.txt
│── data/
│     └── naukri_data_analyst_jobs.csv
│── outputs/
      ├── top_locations.png
      ├── top_skills.png
```

## ▶ How to Run
```
pip install -r requirements.txt
python main.py
```

## 📊 Sample Output (Already Included)
- **Filled dataset** with job listings  
- **Generated charts** saved in `outputs/`

## 📌 Notes
- Naukri blocks heavy scraping. This project includes a simulated filled dataset for safe academic submission.
