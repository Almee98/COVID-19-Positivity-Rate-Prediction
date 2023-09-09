# COVID-19-Positivity-Rate-Prediction
This is an AI/ML project, for predicting the positivity rate of COVID-19 cases in a university.

## Project Title: Predicting COVID-19 Positivity Rates in Universities

#### Project Overview:

- This project is aimed at predicting COVID-19 positivity rates in university settings, leveraging various data sources and employing data science techniques.
- I explore the impact of several factors, including location, population size, testing rates, and environmental conditions like weather.
- Additionally, I investigate the influence of university social media activity, particularly the presence of mask-wearing behaviors in posted images, on positivity rates.

### Key Components and Methodology:

### Data Collection and Preprocessing:

- Gathered comprehensive datasets containing university-specific COVID-19 statistics, including location, population, testing, and positivity rates.
- Integrated weather data to assess potential correlations between environmental conditions and infection rates.
- Introduced "Twitter_Data" dataset with university Twitter handles, bios, posts, images, followers, and more.

### Image Classification for Face Masks:

- Trained an image classification model to detect individuals wearing face masks in university-related social media posts.
- Linked mask-wearing results with the original dataset to evaluate its impact on positivity rates relative to other universities.

### Exploratory Data Analysis and Visualization:

- Conducted extensive data exploration and visualization using tools like Python's 'matplotlib' and Tableau.
- Gained valuable insights into the dataset, aiding in the selection of appropriate machine learning models.

### Time Series Conversion:

- Converted the dataset into a time series format to account for temporal dependencies in the data.

### Machine Learning Models:

- Implemented multiple regression models, including Random Forest Regressor, Decision Tree, and XG Boost.
- Achieved the highest predictive accuracy with XG Boost, yielding an impressive 98% accuracy rate.

### Contributions and Impact:

This project contributes to understanding the factors influencing COVID-19 positivity rates in universities, offering actionable insights for educational institutions and health authorities. By considering variables such as location, population, testing rates, weather conditions, and social media image analysis, we provide a comprehensive approach to predicting and managing COVID-19 outbreaks.

### Future Directions:

Future work may involve refining the image classification model, exploring additional data sources, and collaborating with universities to implement targeted interventions based on predictive results. Furthermore, ongoing monitoring and model refinement are crucial to adapt to changing circumstances.
