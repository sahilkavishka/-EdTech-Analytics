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

<img width="1187" height="590" alt="image" src="https://github.com/user-attachments/assets/f0ca2bc2-edc7-4309-bd6d-7d4a3e8b7e87" />
<img width="1189" height="590" alt="image" src="https://github.com/user-attachments/assets/b323c37c-ebb1-43bc-8cd7-226540802989" />
<img width="1189" height="590" alt="image" src="https://github.com/user-attachments/assets/88fbb96e-0929-40e6-b085-131bf0f29220" />
<img width="948" height="790" alt="image" src="https://github.com/user-attachments/assets/7b498dbc-f914-4559-b3fa-8f93c1927981" />
<img width="1189" height="590" alt="image" src="https://github.com/user-attachments/assets/97766850-940a-439b-92c8-0dcd7153d144" />
<img width="1189" height="590" alt="image" src="https://github.com/user-attachments/assets/a8ad2497-8eca-4303-a609-cdeff362eaa8" />
<img width="1184" height="590" alt="image" src="https://github.com/user-attachments/assets/250faef4-c83e-49f5-83d3-08ddecbd1207" />
<img width="1185" height="590" alt="image" src="https://github.com/user-attachments/assets/550901c2-30aa-4ff8-8a04-03c70335f311" />



