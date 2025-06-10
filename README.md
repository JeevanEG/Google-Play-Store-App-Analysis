# Google-Play-Store-App-Analysis

## 📌 Overview

This project presents an **Exploratory Data Analysis (EDA)** of the Google Play Store dataset. It aims to uncover trends in app categories, pricing, ratings, installs, and content targeting. The insights are valuable for developers, marketers, and analysts seeking to understand the dynamics of app performance on the Play Store.

---

## 📂 Files Included

| File                                        | Description                                                                         |
| ------------------------------------------- | ----------------------------------------------------------------------------------- |
| `EDA_playstore.ipynb`                       | Jupyter Notebook performing EDA on the Play Store dataset                           |
| `Google_Play_Store_App_Analysis_Report.pdf` | Full project report detailing background, methodology, visualizations, and findings |

---

## 🧠 Project Objectives

* Explore characteristics of apps available on the Google Play Store.
* Analyze distribution of app ratings, prices, and installs.
* Identify trends across app categories.
* Compare free vs. paid apps in terms of user engagement.
* Understand the impact of content rating and update frequency on installs.

---

## 🗃 Dataset Details

* **Size**: \~10,000 rows × 13 columns
* **Key Columns**:

  * `Category`, `Rating`, `Reviews`, `Size`, `Installs`
  * `Price`, `Content Rating`, `Genres`, `Last Updated`
  * `Current Version`, `Android Version`

---

## 🔧 Preprocessing Steps

* **Missing Value Handling**: Filled missing ratings with the median.
* **Duplicate Removal**: Removed duplicate app entries.
* **Data Type Cleaning**:

  * Converted installs and prices to numerical values.
  * Standardized app size (MB/KB) and content rating.
* **Final Dataset**: Cleaned and ready for visual EDA and statistical analysis.

---

## 📊 Exploratory Analysis Insights

* **Top Categories**: `Family`, `Game`, and `Tools` dominate app counts.
* **Ratings**: Majority of apps are rated between 4.0 and 4.5.
* **Free vs. Paid**:

  * Free apps are vastly more common and receive more installs.
  * Paid apps are less common but may target niche audiences.
* **Spending Trends**:

  * `Finance`, `Lifestyle`, and `Family` categories saw the most user spending.
* **Rating vs. Installs**: Positive correlation between ratings and install count.
* **Content Ratings**: Apps rated "Everyone" tend to have higher install volumes.
* **Update Activity**: Frequently updated apps tend to have more installs.

---

## 📈 Visualizations Used

* **Histograms**: Ratings, installs
* **Bar Charts**: App category distribution, content ratings
* **Scatter Plots**: Rating vs. installs, price vs. installs

---

## 🔚 Conclusion

This analysis reveals that **category, pricing, and user ratings** play a key role in app performance. Apps with broader appeal (`Everyone` rated), lower prices (or free), and frequent updates are more likely to achieve higher install numbers. The project serves as a strong foundation for further modeling, such as **app success prediction** or **market segmentation**.

---

## 🧑‍💻 Author

**Jeevan EG**
`1RVU22CSE069`
RV University, Bengaluru
Academic Year: 2024–2025

---
