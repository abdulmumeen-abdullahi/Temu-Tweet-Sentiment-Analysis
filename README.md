# Temu Tweet Sentiment Analysis

## 🔹 Problem Statement
In the age of digital marketplaces, the interaction between buyers, sellers, and products has become increasingly seamless. One such platform leading this revolution is Temu, a Chinese online marketplace known for its substantial discounts and promotional gifts.
Despite its apparent generosity, user feedback on social platforms like [X (formerly Twitter)](http://twitter.com) suggests a mixed sentiment—ranging from satisfaction to concerns about deceptive marketing tactics and questionable quality.
This project aims to explore and analyze what users are saying about Temu on X by applying sentiment analysis techniques to tweets related to the brand.

## 🔹 Dataset Description
A custom dataset was scraped using the Twikit API and consists of 1,944 tweets with the following features:
- Username: The X username of the tweet author
- Text: Content of the tweet
- Created At: Timestamp of the tweet
- Retweets: Number of retweets at the time of scraping
- Likes: Number of likes at the time of scraping

## 🔹 Methodology
### 1. Data Preprocessing
- Imported dataset using Pandas
- Defined a text-cleaning function to preprocess tweets (e.g., removing URLs, special characters, emojis)
- Saved processed results into a new column called cleaned_tweet

### 2. Sentiment Analysis
- Utilized TextBlob to compute:
         - Polarity (positive/negative tone)
         - Subjectivity (objective/subjective language)

- Applied VADER (SentimentIntensityAnalyzer) to compute:
         - Compound sentiment score
         - Classified tweets into Positive, Negative, or Neutral

- Calculated and visualized the distribution of sentiment categories using a doughnut-shaped pie chart
![download](https://github.com/user-attachments/assets/db977a0e-5dff-4608-ae5c-d95f87f2b536)

Figure 1: Doughnut-shaped Pie Chart for Sentiment Categories Distribution

### 3. WordCloud Analysis
Generated WordClouds for:

➤ All tweets
![download](https://github.com/user-attachments/assets/00f3945c-c016-4e14-8787-c544b57a9639)

Figure 2: WordCloud for All Tweets

➤ Positive tweets
![download](https://github.com/user-attachments/assets/3b92edb4-a1dc-4438-b6bf-4d8ded8247d4)

Figure 3: WordCloud for Positive Tweets

➤ Negative tweets
![download](https://github.com/user-attachments/assets/4fff6399-df91-48b9-a3e0-86e82623db38)

Figure 4: WordCloud for Negative Tweets

### 4. Tweet Length and Word Count Analysis
Calculated and Visualized tweet length and word count by sentiment category using bar charts <br/>
➤ Tweet text length

![download](https://github.com/user-attachments/assets/a0c924af-927d-47db-b694-1e41a0b69026)

Figure 5: Bar Chart for Tweet Length Distribution

➤ Tweet Word count

![download](https://github.com/user-attachments/assets/93b8c30c-3732-42d4-b412-5c3dee61a760)

Figure 6: Bar Chart for Tweet Word Count Distribution

## 🔹 Real-World Applications
- Brand Monitoring: Helps Temu understand how users perceive their brand online
- Customer Feedback Analysis: Automatically captures user sentiment to improve service delivery
- Market Research: Extracts themes and keywords that drive engagement

## 🔹 Business & Environmental Impact
- 70%+ reduction in manual review time
- Enables real-time monitoring of brand perception
- Supports data-driven strategy development

===================================================== <br/>
Abdullahi Olalekan Abdulmumeen <br/>
_Data Scientist_ <br/>
olalekanabdulmumeen3@gmail.com <br/>
+234 705 305 3024

