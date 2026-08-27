# 🏙️ Tokyo Airbnb Revenue Analysis

An end-to-end analytics project examining the factors associated with Airbnb listing revenue in Tokyo. The analysis explores how listing characteristics, host attributes, neighborhood location, property type, amenities, and guest review signals relate to estimated annual revenue.

The project combines **Python, JMP, Tableau, and Excel** for data preparation, exploratory analysis, statistical modeling, visualization, and business interpretation.

---

## 🎯 Project Objective

The primary business question for this project was:

> **What listing attributes, host characteristics, neighborhood factors, and guest review signals most significantly influence Airbnb listing prices and estimated annual revenue in Tokyo?**

The analysis was designed to identify meaningful revenue drivers and translate the statistical findings into actionable insights for Airbnb hosts and other stakeholders in the short-term rental market.

---

## 🔍 Analysis Approach

The project followed an end-to-end analytical workflow:

1. **Data Preparation and Cleaning**
   - Reviewed and cleaned Airbnb listing data
   - Handled missing values and unnecessary variables
   - Prepared analysis-ready features
   - Created transformed variables required for statistical modeling

2. **Exploratory Data Analysis**
   - Conducted univariate analysis of major listing and revenue variables
   - Examined relationships between listing characteristics and estimated annual revenue
   - Compared revenue across host, property, and neighborhood characteristics
   - Evaluated relationships involving reviews, amenities, bedrooms, accommodations, and other listing attributes

3. **Regression Modeling**
   - Linear regression
   - Semi-log regression
   - Log-log regression
   - Model comparison
   - Residual and diagnostic analysis

4. **Business Interpretation**
   - Evaluated significant predictors of estimated annual revenue
   - Compared the performance of alternative regression specifications
   - Translated statistical findings into practical business insights

---

## 📊 Key Findings

The analysis identified several important patterns associated with estimated annual Airbnb revenue in Tokyo:

- **Location is an important revenue driver**, with listings in Central Tokyo showing particularly strong revenue performance.
- **Superhost status is positively associated with annual revenue**, suggesting that host reputation and service quality can have meaningful business value.
- **Property and room type matter**, with entire-place listings generally demonstrating stronger revenue potential than private or shared-room alternatives.
- **Guest review signals are associated with revenue performance**, highlighting the importance of customer experience and reputation.
- Listing characteristics such as **accommodates, bedrooms, and amenities** also contribute to differences in revenue performance.
- Among the regression specifications evaluated, the **log-log model provided the strongest overall explanatory performance** and was selected as the final model.

---

## 📈 Visualizations Performed as Part of the Analysis

Visualizations were developed throughout the analysis to explore distributions, relationships between variables, revenue patterns, and regression model diagnostics.

The analysis includes:

- Univariate analysis of key listing and revenue variables
- Bivariate analysis of listing characteristics and estimated annual revenue
- Revenue comparisons across neighborhoods, property types, and Superhost status
- Relationships between reviews, amenities, accommodations, bedrooms, and revenue
- Regression residual and diagnostic plots

All visualizations generated as part of the analysis are available in the [`Visualization`](Visualization/) folder.

---

## 🛠️ Tools & Technologies

| Tool | Application |
|------|-------------|
| **Python** | Data preprocessing, cleaning, transformation, and exploratory analysis |
| **Pandas / NumPy** | Data manipulation and preparation |
| **JMP** | Statistical analysis, regression modeling, model comparison, and diagnostics |
| **Tableau** | Exploratory and business-focused data visualization |
| **Excel** | Supporting data transformations and log conversions |
| **Jupyter Notebook** | Documentation and execution of the Python analysis workflow |

---

## 📐 Statistical Modeling

Three regression specifications were evaluated during the project:

### Linear Regression

Used as the initial baseline model for examining relationships between listing characteristics and estimated annual revenue.

### Semi-Log Regression

Introduced a logarithmic transformation of the dependent variable to improve model specification and interpretation.

### Log-Log Regression

Applied logarithmic transformations to relevant variables and provided the strongest explanatory performance among the evaluated models.

The **log-log regression model was selected as the final model** based on model performance and diagnostic evaluation.

---

## 📁 Repository Structure

```text
tokyo-airbnb-revenue-analysis/
│
├── Final_data/
│   └── final_tokyo_listing_updated_april_26.csv
│
├── Visualization/
│   ├── BivariateAnalysis_...
│   ├── ResidualFit_...
│   └── UnivariateAnalysis_...
│
├── final_Airbnb_Tokyo_listing_analysis.ipynb
├── Airbnb_Tokyo_listing.pptx
├── README.md
└── .gitignore
```

### Repository Contents

- **`Final_data/`** – Processed, analysis-ready dataset used in the project
- **`Visualization/`** – Univariate, bivariate, and regression diagnostic visualizations generated during the analysis
- **`final_Airbnb_Tokyo_listing_analysis.ipynb`** – Python notebook containing data preprocessing and supporting analysis
- **`Airbnb_Tokyo_listing.pptx`** – Final project presentation summarizing the methodology, findings, and recommendations

---

## 📌 JMP Analysis

The primary statistical modeling was conducted using **JMP**, including:

- Univariate analysis
- Bivariate analysis
- Correlation analysis
- Linear regression
- Semi-log regression
- Log-log regression
- Model comparison
- Residual analysis
- Model diagnostics

The original JMP project file is not included in this repository due to file-size limitations. Analytical outputs and visualizations from the analysis are included in the `Visualization` folder.

---

## 💾 Data Availability

The original raw Airbnb dataset is not included in this repository due to its large file size.

Instead, the repository contains the **processed analysis-ready dataset** used for the final analytical workflow and modeling.

---

## 💡 Business Takeaways

The results suggest that Airbnb revenue performance in Tokyo is influenced by a combination of **location, host reputation, property characteristics, listing capacity, amenities, and guest experience**.

For hosts, the findings emphasize the potential value of:

- Maintaining strong guest ratings and service quality
- Building Superhost-level performance
- Understanding neighborhood-specific revenue potential
- Optimizing property configuration and listing characteristics
- Using data-driven pricing and positioning strategies

Rather than relying on a single characteristic, the analysis indicates that revenue performance is shaped by several interconnected listing and market factors.

---

## 📎 Project Presentation

The complete project methodology, analysis, model results, visualizations, and business recommendations are available in:

**[`Airbnb_Tokyo_listing.pptx`](Airbnb_Tokyo_listing.pptx)**

---

## 👤 Author

**Devika Desai**  
Master of Science in Business Analytics  
Seattle University
