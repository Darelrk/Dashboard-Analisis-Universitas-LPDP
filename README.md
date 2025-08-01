# World University Opportunity Analysis Dashboard

A tool for discovering "hidden gems" from the list of universities targeted by the LPDP scholarship.

**[View the Interactive Dashboard 🚀](https://lookerstudio.google.com/reporting/8910294d-6399-4722-bf28-3d72bbce1f4f)**

![Dashboard Screenshot](https://github.com/Darelrk/Dashboard-Analisis-Universitas-LPDP/blob/main/images/dashboard.jpg)

---

## 🎯 About This Project

Choosing a university can be confusing, especially when comparing various ranking systems. This project was born from the need to simplify the search process, with a primary focus on finding **"Hidden Gems"**: universities that have outstanding study programs (e.g., Computer Science) even if their overall world ranking isn't always at the top.

All universities in this dashboard are from the official **LPDP** scholarship destination list, making it a highly relevant tool for prospective applicants.

---

## ✨ Key Features

* **Interactive Map**: Visualize the distribution of top world universities from the LPDP list.
* **Ranking Comparison**: Directly compare university rankings from **QS, THE, and CWUR** in a single view.
* **"Hidden Gem" Score**: Discover excellence in Computer Science programs through a specially designed score.
* **Filter by Country**: Focus your search by filtering all data by the destination country.

---

## 🛠️ Technology Stack

* **Data Collection**: `Python` (Selenium)
* **Data Analysis**: `Python` (Pandas, Jupyter Notebook)
* **Data Storage**: `CSV Upload`
* **Data Visualization**: `Looker Studio`

---

## ⚙️ Behind the Scenes

1.  **Data Collection**
    Overall and Computer Science-specific ranking data was automatically collected from the QS, THE, and CWUR sites, using the official LPDP directory as the reference list of universities.

2.  **Cleaning & Merging**
    All raw data from multiple sources was cleaned, standardized, and merged into a single master CSV *file* using Pandas.

3.  **Visualization**
    The cleaned CSV *file* was uploaded to Looker Studio to create the interactive dashboard you can see and use.
