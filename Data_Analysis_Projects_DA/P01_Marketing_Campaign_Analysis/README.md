# P01_Marketing Campaign Analysis with A/B Testing  

## Situation

A company launched multiple marketing campaigns but was unsure which campaigns were truly effective and whether observed differences in performance were statistically significant.

The business wanted to analyze historical campaign data to understand:
- Which marketing campaigns had higher acceptance rates
- Which customer attributes (income, purchase behavior) influenced campaign response
- Whether differences between campaigns were due to real impact or random variation

This project uses a real marketing dataset containing customer demographics, purchase history, campaign responses, and engagement metrics.

## Task

The objectives of this project were to:

- Clean and prepare raw marketing data for analysis  
- Perform exploratory data analysis (EDA) to identify patterns and trends  
- Apply **A/B Testing** to compare campaign performance statistically  
- Evaluate campaign effectiveness across different customer segments  
- Provide actionable, data-driven recommendations to improve future marketing strategies  

## Action

###  1. Data Loading & Cleaning
- Loaded the dataset into a Jupyter Notebook  
- Handled missing values (e.g., replaced missing income values with median income)  
- Corrected inconsistent or mislabeled categorical values  
- Ensured correct data types for numerical and categorical variables  

###  2. Exploratory Data Analysis (EDA)
- Analyzed dataset structure (rows, columns, data types)  
- Examined customer demographics such as age and income  
- Visualized campaign acceptance rates across multiple campaigns  

**Key EDA Findings:**
- Campaign acceptance rates vary significantly across campaigns  
- Higher-income customers show higher campaign acceptance  
- Certain customer segments respond better to specific campaigns  

### 3. A/B Testing (Campaign Comparison)

To validate whether observed differences between campaigns were statistically significant:

- Selected two or more campaigns for comparison (Control vs Variant)  
- Defined hypotheses:  
  - **Null Hypothesis (H₀):** No significant difference in acceptance rates between campaigns  
  - **Alternative Hypothesis (H₁):** A significant difference exists in acceptance rates  
- Applied statistical testing (e.g., t-test / proportion test)  
- Evaluated p-values against a defined significance level  

**Purpose of A/B Testing:**
- Ensure campaign performance differences are not due to random chance  
- Support business decisions with statistical evidence  

### 4. Insights & Visualization
- Identified the most successful campaigns based on acceptance percentage  
- Analyzed the relationship between income and campaign acceptance  
- Compared purchase behavior between customers who accepted campaigns and those who did not  

**Visualizations Used:**
- Bar charts for campaign acceptance rates
- Histograms for income distribution 
- Line charts for purchase trends across campaigns  

### 5. Insights Summary
Translated analytical and statistical findings into business insights:
- Focus future campaigns on customer segments with statistically higher acceptance rates  
- Allocate more budget to campaigns proven effective through A/B testing  
- Personalize marketing strategies based on customer income and spending behavior

## Visualizations Charts
-- Visualize the distribution of ad clicks and conversions for Facebook and AdWords campaigns using histograms with KDE to understand frequency, spread, and data distribution

<img width="1249" height="557" alt="image" src="https://github.com/user-attachments/assets/dce8e8ef-6fc4-4dc3-8841-2a327565c983" />

-- Plotting scatter plots for Facebook and AdWords Clicks vs Conversions. Using Matplotlib and Seaborn with a figure size and subplots

<img width="1257" height="559" alt="image" src="https://github.com/user-attachments/assets/f6319974-a3bd-4591-8b43-d9e5921bbe76" />

-- Plotting Linear Regression for Facebook Ads

<img width="906" height="687" alt="image" src="https://github.com/user-attachments/assets/6d069701-f6f2-40c5-b71a-ca26e1c3b3b5" />

-- Plotting Weekly Facebook Ad Conversions

<img width="894" height="597" alt="image" src="https://github.com/user-attachments/assets/68e6f3af-225a-447f-89bc-abe2e6d9ec4d" />

-- Plotting Monthly Facebook Ad Conversions

<img width="884" height="599" alt="image" src="https://github.com/user-attachments/assets/b363fbfc-007b-416b-bc82-5c0447f1cf2d" />

## Results

By the end of the project, the following outcomes were achieved:

- ✔ Identified top-performing marketing campaigns  
- ✔ Validated campaign performance using A/B Testing  
- ✔ Determined key customer factors influencing campaign acceptance  
- ✔ Delivered statistically backed recommendations for marketing optimization  

These results empower the business to make **confident, data-driven marketing decisions** and improve overall campaign ROI.

## Tools & Technologies Used

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- SciPy (for A/B Testing)  
- Jupyter Notebook  

## Project Folder Structure 

<img width="728" height="477" alt="image" src="https://github.com/user-attachments/assets/5b1f9edb-43f4-4b95-b25e-20e109813ff0" />

## Conclusion

This project demonstrates an end-to-end marketing analytics workflow combining:
- Data cleaning
- Exploratory data analysis
- Statistical hypothesis testing (A/B Testing)
- Business insight generation

It reflects real-world decision-making processes used by data analysts and marketing teams.
