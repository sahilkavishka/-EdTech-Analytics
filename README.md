# 🚀 EdTech Market Intelligence & SEO Analytics Pipeline

## 📌 Project Overview
This project is an advanced, automated data engineering pipeline designed to extract, process, and analyze the Sri Lankan EdTech market on YouTube. Bypassing traditional scraping methods, this pipeline leverages the **Official YouTube Data API v3** to gather 100% accurate, enterprise-grade metrics for educational content analysis.

## 🛠️ Key Features & Business Logic
Unlike basic data extraction scripts, this pipeline incorporates advanced feature engineering to derive actionable business intelligence:
* **Auto-Categorization (NLP):** Automatically classifies content into categories (e.g., A/L, O/L, Motivation) based on title keywords.
* **View Velocity Metric:** Calculates `Views_Per_Day` to fairly compare the performance of newly uploaded videos against older content.
* **Channel Authority (Viral Multiplier):** Extracts channel subscriber counts to calculate how many times a video's views exceeded its native audience (Views/Subscribers).
* **Engagement Rate Calculation:** Measures true audience interaction (Likes + Comments / Views).
* **Automated Pagination & De-duplication:** Uses `sets` and `pageToken` to harvest large volumes of unique data seamlessly.

## 💻 Tech Stack (2026 Standards)
* **Language:** Python 3.x
* **Libraries:** `google-api-python-client`, `pandas`, `isodate`, `tqdm`
* **Data Source:** Google Cloud - YouTube Data API v3

## ⚙️ How to Run
1. Clone the repository.
2. Install the required dependencies: `pip install -r requirements.txt`
3. Replace `'YOUR_API_KEY_HERE'` in the `data_pipeline.py` script with your actual Google Cloud API Key.
4. Run the script. The processed output will be saved as `Ultimate_EdTech_Intelligence_2026.csv`.

## 📊 Next Steps (Visualization)
The generated dataset is perfectly structured for immediate import into **Power BI**, where dashboards will be created to identify peak upload hours, top-performing SEO tags, and market gaps in the local EdTech space.
