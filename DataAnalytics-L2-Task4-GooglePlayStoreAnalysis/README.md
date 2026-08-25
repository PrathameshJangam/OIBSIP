# Google Play Store Analysis 📱📊

## Project Overview

This project performs an exploratory data analysis (EDA) of the Google Play Store ecosystem using app information and user reviews.

The analysis focuses on app categories, ratings, installations, app size, pricing, estimated revenue, and user sentiment. The goal is to identify useful patterns and insights that can help developers make informed decisions when planning to launch a new application.

---

## Objectives

The main objectives of this project are:

- Clean and preprocess real-world Google Play Store data
- Analyze the distribution of apps across different categories
- Identify highly saturated app categories
- Analyze app ratings and average ratings by category
- Study the relationship between app size and installations
- Compare free and paid applications
- Analyze pricing patterns of paid apps
- Estimate potential revenue by category
- Perform sentiment analysis on user reviews
- Compare positive, negative, and neutral sentiment across categories
- Create visualizations to communicate key findings

---

## Dataset

The project uses the **Google Play Store Apps** dataset and the **Google Play Store User Reviews** dataset.

### Dataset Source

[Kaggle - Google Play Store Apps](https://www.kaggle.com/datasets/lava18/google-play-store-apps)

### Files Used

- `googleplaystore.csv` — Contains information about Google Play Store applications.
- `googleplaystore_user_reviews.csv` — Contains user reviews and sentiment-related information.

### Important Features

Some of the main columns used in the analysis include:

- `App`
- `Category`
- `Rating`
- `Reviews`
- `Size`
- `Installs`
- `Type`
- `Price`
- `Content Rating`
- `Genres`
- `Last Updated`
- `Translated_Review`
- `Sentiment`

---

## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- TextBlob
- Plotly

---

## Project Workflow

### 1. Data Loading

The app and user review datasets are loaded separately using Pandas.

### 2. Data Cleaning

The datasets are cleaned by:

- Removing duplicate records
- Handling missing values
- Converting `Installs` from text to numeric values
- Removing `$` from the `Price` column
- Converting `Price` to numeric format
- Converting app sizes into MB
- Handling invalid category records
- Preparing review data for sentiment analysis

### 3. Category Analysis

The number of applications in each category is analyzed to identify categories with a high concentration of apps.

### 4. Ratings Analysis

The project examines:

- Distribution of app ratings
- Average rating by category

### 5. Size and Installation Analysis

A scatter plot is used to examine the relationship between application size and number of installations.

Correlation analysis is also performed to measure the strength of the relationship.

### 6. Pricing Analysis

The analysis compares:

- Free vs paid applications
- Price distribution of paid applications
- Estimated revenue by category

Estimated revenue is calculated using:

`Estimated Revenue = App Price × Number of Installs`

This is only a simplified estimate and should not be considered actual revenue.

### 7. Sentiment Analysis

User reviews are analyzed using TextBlob to classify reviews into:

- Positive
- Negative
- Neutral

### 8. Sentiment by Category

Review data is combined with app category information to determine which categories have relatively more positive or negative user sentiment.

### 9. Interactive Visualization

Plotly is used to create interactive visualizations that allow users to explore the data more easily.

---

## Key Insights

The analysis provides insights into:

- Competition and saturation across app categories
- Rating patterns across different categories
- Relationship between app size and installations
- Dominance of free applications
- Pricing patterns among paid applications
- Potential revenue opportunities across categories
- User satisfaction and sentiment across app categories

---

## Conclusion

The analysis suggests that developers should carefully evaluate category competition before launching a new application. A free or freemium strategy may help attract a larger user base, while user ratings and reviews can provide valuable feedback for continuously improving the application.

Overall, combining market competition, ratings, installations, pricing, and user sentiment can help developers make more informed app-launch decisions.

---

