# Quantium Virtual Experience Program: Data Analytics Projects

Welcome to my submissions for the **Quantium Virtual Experience Program** in Data Analytics. This repository contains code and insights from three data-driven tasks that focus on customer purchasing behavior and store performance analysis.

---

## 🚀 Project Overview

The program consists of three tasks:

- **Task 1:** Data Preparation and Customer Analytics  
- **Task 2:** Experimentation and Uplift Testing  
- **Task 3:** Analytics and Commercial Application  

Each folder contains code files specific to the task, with the data files being provided by Quantium.

---

## 🛠️ Tools and Libraries Used

- **Python Version:** 3.10
- **Libraries:** `pandas`, `numpy`, `seaborn`, `sklearn`, `matplotlib`, `datetime`, `scipy`

---

## Task 1: Data Preparation and Customer Analytics

### 🎯 Objective:
Analyze customer transaction data to uncover purchasing behaviors and make commercial recommendations.

### 📝 Task Details:
We conducted an in-depth analysis of transaction data to explore customer segments, chip purchasing trends, and derive strategic insights.

### 🔍 Key Steps:
1. **Data Cleaning:**  
   Handled missing data, anomalies, and standardization of product names.  
   ![Cleaned Brand Names](https://github.com/MrMaxMind/Quantium-Virtual-Experience-Program/blob/main/Data%20Visualizations/Task%201/Brand_Names.png)

2. **Customer Segmentation Analysis:**  
   Analyzed purchasing behaviors by customer segments based on total sales, number of customers, and average purchases.  
   ![Total Sales by Segment](https://github.com/MrMaxMind/Quantium-Virtual-Experience-Program/blob/main/Data%20Visualizations/Task%201/Stage_Plot1.png)  
   ![Average Chips per Customer](https://github.com/MrMaxMind/Quantium-Virtual-Experience-Program/blob/main/Data%20Visualizations/Task%201/Average_Purchase.png)

### 📊 Insights:
- **Top Segments by Total Sales:**  
  1. Older Families (Budget)  
  2. Young Singles/Couples (Mainstream)  
  3. Retirees (Mainstream)  

- **Key Customer Segments:**  
  - Older Families exhibit high frequency of purchases.  
  - Doritos is a popular brand among Young Singles/Couples (Mainstream).

### 💡 Recommendations:
- **Older Families (Budget):** Focus on increasing purchase frequency through targeted promotions.  
- **Young Singles/Couples (Mainstream):** Partner with Doritos for a targeted branding campaign.  
- **Retirees (Mainstream):** Maximize promotional reach to capture their high purchase potential.

---

## Task 2: Experimentation and Uplift Testing

### 🎯 Objective:
Evaluate store trial performance by comparing trial stores against control stores to measure the impact of new store layouts on sales and customer metrics.

### 🔍 Key Steps:
1. **Selecting Control Stores:**  
   Used Pearson correlation and magnitude distance to find control stores for each trial store.

2. **Statistical Testing:**  
   Checked for statistically significant changes in total sales and customer behavior between trial and control stores.  
   ![Total Sales Trial vs Control1](https://github.com/MrMaxMind/Quantium-Virtual-Experience-Program/blob/main/Data%20Visualizations/Task%202/Compare%20performance%201.png)

### 📊 Insights:
- Trial stores 77 and 86 showed a significant increase in sales and customer numbers during the trial period.
- No significant change was observed for trial store 88.

### 💡 Recommendations:
- **Trial Store 77 & 86:** Consider extending the layout changes based on the observed uplift in sales.  
- **Trial Store 88:** Investigate potential differences or challenges specific to this store before proceeding.

---

## Task 3: Analytics and Commercial Application

### 🎯 Objective:
Deliver insights and recommendations to the Category Manager using the findings from Task 1 and Task 2.

### 📝 Key Deliverables:
- **Report Preparation:**  
  Created a comprehensive report using the Pyramid Principle framework. Included data visualizations, strategic insights, and actionable recommendations for the client.

### 📊 Key Insights:
- Focus on segment-specific promotions based on the chip purchasing trends identified in Task 1.
- Leverage the trial results from Task 2 to inform future store layout experiments.

### 💡 Recommendations:
- Expand targeted promotions for Older Families and Young Singles/Couples.
- Consider replicating successful store layout trials in similar stores.

---

## 📂 Repository Structure

- `Task 1/`: Data cleaning and customer analytics
- `Task 2/`: Experimentation and uplift testing
- `Task 3/`: Final report and commercial recommendations
- `Data Visualizations/`: All supporting charts and graphs

---

## Contributing
If you have suggestions or improvements, feel free to open an issue or create a pull request.

---

## *Thank you for visiting! If you find this project useful, please consider starring the repository. Happy coding!*
