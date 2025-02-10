# 🚗 **Car Data Analysis (Python)**

## 📄 Context
A well-known car manufacturer has collected an extensive dataset of vehicle information, including make, model, engine specifications (including power, displacement and fuel type), fuel consumption (city and motorway), price and market segment. The company now wants to gain valuable insights by thoroughly analysing this dataset to make better, data-driven business decisions.

---

## 🎯 Objective
The aim of this project is to develop a deeper understanding of customer preferences and market trends within the automotive industry by analysing a comprehensive vehicle dataset. By identifying correlations between vehicle features such as performance, equipment, price and sales figures, recommendations for action for product development, marketing and sales are to be derived in order to strengthen the company's competitiveness.

---

## 🚀 Approach and Implementation
For this analysis, I chose Python as my preferred programming language. Using the libraries Pandas, NumPy, Matplotlib, and Seaborn, I was able to efficiently prepare, analyze, and visualize the data.

The analysis of the vehicle dataset revealed that various vehicle characteristics have a significant impact on price, popularity, and fuel consumption. For example, there is a strong positive correlation between engine power and selling price. Vehicles with higher horsepower generally command higher prices. Additionally, it was found that larger vehicles such as SUVs and vans have higher average selling prices.

---

## 📊 Project Steps

**Step 1: Data Cleaning** _(This step involves preparing the raw data for analysis by)_
* Identifying and Handling Missing Values: Identifying missing values in the dataset and deciding on appropriate handling methods (e.g., imputation, removal of rows).
* Ensuring Data Type Consistency: Converting data types of columns to ensure accurate analysis (e.g., converting the 'Year' column to integer).
* Filtering the Dataset: Removing any data points that do not meet the analysis criteria (e.g., filtering the dataset to include only cars manufactured after 1995).
* Standardizing Text Data: Converting text entries in the "Vehicle Style" and "Market Category" columns to lowercase for consistency and easier analysis.
  
**Step 2: Feature Engineering** _(This step involves creating new features from the existing data to enhance the analysis)_
* Calculate Total MPG: A new column, "Total MPG", is created by calculating the average of "city mpg" and "highway MPG" to provide a more comprehensive measure of fuel efficiency.
* Calculate Price per HP: A new column, "Price per HP", is created by dividing the Manufacturer's Suggested Retail Price (MSRP) by the "Engine HP". This metric provides valuable insights into the price-to-performance ratio of different vehicles.

**Step 3: Exploratory Data Analysis (EDA)**  _(This step involves exploring and visualizing the data to gain insights and identify patterns)_
* Descriptive Statistics: Calculate key statistics (mean, median, standard deviation) for "Engine HP", "MSRP", "Popularity", "highway MPG", and "city mpg" to understand their distributions and identify potential outliers.
* Group Analysis: Group the data by "Driven_Wheels", "Vehicle Size", and "Engine Cylinders" to analyze how average "MSRP" and "Popularity" vary across these categories.
* Visualizations: Create various visualizations to explore the data:
* Correlation Analysis: Investigate the correlation between key variables ("Engine HP", "MSRP", "Popularity", "city mpg", and "highway MPG") to identify potential relationships.

<img width="1049" alt="Screenshot 2025-02-07 at 21 34 17" src="https://github.com/user-attachments/assets/86b95850-77a0-4f38-b090-60398b204963" />

---

## 🔍 Insights
* **Pricing:**  
  The analysis revealed that factors like engine power, vehicle size, and additional features significantly influence vehicle pricing. These findings can inform pricing strategies to maximize profitability.
* **Product Development:**  
  The data indicates that there is a strong demand for specific vehicle types, such as SUVs and electric vehicles, and specific features like advanced safety systems and connectivity options. This information can be used to prioritize product development efforts.
* **Marketing:**  
By identifying customer segments and their preferences, marketing campaigns can be tailored to specific target audiences, increasing their effectiveness.
---

## 🔮 Future Work
* Advanced Feature Engineering:
    * Create more sophisticated features: Consider creating features that capture the age of the vehicle, the ratio of horsepower to weight, or the environmental impact of the vehicle.
    * Utilize external data: Incorporate external data sources such as economic indicators, fuel prices, and competitor information to enhance the analysis.

* Predictive Modeling:
    * Develop predictive models to forecast vehicle prices based on various factors.
    * Build models to predict the popularity of new vehicle models.
    * Explore the use of machine learning techniques for customer churn prediction.

* Sustainability Analysis:
    * Analyze the environmental impact of different vehicle types and technologies.
    * Investigate the potential for electric vehicles and alternative fuel sources.


By pursuing these avenues of future work, the company can gain a deeper understanding of the automotive market, make more informed business decisions, and stay ahead of the competition.

---

## 🌟 Standout Section
Beyond the core requirements, I enhanced my analysis by introducing the 'Total MPG' feature, which provided a more comprehensive measure of fuel efficiency. By stratifying the data by vehicle size and visualizing the results, I was surprised to find that not only the vehicle size but also the engine type, particularly small engines in large vehicles, had a significant impact on fuel consumption. This finding opens up new questions regarding the optimization of drive trains, the development of more efficient vehicle concepts, and the potential for engine downsizing while maintaining adequate performance.

---

## 📋 Executive Summary

---

## 🔗 Links
* [Google Colabs Notebook](hhttps://colab.research.google.com/drive/1867ErT9_cWf1LzrVDklDDi1wnbPa-sc4?usp=sharing)

---

## ✅ Recommendations
* Drive innovation by developing niche models that address untapped market segments, such as electric sports cars or compact SUVs with off-road capabilities, to enhance brand image and attract new customer groups.
* Implement dynamic pricing strategies that consider real-time demand, competitor pricing, and vehicle features to optimize profitability and offer personalized deals to individual customers.
* Leverage data-driven personalization to create a seamless and engaging customer journey across all touchpoints, from online research to in-store experiences, to build stronger customer relationships.

By pursuing these avenues of future work, the company can gain a deeper understanding of the automotive market, make more informed business decisions, and stay ahead of the competition.











