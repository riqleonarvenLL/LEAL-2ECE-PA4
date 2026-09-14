
# Experiment 4: Data Wrangling and Data Visualization  
ECE 2112 – Advanced Computer Programming and Algorithms  

## 📘 Overview
This notebook demonstrates data wrangling and visualization using **Python (Pandas + Matplotlib)** in Google Colab.  
The dataset used is `board2.xlsx`, containing ECE Board Exam 2 results with columns:  
**Name, Gender, Track, Hometown, Math, GEAS, Electronics, Communication, Average**.  

The activity follows three tasks (A, B, C) as required in the lab instructions.

----

## 🅰️ Visayas Communication DataFrame
- Filtered students with **Hometown = Visayas** and **Track = Communication**.  
- Retained columns: `Name, Gender, Math, Electronics, Average`.  
- Displayed the resulting DataFrame and its number of rows.

  <img width="1548" height="1182" alt="image" src="https://github.com/user-attachments/assets/f384b779-6bce-4590-8793-89ab76537ec6" />


---

## 🅱️ Visayas Female DataFrame
- Filtered students with **Hometown = Visayas** and **Gender = Female**.  
- Retained columns: `Name, Track, GEAS, Electronics, Average`.  
- Displayed the full DataFrame.  
- Applied a second filter to show only rows with **Average ≥ 60** (without overwriting the original).

  <img width="1380" height="864" alt="image" src="https://github.com/user-attachments/assets/b9dabe31-fb48-48c7-b859-1eb36a9953da" />
  <img width="1172" height="544" alt="image" src="https://github.com/user-attachments/assets/5a3bd2ea-465f-40ca-bda3-44067deed2e1" />

---

## 🅲 Category‑Average Visualization
- Computed mean **Average** grouped by:
  - Track  
  - Gender  
  - Hometown  
- Displayed three summary tables.  
- Plotted three bar charts in one figure (mean Average by Track, Gender, Hometown).  
- Wrote concise interpretation statements identifying which category had the highest mean in each case.

  <img width="1124" height="1302" alt="image" src="https://github.com/user-attachments/assets/ef93616e-1c2c-4ae2-a7fa-e9ddc880cc80" />
  <img width="2074" height="1142" alt="image" src="https://github.com/user-attachments/assets/8d786697-239d-4e57-bc26-9ddcb2f54b2d" />
  <img width="1236" height="750" alt="image" src="https://github.com/user-attachments/assets/910cb283-411a-4a32-8c21-e2fc6f009dfd" />




---
