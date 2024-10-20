## Learning the Code - Patterns in Learning & Career Outcomes

### Team 8 - Members & Contributions
- **Jie Luo** (jiemluo@umich.edu): Unsupervised Learning (Objective 3), Data cleaning and preprocessing, Feature Engineering
- **Kittnipatt Buranasiri** (kburana@umich.edu): Supervised Learning (Objective 2), EDA, Ethical Considerations
- **Lydia Schrandt** (schrandt@umich.edu): Supervised Learning (Objective 1), EDA, Report Final Edit

Besides the list above, all other aspects will be collaborative efforts among the team.

### Project Overview
This project analyzes the **2021 New Coder Survey** dataset from freeCodeCamp to understand the motivations, learning methods, and career outcomes of new coders. By utilizing both supervised and unsupervised machine learning approaches, we aim to uncover factors influencing job placement, salary expectations, and learning preferences. Key challenges involve preprocessing natural language data and understanding the performance differences between models implemented using Scikit-learn.

### Project Objectives
#### Supervised Learning
1. **Objective 1**: Multi-class prediction of job status (high-income, low-income, or no job) to gain insights into economic positioning.
2. **Objective 2**: Multi-class prediction of job satisfaction (high or low expectations) for both employed and unemployed individuals.

#### Unsupervised Learning
1. **Objective 3**: Identify common patterns and clusters among survey respondents. These insights will help create a recommendation engine that suggests personalized learning paths for new coders.

### Data
The dataset is sourced from freeCodeCamp's [2021 New Coder Survey](https://github.com/freeCodeCamp/2021-new-coder-survey) and is stored in this repository under the `2021-new-coder-survey-raw` folder.

#### Key Files:
- **1.Data_Exploration.ipynb**: Data exploration and preprocessing, including cleaning, handling missing values, and feature engineering. Outputs the final processed dataset (`df_final.csv`).
- **df_final.csv**: The cleaned and preprocessed dataset, ready for modeling.
- **2.Supervised_Learning_Objective_1.ipynb**: Multi-class prediction of job status (Objective 1).
- **3.Supervised_Learning_Objective_2.ipynb**: Multi-class prediction of job expectations (Objective 2).
- **4.Unsupervised_Learning.ipynb**: Clustering analysis to identify patterns among survey respondents (Objective 3).

### How to Run the Code
1. Clone this repository to your local machine.
2. Start by running the `1.Data_Exploration.ipynb` notebook to preprocess the raw dataset.
3. Move on to the relevant notebooks (`2_Supervised_Learning_Objective_1.ipynb`, `3_Supervised_Learning_Objective_2.ipynb`, and `4_Unsupervised_Learning.ipynb`) for each part of the analysis.

### License
This project is licensed under the MIT License.
