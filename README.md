# Enhancing Healthcare Services through Data-Driven Analysis

## 📌 Project Overview
This project aims to leverage **big data technologies** to analyze and improve healthcare services by identifying key insights from hospital data. By examining patient conditions, hospital resource availability, and illness severity, we strive to **optimize patient care, reduce mortality rates, and enhance resource allocation** in healthcare facilities.

## 🏥 Application Domain
- **Field**: Healthcare Management  
- **Problem Statement**: Many hospitals face challenges in managing patient care efficiently, especially during high-demand periods (e.g., COVID-19). Our project seeks to analyze hospital data to **predict patient stay durations** and **improve treatment prioritization**.  
- **Solution**: Use **machine learning and big data analytics** to classify patient risks and enhance decision-making for healthcare professionals.

## 📊 Dataset Details
- **Source**: [Kaggle - Healthcare Analytics 2](https://www.kaggle.com/datasets/vetrirah/av-healthcare2)
- **Size**: 300,000+ records
- **Key Features**:
  - **Patient Info**: Case ID, Age, Patient ID, Admission Type, Severity of Illness  
  - **Hospital Info**: Hospital Code, Region Code, Bed Grade, Available Extra Rooms  
  - **Target Variable**: `Stay` (predicting patient admission duration)  

## 🔍 Data Processing Steps
### 1️⃣ Data Cleaning
- Handled missing values in **Bed Grade** and **City Code** using appropriate techniques (mean, mode, forward fill).  
- Removed duplicates and inconsistencies to ensure **data integrity**.

### 2️⃣ Data Processing
- **Categorical Encoding**: Converted hospital type, department, admission type, and severity levels into numerical representations.
- **Data Normalization**: Applied **Parallel Coordinates Plot** to handle outliers and normalize features.

### 3️⃣ Data Visualization
We utilized **Plotly, Altair, and Seaborn** for interactive and insightful visualizations:
- **Box Plot**: Analyzed hospital regions vs. patient stays.
- **Violin Plot**: Explored illness severity distributions.
- **Pairplot & Lmplot**: Examined relationships between features.
- **Displot**: Analyzed frequency distributions of admission types.

## 🛠️ Tech Stack & Tools
- **Big Data Tools**: Apache Spark, Pandas, NumPy  
- **Machine Learning**: Scikit-learn, MLlib  
- **Data Visualization**: Matplotlib, Seaborn, Plotly, Altair  
- **Programming Languages**: Python  
- **Jupyter Notebook**: For exploratory data analysis  

## 📌 Key Findings & Insights
1. **Age-Wise Analysis**: Majority of patients are aged **31-50 years**, with **moderate severity** cases being the most frequent.  
2. **Hospital Department Analysis**: **Gynecology** had the highest patient volume, requiring **improved facility management**.  
3. **City-Based Insights**: City `2` had **the highest hospitalization rates**, indicating a **need for better infrastructure**.  
4. **Severity vs. Stay Duration**: Patients with **extreme illnesses had longer stays and higher visitor counts**, increasing **infection risks**.

## 🎯 Conclusion & Recommendations
- Hospitals should **prioritize high-risk patients** during admission to **reduce mortality rates**.  
- **Better resource management** is needed for cities with high hospitalization rates.  
- **Predictive analytics** can help hospitals **optimize treatment plans** and **prevent overcrowding**.

## 🚀 Future Work
- Implement **real-time dashboards** for hospital administrators.  
- Extend the model to **predict readmission rates**.  
- Integrate **deep learning models** for enhanced predictive capabilities.

