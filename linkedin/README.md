📊 LinkedIn App Review Analysis
This project performs an exploratory data analysis (EDA) on user reviews of the LinkedIn mobile app. The goal is to understand user sentiment, identify common themes in feedback, and provide insights into areas of improvement for the app.

🧾 Project Overview
Millions of users rely on the LinkedIn app for networking and career growth. User reviews provide a valuable source of feedback that can guide developers and stakeholders in improving the user experience. This notebook analyzes a dataset of reviews from the LinkedIn app to:

Explore review distributions by rating and date

Perform text preprocessing and word frequency analysis

Visualize common keywords and complaints

Detect sentiment trends in user feedback

📁 Dataset
The dataset consists of user reviews scraped from the LinkedIn app on the Google Play Store. It includes:

Review: Text of the user's review

Rating: Star rating given by the user (1 to 5)

Date: Date the review was posted

Translated_Review: English translation of non-English reviews (if applicable)

Sentiment: Pre-labeled sentiment (Positive, Neutral, Negative) or inferred

⚙️ Tools & Libraries
Python 3

Pandas

Matplotlib / Seaborn

NLTK / TextBlob (for sentiment analysis)

WordCloud

Regular Expressions

📌 Key Findings
Most users give 4–5 star ratings, but 1-star reviews highlight recurring issues such as login bugs and notification problems.

Common keywords include “job”, “profile”, “network”, and “slow”.

Sentiment analysis shows a generally positive tone, but a notable cluster of negative reviews spike after certain updates.

Users frequently mention UX/UI issues and request better customization features.

📈 Sample Visualizations
Distribution of ratings over time

Word clouds of positive vs. negative reviews

Sentiment breakdown by rating

Most frequent bigrams in complaints

🧠 Conclusion
The analysis reveals a largely satisfied user base, but some persistent problems affect user experience. These insights can help prioritize development focus areas for future updates.

🚀 Future Work
Integrate Google Play scraping for real-time review analysis

Use more advanced NLP techniques (e.g., LDA topic modeling)

Compare review trends across similar professional networking apps

📄 License
This project is open-source and available under the MIT License.
