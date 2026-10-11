# Google Play Store Analysis

## Project Overview

This project analyzes the Google Play Store dataset to understand app categories, ratings, installs, reviews, pricing, and other factors that influence app popularity.

The dataset was cleaned and analyzed using Python to identify useful patterns and insights.

## Dataset

The dataset contains information about Google Play Store applications, including:

* App
* Category
* Rating
* Reviews
* Size
* Installs
* Type
* Price
* Content Rating
* Genres
* Last Updated
* Current Version
* Android Version

## Data Cleaning

The following cleaning steps were performed:

1. Removed duplicate records.
2. Handled missing ratings using the median rating.
3. Filled missing categorical values.
4. Converted reviews into numeric format.
5. Removed one invalid record with a missing review value.
6. Converted install values into numeric format.
7. Converted prices into numeric format.
8. Converted app size into MB.
9. Performed final data quality checks.

After cleaning, the dataset contained **10,357 records and 14 columns**.

## Analysis Performed

The following analyses were performed:

1. App count by category.
2. Average rating by category.
3. Total installs by category.
4. Free vs Paid app comparison.
5. Average rating of Free vs Paid apps.
6. Top 10 apps by installs.
7. Reviews vs Installs analysis.
8. Correlation between Reviews and Installs.
9. Correlation heatmap.
10. Paid app price analysis.
11. Category performance summary.

## Key Insights

* **FAMILY** has the highest number of apps.
* **GAME** has the highest total number of installs.
* **EVENTS** has the highest average rating.
* Free apps are much more common than paid apps.
* Paid apps have a slightly higher average rating than free apps.
* Reviews and installs have a moderate positive correlation of approximately **0.635**.
* Several popular apps have approximately **1 billion installs**.
* A small number of paid apps have unusually high prices close to **$400**.

## Recommendations

* Developers can explore high-demand categories such as GAME, COMMUNICATION, SOCIAL, and PRODUCTIVITY.
* A free or freemium model can help reach a larger user base.
* Developers should focus on app quality and user experience.
* Encouraging genuine user engagement and reviews can support app visibility.
* Paid apps should provide clear value and use reasonable pricing.

## Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

## Project Files

* `Google_Play_Store_Analysis.ipynb` — Jupyter Notebook containing the analysis.
* `cleaned_googleplaystore.csv` — Cleaned dataset.
* `googleplaystore.csv` — Original dataset.
* `googleplaystore.csv.zip` — Original downloaded dataset archive.

## Conclusion

The analysis provides useful insights into the Google Play Store ecosystem. App popularity is influenced by category, installs, reviews, ratings, and pricing. The results can help developers understand popular categories, user engagement, and potential strategies for improving app reach and performance.
