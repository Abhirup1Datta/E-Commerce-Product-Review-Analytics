## Predicting_Credit_Card_Approvals  
So this project was part of my independent learning initiative where I wanted to apply NLP and machine learning to real-world data. I chose product reviews for Apple AirPods Pro because it’s a globally used product with a lot of user feedback available online. I scraped around 20,000 reviews from Walmart to analyze what customers actually feel about the product.
### Methodology:
Used Pandas to load the dataset and get a peek at the underlying data in the dataframe. Performed data pre-processing and exploration using Python, handled missing values and dealt with extreme outliers using relevant methods. Utilised matplotlib and seaborn libraries for detailed visualisation.  
Imported the cleaned data into MySQL and wrote several queries to gain insights on the data. 
Using scikit-learn library in Python performed data scaling and applied various machine learning models to train the data and predict whether the application will be approved or rejected. Analysed and compared the performance of each model using suitable metrics and plot. 


S – Situation
“So this project was part of my independent learning initiative where I wanted to apply NLP and machine learning to real-world data. I chose product reviews for Apple AirPods Pro because it’s a globally used product with a lot of user feedback available online. I scraped around 20,000 reviews from Walmart to analyze what customers actually feel about the product.”

🎯 T – Task
“The main goal was to understand the overall sentiment of the product — whether users are generally positive or negative — and then to go a level deeper and identify key themes or topics that drive those sentiments.
So essentially, I wanted to answer ‘What do people like or dislike about AirPods?’”

⚙️ A – Action
“I broke the project into three main parts:
1. Data Collection & Cleaning:
I used Python for web scraping and libraries like BeautifulSoup and pandas for structuring the data. Then I cleaned the text — removing stopwords, special characters, and tokenizing sentences using NLTK’s Punkt tokenizer.
2. Sentiment Analysis using DistilBERT:
Instead of using simple models like Naive Bayes, I used a Transformer-based model — DistilBERT — because it understands context better. This helped me classify each review as positive or negative with high accuracy.
(You can mention: “I didn’t use lemmatization here because BERT-based models handle context and word forms internally.”)
3. Topic Modeling (LDA):
After classifying reviews, I separated positive and negative ones and performed Topic Modeling using Latent Dirichlet Allocation (LDA) to uncover key discussion areas.
•	First, I converted text into TF-IDF vectors using TfidfVectorizer (to give importance to meaningful words).
•	Then, I ran LDA to identify word clusters representing major themes.
•	I experimented with different vocabulary sizes (100, 250, 500, 1000) to get stable and interpretable topics.
4. Model Comparison for Classification:
I also trained traditional ML models — Logistic Regression, Random Forest, and XGBoost — on TF-IDF features to predict sentiment for future reviews.
This gave a good performance baseline to compare against the deep learning model.”

📈 R – Result
“The insights were quite actionable:
•	From positive reviews, topics like sound quality, comfort, and premium gifting came up most often.
•	From negative reviews, major themes were delivery issues, battery backup, and charging problems.
So apart from just knowing that 85% of reviews were positive, the analysis told why people felt positive or negative.
This kind of analysis can help product and marketing teams identify improvement areas and highlight what customers love most in their campaigns.”
