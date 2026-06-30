# Social Media Engagement Analysis  
### Sentiment-Based Marketing Analytics Dashboard

## Project Overview

Social media has become one of the most important channels for brand communication and customer engagement. However, businesses often struggle to measure campaign effectiveness and understand what factors drive user interaction.

This project analyzes over **12,000 social media posts** across multiple platforms to uncover patterns in:

- User sentiment
- Engagement behavior
- Campaign performance
- Hashtag effectiveness
- Geographic audience distribution

The objective is to transform raw social media data into actionable business insights for improving digital marketing strategies.

---

## Business Problem

Marketing teams frequently face questions such as:

- Which platform generates the highest engagement?
- What emotional tone drives stronger audience interaction?
- Which campaigns perform best?
- How do hashtags impact reach and impressions?
- Which regions contribute the most engagement?

This project was built to answer these questions through data analytics and sentiment analysis.

---

## Dataset

**Source:** Kaggle  
**Size:** 12,000 social media posts

### Platforms:
- Instagram
- Facebook
- Twitter
- Reddit
- YouTube

## Tech Stack

### Data Processing
- Python
- Pandas
- NumPy

### NLP / Machine Learning
- BERT
- Hugging Face Transformers
- PyTorch

### Database
- SQL Server
- T-SQL

### Visualization
- Tableau

---

## Project Workflow

Raw Data (CSV)  
↓  
Data Cleaning & Transformation  
↓  
Text Preprocessing  
↓  
Sentiment Classification (BERT)  
↓  
Data Modeling (SQL Server)  
↓  
Analytical Queries (T-SQL)  
↓  
Interactive Dashboard (Tableau)

---

## Key Contributions

### 1. Data Cleaning & Transformation

Processed and standardized raw data by:

- Cleaning missing values
- Standardizing timestamps
- Extracting hashtags and mentions
- Mapping language codes
- Splitting locations into region/country
- Identifying brands and products
- Calculating engagement rates

---

### 2. Sentiment Analysis

Built a BERT-based sentiment analysis pipeline to classify:

### Emotion Types:
- Joy
- Sadness
- Anger
- Fear
- Surprise
- Disgust
- Shame

### Sentiment Categories:
- Positive
- Neutral
- Negative

Model accuracy: **~70–75%**

---

### 3. Database Design

Designed a relational data warehouse using **Snowflake Schema**

Core tables:
- Users
- Posts
- Campaigns
- Brands
- Products
- Analytics

This structure improves analytical performance and scalability.

---

### 4. Dashboard Development

Built interactive Tableau dashboards for:

- Platform performance analysis
- Campaign effectiveness tracking
- Sentiment distribution
- User behavior analysis
- Geographic engagement mapping
- Trending hashtag detection

---

# Dashboard Preview

## 1. Overview Dashboard

Provides a high-level summary of social media performance.

### Key Metrics:
- Total Posts: **12,000**
- Total Likes: **258M+**
- Total Comments: **86M+**
- Total Shares: **58M+**
- Total Impressions: **599M+**

### Key Insight:
Instagram achieved the highest average engagement among all platforms.

![Overview Dashboard](./dashboard/dashboard_images/overview.png)

---

## 2. Campaign Performance Dashboard

Analyzes campaign effectiveness and product engagement.

### Key Insight:
Black Friday generated the highest engagement, indicating strong urgency-driven consumer behavior.

![Campaign Dashboard](./dashboard/dashboard_images/campaign.png)

---

## 3. Sentiment Analysis Dashboard

Visualizes emotion distribution and sentiment impact on engagement.

### Key Insight:
Positive sentiment accounted for **73.59%** of all posts and generated the strongest impressions.

![Sentiment Dashboard](./dashboard/dashboard_images/sentiment.png)

---

## 4. User Behavior Dashboard

Tracks regional user activity and toxic engagement behavior.

### Key Insight:
North America and Europe represented the highest user concentration, while toxic engagement peaked in the USA.

![User Dashboard](./dashboard/dashboard_images/user.png)

---

## Key Insights

### Platform Performance
- Instagram showed the highest engagement rate.
- Facebook ranked second in total interactions.

### Sentiment Distribution
- Positive sentiment represented **73.59%** of all content.
- Joy-based content produced the highest impressions.

### Campaign Performance
Top-performing campaigns:
- Black Friday
- Fall Collection
- SpringBlast2025

Black Friday outperformed due to urgency-driven buying behavior.

### User Behavior
- Peak impressions were concentrated in North America and Europe.
- Toxic interactions were significantly higher in the USA.

### Hashtag Effectiveness
Trending hashtags increased visibility by approximately **20%**.

---

## Business Recommendations

Based on the analysis:

- Focus engagement-driven campaigns on Instagram.
- Use positive emotional framing for higher reach.
- Leverage seasonal campaigns such as Black Friday.
- Optimize hashtag strategy for better impressions.
- Monitor negative sentiment early to reduce brand risks.

---

## Skills Demonstrated

- Data Cleaning
- NLP
- Sentiment Analysis
- SQL Query Optimization
- Data Modeling
- Dashboard Design
- Business Intelligence
- Marketing Analytics

---

## Repository Structure

```bash
social-media-engagement-analysis/
│── data/
│── notebooks/
│── dashboard/
│   ├── dashboard_images/
│── README.md
│── requirements.txt
```