# 📊 Fitbit Predictions 🏋️‍♀️💤

Welcome to the **Fitbit Data Analysis** project! 🎉  
This repository showcases an insightful analysis of Fitbit data, tailored for women's health and wellness.  
The project is inspired by Bellabeat's mission to empower women with smart wearables and wellness programs.  

---

## 🔍 **Overview**

This project analyzes **Fitbit data** to understand women's:  
- 🌙 Sleep patterns  
- 🏃‍♀️ Activity levels  
- 🏋️‍♀️ Intensity of workouts  
- ⚖️ Weight trends  
- 🔥 Calorie expenditure  

The goal is to uncover meaningful insights and build predictive models to support holistic health and well-being.  

---

## 📁 **Project Structure**

```
├── Fitbit Data Analysis.Rmd   # Main analysis script
├── README.md                  # This README file
├── Data/
│   ├── dailyActivity_merged.csv
│   ├── hourlyCalories_merged.csv
│   ├── hourlyIntensities_merged.csv
│   ├── sleepDay_merged.csv
│   ├── weightLogInfo_merged.csv
├── Results/                   # Visualizations and outputs
```

---

## ⚙️ **Key Features**

### 📊 **Data Cleaning and Transformation**
- 🗂 **Data merging** across activity, sleep, calorie, and weight logs.  
- 🧹 **Date formatting** using `lubridate`.  
- ✅ Ensured consistency across datasets.  

### 🔍 **Exploratory Data Analysis**
- **Visualizations** using `ggplot2`:  
  - **Calories vs Steps**  
  - **Sleep vs Time in Bed**  
  - **Workout Intensity over Time**  
- Key insights on sedentary behavior, sleep health, and activity levels.  

### 🤖 **Predictive Analytics**
- Built a **Random Forest Model** to predict **future weight** based on activity, calorie burn, and BMI.  
- Evaluated using metrics like **Precision**, **Recall**, and **Accuracy**.  

---

## 📦 **Setup Instructions**

1. Clone this repository:  
   ```bash
   git clone https://github.com/sitharavs/FitBit-Predictions.git
   cd FitBit-Predictions
   ```

2. Install required packages:  
   ```R
   install.packages(c("dplyr", "ggplot2", "tidyr", "lubridate", "randomForest", "caret", "Metrics"))
   ```

3. Run the **`RMarkdown-Code.Rmd`** script in RStudio.  

---

## 📈 **Results**

### Insights:
- Sedentary time exceeds **24 hours per day** for some participants—too high!  
- Majority of participants average **7.5 hours of sleep**, which is healthy.  
- Average steps/day are **6,547**, but **8,000+ is recommended** for optimal health.  

---

## 🚀 **Future Work**
- Integrate other datasets (e.g., nutrition or menstrual cycles).  
- Improve the predictive model using additional algorithms (e.g., Gradient Boosting).  
- Build a user-friendly dashboard for real-time insights.  

---

## 👩‍💻 **Contributing**
Feel free to:  
- Open an **issue** if you spot a bug 🐞  
- Submit a **pull request** for improvements ✨  

