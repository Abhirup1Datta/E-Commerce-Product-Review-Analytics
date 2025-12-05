## Predicting_Credit_Card_Approvals  
So this project was part of my independent learning initiative where I wanted to apply NLP and machine learning to real-world data. I chose product reviews for Apple AirPods Pro because it’s a globally used product with a lot of user feedback available online. I scraped around 20,000 reviews from Walmart to analyze what customers actually feel about the product.
### Methodology:
• The main goal was to understand the overall sentiment of the product — whether users are generally positive or negative — and then to go a level deeper and identify key themes or topics that drive those sentiments

• Used Distilbert to classify the reviews as positive or negative  

• After classifying reviews, I separated positive and negative ones and performed Topic Modeling using Latent Dirichlet Allocation (LDA) to uncover key discussion areas  

• Finally trained ML models on TF-IDF features to predict sentiment for future reviews

