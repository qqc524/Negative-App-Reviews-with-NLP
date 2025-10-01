This project analyzes negative reviews from the Google Play Store to understand the main problems users face with a mobile app. 
The goal is to find common issues and group them into categories so app developers can prioritize fixes and improve user experience.


### Dataset

The project uses a dataset of Google Play reviews with the following columns:
| Column    | Description                    |
| --------- | ------------------------------ |
| `content` | Text of the review             |
| `score`   | Rating given by the user (1–5) |


### Tools & Libraries

Python
* Pandas - for data manipulation
* NLTK - for text preprocessing
* scikit-learn - for TF-IDF vectorization and K-means clustering
* Matplotlib - for visualization


This analysis helps identify the most common problems in the app, making it easier to plan improvements.
