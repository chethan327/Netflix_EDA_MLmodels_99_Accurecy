# Netflix Data Analysis Project

## Overview

This project analyzes a dataset of movies and TV shows available on Netflix to uncover patterns and insights into content distribution, popularity, and trends. The analysis explores various attributes such as content type, duration, genres, country of origin, and release years. Additionally, predictive models are implemented to forecast content success.

---

## Objectives

1. Identify trends in content types (Movies vs. TV Shows).
2. Analyze country-wise contributions and genre popularity.
3. Explore trends in content duration over time.
4. Predict the likelihood of content success based on key attributes.

---

## Dataset

**Source**: Netflix’s publicly available data archives.  

### Features:

- **`show_id`**: Unique identifier for each title.
- **`type`**: Content type (“Movie” or “TV Show”).
- **`title`**: Name of the content.
- **`director`**: Director of the content.
- **`cast`**: Cast members.
- **`country`**: Country of origin.
- **`date_added`**: Date when the content was added to Netflix.
- **`release_year`**: Year of release.
- **`rating`**: Audience rating (e.g., PG, TV-MA).
- **`duration`**: Duration in minutes (for Movies) or seasons (for TV Shows).
- **`listed_in`**: Genre(s) or category.
- **`description`**: Synopsis of the content.

---

## Tools and Libraries

- **Programming Language**: Python  
- **Libraries Used**:
  - Pandas: For data manipulation.
  - Matplotlib & Seaborn: For data visualization.
  - Missingno: For missing value visualization.
  - Scikit-learn: For building machine learning models.

---

## Exploratory Data Analysis (EDA)

### Key Insights:

1. **Content Type Trends**:
   - Movies outnumber TV Shows on Netflix.
   - TV Shows often span fewer than three seasons.

2. **Country Contributions**:
   - The United States dominates Netflix's library.
   - Significant contributions also come from countries like India, the UK, and Canada.

3. **Genre Popularity**:
   - Action, Comedy, and Drama are the most popular genres.
   - Documentaries and International content offer niche appeal.

4. **Content Duration**:
   - Movies typically range from 90 to 120 minutes.
   - TV Shows are designed for binge-worthy, shorter seasons.

---

## Machine Learning Models

### Models Implemented:
1. **Random Forest Classifier**:
   - **Accuracy**: 99%

2. **DecisionTreeClassifier**:
   - **Accuracy**: 98%

3. **Support Vector Classification**:
   - **Accuracy**: 92%

4. **Logistic Regression**:
   - **Accuracy**: 88%




### Feature Engineering:

- Extracted numerical values from `duration`.
- One-hot encoded categorical variables such as `type`, `rating`, and `listed_in`.

### Model Evaluation Metrics:

- Accuracy


---


## How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/netflix-data-analysis.git
