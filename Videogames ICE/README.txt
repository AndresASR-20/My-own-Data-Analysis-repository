# 🎮 Video Game Success Pattern Analysis - Ice Store

Comprehensive analysis of video game sales data to identify patterns that determine commercial success and plan marketing strategies for 2017.

## 🎯 Project Objectives

**Business Problem:** Ice Store needs to identify which factors determine a video game's success to optimize advertising campaigns and detect promising projects.

**Key Questions Answered:**
- Which platforms and genres generate the highest sales?
- How do preferences vary by region (NA, EU, JP)?
- Do critic and user reviews impact sales?
- What temporal patterns exist in platform life cycles?

## 🛠️ Technologies Used

- **Python 3.8+**
- **pandas** - Data manipulation and analysis
- **NumPy** - Numerical calculations
- **matplotlib & seaborn** - Data visualization
- **scipy** - Statistical tests and hypothesis testing
- **Jupyter Notebook** - Development and documentation

## 📊 Dataset

**Source:** Historical video game sales data (up to 2016)
**Records:** 16,715 games
**Key Variables:**
- Sales by region (NA, EU, JP, Other)
- Gaming platforms
- Genres and ESRB ratings
- Critic and user scores

## 🔍 Analysis Methodology

### **1. Data Preparation**
- Column cleaning and normalization
- Missing value treatment (TBD, NaN)
- Data type conversion
- Total global sales calculation

### **2. Exploratory Analysis**
- Temporal evolution of releases and sales
- Platform life cycle analysis
- Sales distribution by genre and region
- Correlation between reviews and sales

### **3. Regional Analysis**
- User profiles by region (NA, EU, JP)
- Top 5 platforms and genres by market
- ESRB rating impact

### **4. Hypothesis Testing**
- H₁: Xbox One vs PC ratings (t-test)
- H₂: Action vs Sports genres (t-test)
- Significance level: α = 0.05

## 📈 Key Findings

### **🏆 Leading Platforms (2014-2016)**
- **PS4:** 139.36M in global sales
- **Xbox One:** 85.80M in global sales
- **3DS:** Dominant in Japanese market

### **🎯 Most Profitable Genres**
1. **Action:** 1,751.18M
2. **Sports:** 1,330.93M
3. **Shooter:** 1,037.37M

### **🌍 Regional Insights**
- **North America:** Prefers Action and Sports
- **Europe:** Balanced across multiple genres
- **Japan:** Strong preference for Role-Playing games

### **📊 Review Impact**
- Strong correlation between critic scores and sales (r=0.58)
- User scores show moderate correlation (r=0.34)
- Games with 75+ critic score: 3x higher average sales

## 🧪 Statistical Conclusions

### **Hypothesis Test Results:**
- **H₁:** No significant difference in Xbox One vs PC user ratings (p=0.12)
- **H₂:** Action games significantly outsell Sports games (p<0.001)

## 📁 Project Structure

```
ice-videogames-analysis/
├── data/
│   └── extract the datasets from the following link: https://drive.google.com/drive/folders/1k1FWkT5uzP4iJu3zux5lKp5N3fTYi9Rn?usp=drive_link
├── notebooks/
│   └── videojuegos ICE.ipynb
├── images/
│   └── visualizations/
├── requirements/
│   └── requirements.txt
└── README.md

## 🚀 Instalation & how it works?

  1. Clone the repository
  2. Download the datasets and save them at the same position where Jupyter Notebook is located, but inside a folder named "Datsets"
  2. Install dependencies: `pip install -r requirements.txt`
  3. Open the notebook: `videojuegos ICE.ipynb`

##8. 📧 Contact

  ##- LinkedIn: https://www.linkedin.com/in/luis-andres-aponte-san-roman/
  ##- Email: andres_laasr20@outlook.com
