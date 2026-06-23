# Predicting UFC Fight Finishes using Machine Learning
**AAI-510 Final Project**

## Project Overview
This project aims to predict whether a UFC fight will end in a finish (KO/TKO/Submission) or go to a decision using machine learning. By forecasting fight outcomes, this solution provides valuable insights for sports betting markets, fan engagement platforms, and targeted advertising. This project is presented to an executive decision-making body to demonstrate the business viability of deploying this ML solution into production.

## Team Members
* Christian Ian Lopez
* Ramon Diehl Verdugo

## Deliverables
* **Jupyter Notebook**: Located in `notebooks/`. Contains the technical methodology, EDA, modeling, evaluation, and an LLM concept for fight-preview summaries.
* **Business Presentation**: Located in `presentations/`. Targeted to the non-technical executive committee.
* **Video Presentation**:

 https://drive.google.com/file/d/14CzEvb0YFl5kueAL9KZciAkMup48NSYj/view?usp=share_link

## Methodology (CRISP-DM)

### 1. Business Understanding
* **Objective**: Predict UFC fight outcomes (Finish vs. Decision) using pre-fight statistics.
* **Impact**: Enhances predictive modeling for sports analytics, driving engagement and optimizing odds-making.

### 2. Data Understanding
* **Dataset**: Kaggle UFC Dataset.
* **Key Steps**: Created the target variable (Finish vs. Decision) and removed data leakage columns (e.g., post-fight statistics that models wouldn't know before a fight).

### 3. Data Preparation & Feature Engineering
* Handled missing values, outliers, and engineered features for the modeling pipelines.
* *Note: Two separate data cleaning and modeling pipelines are being developed and compared by the engineering team to ensure the highest accuracy.*

### 4. Modeling
* **Models Tested**: Testing various algorithms (including ensemble methods) to compare performance.
* **Advanced Features**: Includes feature importance analysis and an LLM concept for generating dynamic fight-preview summaries.

### 5. Evaluation
* Models are evaluated against business objectives. The final model will be selected based on its ability to minimize false predictions while maximizing actionable insights.

### 6. Deployment Strategy
* **Architecture**: Batch vs. Real-time inference
* **Considerations**: Evaluating latency, cost, and hosting requirements for a production rollout.
