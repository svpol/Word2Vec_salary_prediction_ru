# Overview

This project is salary prediction by the vacancy text data: name, description, key skills and experience.
Prediction was calculated for full-time and full-day vacaincies only.

Text vectorization is made via Word2Vec and then two linear models are applied: linear regression and Lasso.

# Data

The data are presented in `vacancies.csv`. Text data are in Russian.

Data structure:

- `name` - vacancy name.
- `experience` - years of working experience.
- `schedule` - work schedule, e.g.: by schift, full day or other types.
- `employment` - full-time, part-time or other types.
- `description` - vacancy description.
- `key_skills` - key required skills.
- `salary` - salary, our target variable.

# Results

Prediction results are available at the ipynb file as a dataframe and also in the directory `pred_results` as csv files.