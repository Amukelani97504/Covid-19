# 📊 COVID-19 Global Data Tracker

## 📌 Project Overview  
This project analyzes global COVID-19 trends, including cases, deaths, recoveries, and vaccinations. Using Python data tools, it performs **exploratory data analysis (EDA)**, cleans real-world datasets, and visualizes trends through interactive charts and maps.  

By the end of this project, users will have a **detailed data analysis report** with meaningful insights, suitable for presentation or publishing.

---

## 🚀 Project Objectives  

✅ Import and clean **COVID-19 global data**  
✅ Analyze time trends (**cases, deaths, vaccinations**)  
✅ Compare metrics across countries/regions  
✅ Visualize trends with **charts, maps, and interactive dashboards**  
✅ Communicate findings in a **Jupyter Notebook or PDF report**

---

## 🗂️ Project Workflow  

### **1️⃣ Data Collection**  
**Data Sources:**  
- [Our World in Data](https://ourworldindata.org/coronavirus-source-data)  
- Johns Hopkins University GitHub Repository  
- Kaggle COVID-19 datasets  

**Action Steps:**  
- Download `owid-covid-data.csv`  
- Save it in your working directory  

### **2️⃣ Data Exploration**  
**Tasks:**  
- Load data using `pandas.read_csv()`  
- Check dataset structure (`df.head()`, `df.columns()`)  
- Identify missing values (`df.isnull().sum()`)  

### **3️⃣ Data Cleaning**  
**Tasks:**  
- Filter countries of interest (e.g., South Africa, USA, India, Kenya)  
- Convert date column (`pd.to_datetime()`)  
- Handle missing numeric values (`fillna()` or `interpolate()`)  

### **4️⃣ Exploratory Data Analysis (EDA)**  
**Visualizations:**  
- **Line Charts:** Total cases & deaths over time  
- **Bar Charts:** Top affected countries  
- **Scatter Plots:** Vaccination impact vs cases  
- **Heatmaps:** Correlation analysis  

### **5️⃣ Advanced Data Visualization**  
**Interactive Visualizations (Plotly):**  
- Dynamic line charts for cases  
- Choropleth world map of case densities  
- Scatter plots analyzing vaccination effects  

### **6️⃣ Reporting & Insights**  
Deliverables:  
✅ Well-documented **Jupyter Notebook** (code + analysis)  
✅ Exportable **PDF report** with findings  
✅ Optional **PowerPoint** summary  

---

## 🛠️ Technologies Used  

✅ Python  
✅ Pandas  
✅ Matplotlib & Seaborn  
✅ Plotly  
✅ Jupyter Notebook  

---

## 🔗 Helpful References  
- [Our World in Data COVID-19](https://ourworldindata.org/coronavirus-source-data)  
- [Plotly Documentation](https://plotly.com/python/)  
- [Pandas Documentation](https://pandas.pydata.org/docs/)  

---

## 📢 How to Run This Project  

1️⃣ Clone the repository (or use your project folder)  
```bash
git clone 
cd covid19-tracker
