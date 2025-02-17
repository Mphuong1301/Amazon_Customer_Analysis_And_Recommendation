# Foody_Sentiment_Review_Prediction
## I. Business Objective
Foody.vn is a platform that collaborates with restaurants and eateries to sell food online.
Here, users can browse reviews, read feedback, and place food orders.
Based on customer reviews, the key issue is how restaurants and eateries can better understand their customers, gain insights into their feedback, and improve their products and services accordingly.

## II. Process
1. Understand the problem
2. Import the necessary libraries and learn how to use them
3. Load the data (the dataset for this project is provided)
4. Perform basic EDA (Exploratory Data Analysis) using Pandas Profiling Report
5. Preprocess the data: cleaning, feature engineering, selecting relevant features, etc.
6. Visualize the data
7. Choose an appropriate algorithm for the classification task
8. Build the model
9. Evaluate the model
10. Report the results

### Step 1: Business Understanding
Based on the description above, we define the problem as follows:

- Build a system that utilizes historical customer reviews. The data is collected from customer comments and ratings on Foody.vn.
- Objective: Develop a predictive model that allows restaurants to quickly understand customer feedback about their products or services (positive, negative, or neutral). This insight helps restaurants assess their business performance, understand customer opinions, and improve their services and products.
- After collecting the data, we have 33,632 samples with three key attributes:
      - ID user
      - ID shop
      - Review date
      - Review text
      - User name
      - Rating

- We can now focus on solving the problem of Sentiment Analysis in the Cuisine Domain using Supervised Learning – Classification algorithms, such as:
      - LightGBM
      - Decision tree
      - Logistic Regression
      - Support Vector Machine
      - MLP

- Labeling and Grouping Strategy:
      - Rate < 5 → "negative"
      - Rate >= 5 → "positive"

### Step 3: Data Preparation
Key tasks for preprocessing, especially for Vietnamese text data:

- Check and relabel comments
- Data Cleaning
- Use Scattertext for text visualization
- Generate WordCloud plots
- Apply TF-IDF & Word2Vec embeddings for feature extraction

### Step 4 & 5: Modeling & Evaluation / Analysis & Reporting
- Build classification models to predict customer sentiment, including:
- Using evaluate model performance using: Accuracy, Precision, Recall, F1-score, etc.

## III. Conclusion
Summarize the results and insights to help restaurants better understand customer sentiments and enhance their services.







