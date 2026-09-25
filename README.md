# 🍎 Apple Fruit Market Analysis: An EDA and Web Scrapping Approach
*A data-driven exploration of Apple’s performance, products, and market indicators.*

## 📌 **`Project Overview`**

- This project is a part of my learning journey in Exploratory Data Analysis (EDA).
- The main goal of this project was to understand how apple market prices and arrivals change across regions and time, using real data collected from the web.
- Instead of working on a ready-made dataset, I collected the data myself through web scraping, cleaned it, and then explored it using Python.
- This helped me understand how real-world data looks before analysis and how much effort goes into preparing it.

## 🎯 **`Objectives`**
- To collect apple market data from online sources
- To clean and organize raw data for analysis
- To explore price trends, arrivals, and variations using EDA
- To visualize patterns that can help understand market behavior 

## 🧰 **`Tools & Technologies`**

* **Python**
* **Libraries:**
  * Pandas
  * NumPy
  * Matplotlib
  * Seaborn
* **Jupyter Notebook**

## ⚙️ **Steps to Run the Project**

1. Clone the repository
2. Install required Python libraries
3. Open the notebooks in Jupyter
4. Run them in sequence:
   * 01_Data_Cleaning
   * 02_EDA
   * 03_Insights

## 🔍 **Key Techniques Used**

* Handling missing values
* Cleaning inconsistent formats
* Feature extraction
* Statistical analysis
* Trend analysis
* Data visualization

## 📈 **`Key Insights `**

`NOTE: These insights are derived from the exploratory data analysis performed in this project. They reflect the patterns observed in the dataset, but further analysis may reveal additional insights.`

### 🍎 **1. Variety & Grade Preferences**

* *Delicious* is the most frequently traded apple variety by a huge margin.
* Over **95%** of all apples sold belong to just two grades: **Medium** and **Large**, showing strong market preference for bigger sizes.
* Small-grade apples form less than **5%** of total records, indicating very low demand.

### 🏙️ **2. Pricing Differences Across Districts**

* **Udhampur** consistently records the **highest average apple prices** (₹11,000+/Quintal).
* **Kathua** also shows high pricing, while **Anantnag** and **Badgam** remain the most affordable markets (~₹4,000/Quintal).
* **Srinagar** shows the **widest price variation**, making it the most unpredictable market.
  
### 📉 **3. Supply vs Price Relationship**

* When **arrivals increase**, the **modal price drops** — clear demand–supply behavior.
* The **highest price spikes** (up to ₹35,000/Quintal) occur when arrivals are extremely low.
* These premium prices belong almost entirely to the **Large grade**, highlighting its high value at low supply.

### 🗓️ **4. Seasonal Market Activity**

* Apple records appear **throughout the year**, but market activity surges nearly **20x in April**, showing a seasonal peak.
* Most other months stay steady with low, consistent records.

### 💰 **5. Price Trends by Variety**

* The **‘Apple’ variety** is the **most expensive**, averaging above ₹8,000/Quintal.
* The popular **Delicious variety** maintains a strong price (~₹7,500/Quintal).
* Varieties like **Kesri** and **Condition** are at the bottom with prices around ₹2,500/Quintal.

### 📌 **6. Market Stability & Risk**

* The **American** variety has the **most stable pricing**, making it a reliable trading option.
* **Srinagar** market carries the highest profit potential *but also the highest risk* due to unpredictable price swings.

## 🧠 *"`Learnings`**

- Learned how to work with raw, unstructured data
- Understood the importance of data cleaning before analysis
- Improved my skills in Exploratory Data Analysis
- Gained confidence in extracting insights using visualizations

## 🚀 **`Future Enhancements`**

* Build an interactive dashboard using **Power BI** or **Tableau**
* Add forecasting models to predict future Apple product trends
* Perform sentiment analysis on customer reviews
* Automate reports using Python scripts
