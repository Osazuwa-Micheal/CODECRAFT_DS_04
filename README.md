# Sentiment Analysis of Social Media Data


## 1. Introduction
This report explores sentiment patterns in Twitter data to understand public opinion on various brands and topics. The analysis involves data preprocessing, sentiment categorization, and visualization to uncover trends in public perception.

## 2. Data Overview
The dataset is compiled from two sources:
- **twitter_training.csv**
- **twitter_validation.csv**

Both datasets were merged into a single dataset containing the following attributes:
- **ID**: Unique identifier for each tweet
- **Entity**: Brand, product, or topic mentioned in the tweet
- **Sentiment**: Sentiment classification (Positive, Negative, or Neutral)
- **Tweet**: Text of the tweet

### 2.1 Data Cleaning
To ensure data reliability, the following preprocessing steps were applied:
- **Irrelevant sentiment labels removed** to focus on meaningful analysis.
- **Missing values handled** by dropping tweets with null content.
- **Text standardization** by converting all tweets to lowercase for consistency.

## 3. Sentiment Analysis

### 3.1 Sentiment Distribution
A bar chart was generated to illustrate the proportion of each sentiment type in the dataset.

#### Key Observations:
- Positive tweets were slightly more prevalent than negative tweets.
- Neutral tweets comprised a smaller fraction of the dataset.
- Understanding sentiment distribution helps assess overall public opinion.

### 3.2 Sentiment Trends by Entity
Sentiment was analyzed for the top 10 most frequently mentioned brands or topics.

#### Key Findings:
- Sentiment distribution varied significantly across different entities.
- Some brands received predominantly positive sentiment, while others faced more criticism.
- Stacked bar charts provided insights into public perception trends.

## 4. Conclusion and Recommendations

### 4.1 Summary of Findings
- **Sentiment analysis provides valuable insights into public perception of brands and topics.**
- **Entities with a high proportion of negative sentiment** may need to address public concerns.
- **Word cloud analysis** highlights the main drivers behind different sentiment types.




