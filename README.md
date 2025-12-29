# 🇮🇩 Kalibrr Job Market Analysis & Visualization

<div align="center">
  <img src="https://static.kalibrr.com/public/kalibrr-og-image.png" width="80%" alt="Kalibrr Banner">
  
  <p>
    <b>Analyzing employment trends in Indonesia through automated web scraping and statistical visualization.</b>
  </p>

  <img src="https://img.shields.io/badge/R-276DC3?style=for-the-badge&logo=r&logoColor=white">
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white">
  <img src="https://img.shields.io/badge/Data_Miner-FFA500?style=for-the-badge&logo=scrape&logoColor=white">
</div>

---

## 📌 Project Overview
This project aims to analyze the current job market landscape in Indonesia by scraping real-time data from **Kalibrr**. By collecting and processing job posting data, we extract insights regarding high-demand roles, salary distributions, and geographical opportunities.

The data is scraped using **Data Miner**, stored in **MongoDB** (NoSQL), and processed/visualized using **R**.

---

## 🔍 Key Insights & Objectives
We focused on answering the following business questions through data visualization:

* **Job Demand:** Which positions and industries have the highest number of openings?
* **Salary Analysis:** What is the distribution of salaries across different job levels? (Boxplot analysis)
* **Geographical Trends:** Which cities offer the most opportunities?
* **Transparency:** What is the proportion of companies that disclose salary information?
* **Company Analysis:** Identifying top hiring companies based on job volume.

---

## 🛠️ Tech Stack & Workflow

| Component | Tool | Description |
| :--- | :--- | :--- |
| **Scraping** | Data Miner | Automated extraction of job attributes (Title, Company, Salary, Location). |
| **Database** | MongoDB | Storing unstructured JSON data from the scraping process. |
| **Analysis** | R (RStudio) | Data cleaning, aggregation, and visualization (ggplot2). |

---

## 📊 Project Artifacts

We have documented the analysis process and results. You can view the full presentation below:

| Type | Link/File | Description |
| :--- | :--- | :--- |
| **📄 PDF Slides** | **[View Presentation (PDF)](./kalibrr.pdf)** | *Recommended.* Full presentation deck with visualization results. |
| **💻 Source Code** | **[R Script & Data](./)** | Access the raw code and aggregated data in this repository. |
---
## 📂 Data Structure
The raw data collected is stored in JSON format within MongoDB. Below is a sample document:

```json
{
  "_id": "68381022b6b2dc150057f7cb",
  "Job_Title": "Loyalty Marketing Associate Manager",
  "Company": "Traveloka",
  "Location": "Tangerang, Indonesia",
  "Salary": "Undisclosed",
  "Type": "Full Time",
  "Level": "Mid-Senior Level Manager",
  "Deadline": "06 July 2025"
}

