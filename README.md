# Exploratory Data Analysis (EDA) Report


## 1. Introduction
This report presents a detailed Exploratory Data Analysis (EDA) of a dataset containing passenger information, including demographics, ticket details, and survival status. The objective is to identify patterns, relationships, and key factors influencing survival.

## 2. Data Overview
The dataset consists of 712 entries with 11 attributes, which provide insights into the passengers' demographics and travel details. The key variables are:

- **PassengerId**: Unique identifier for each passenger  
- **Survived**: Binary indicator of survival (1 = Survived, 0 = Did not survive)  
- **Pclass**: Ticket class (1st, 2nd, or 3rd)  
- **Name**: Full name of the passenger  
- **Age**: Age of the passenger in years  
- **SibSp**: Number of siblings/spouses aboard the ship  
- **Parch**: Number of parents/children aboard the ship  
- **Ticket**: Ticket number  
- **Fare**: Cost of the ticket  
- **Cabin**: Cabin number (if available)  
- **Embarked**: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)  

### 2.1 Data Cleaning
The dataset was preprocessed using Excel to handle missing values and correct inconsistencies before conducting the analysis.

## 3. Exploratory Data Analysis (EDA)

### 3.1 Survival Distribution
A count plot of survival status revealed that a significant portion of passengers did not survive. 

#### Key Observations:
- **1st class passengers had a higher survival rate** compared to those in 2nd and 3rd class.  
- **Women and children** had a better chance of survival.  
- **Higher fare prices were associated with a higher survival rate.**  

### 3.2 Correlation Analysis
A correlation heatmap was used to identify relationships between variables.

#### Key Findings:
- **Survived & Pclass (-0.34)** → Higher-class passengers were more likely to survive.  
- **Survived & Fare (+0.26)** → Higher fares indicate a better survival chance.  
- **Pclass & Fare (-0.55)** → 1st class passengers paid more, 3rd class paid less.  
- **SibSp & Parch (+0.41)** → Passengers with family members onboard tended to be in groups.  

### 3.3 Outlier Detection
Boxplots for **Fare** and **Age** revealed the presence of outliers, particularly in fare values, suggesting that a few passengers paid exceptionally high prices for tickets.

### 3.4 Age vs. Survival
Passengers were categorized into three age groups: 
- **Children (<10 years)**: Highest survival rate (59.38%).  
- **Adults (10-50 years)**: Moderate survival rate (39.15%).  
- **Elderly (>50 years)**: Lowest survival rate (33.33%).  

### 3.5 Fare vs. Survival
Passengers were categorized based on ticket fare:
- **Low (<$10)**: 20.09% survival rate.  
- **Medium ($10-$50)**: 42.65% survival rate.  
- **High ($50-$100)**: 68.18% survival rate.  
- **Very High (>$100)**: 75.00% survival rate.  

### 3.6 Survival Rate by Title
Passengers' titles were extracted from their names and categorized. The analysis revealed that:
- **Royalty and higher social status titles** had a higher survival rate.  
- **Miss and Mrs. titles** had better survival chances than male titles.  
- **Rare titles (Dr, Rev, Major, etc.)** had lower survival rates.  

### 3.7 Survival Rate by Passenger Class (Pclass)
- **1st class passengers had the highest survival rate (~63%)**, while **3rd class had the lowest (~25%)**.  
- This confirms that social class played a major role in survival chances.  

## 4. Conclusion

### 4.1 Summary of Findings
- **Ticket class, fare, gender, and age** were key determinants of survival.  
- **1st class passengers had a significant survival advantage** over 2nd and 3rd class.  
- **Women and younger passengers had a higher probability of survival.**  
- **Passengers who paid more for their tickets were more likely to survive.**  
- **Titles and social status influenced survival chances.**  


