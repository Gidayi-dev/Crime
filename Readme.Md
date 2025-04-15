# 🕵️‍♀️ Crime Data Analysis Project

This project explores crime data to uncover insights into when and where crimes occur most frequently and which age groups are most affected. The analysis was performed using Python with Pandas and Seaborn for data manipulation and visualization.

## 📁 Dataset

The dataset (`crimes.csv`) contains records of reported crimes, including:
- `TIME OCC` – The time the crime occurred (in 24-hour format)
- `AREA NAME` – The name of the area where the crime occurred
- `Vict Age` – Age of the victim
- Other incident-specific details

## 🔍 Objectives

1. **Find the peak crime hour**  
   - Extracted hour from the `TIME OCC` column
   - Identified the hour with the highest number of crimes

2. **Identify the area with the most night crimes (10 PM – 3:59 AM)**  
   - Filtered the dataset for night-time crimes
   - Determined the area with the highest night crime frequency

3. **Analyze crimes by victim age group**  
   - Binned victim ages into custom age brackets:
     - `0-17`, `18-25`, `26-34`, `35-44`, `45-54`, `55-64`, `65+`
   - Counted the number of crimes for each age group

## 🧰 Tools & Libraries Used

- **Python** – Programming language
- **Pandas** – Data manipulation
- **NumPy** – Numerical computations
- **Seaborn & Matplotlib** – Data visualization

## 📊 Sample Visualizations

- Hourly crime frequency plot
- Victim age distribution chart

## 🚀 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/Gidayi-dev/Crime
   
2. Install required libraries
pip install pandas numpy seaborn matplotlib
