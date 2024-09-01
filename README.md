
**Optimization Sustainability: Machine Learning Insights for Enhanced Electricity Production from Solar and Wind Energy**  

Independent project report submitted for the degree of Master of Science in Data Science  
University of the West of England (UWE) Bristol

Author: Masoud Rayat Zadeh  
Supervisor: Dr. Neil Phillips

August 2024

## Project Overview
This project examines how machine learning techniques can be applied to optimize electricity production from solar and wind energy sources in France. Focusing on the years 2020 to 2023, the study aims to enhance the sustainability and efficiency of renewable energy generation. Through the analysis of historical data, the development of predictive models, and the use of optimization algorithms, this research seeks to provide actionable insights that can improve the performance and reliability of renewable energy systems.

## Technologies Used

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Google Colab](https://img.shields.io/badge/Google%20Colab-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=white)
![VSCode](https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-2C5AB1?style=for-the-badge&logo=matplotlib&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=for-the-badge&logo=scipy&logoColor=white)
![Pyomo](https://img.shields.io/badge/Pyomo-3776AB?style=for-the-badge&logo=python&logoColor=white)

## Features

- **Predictive Models:** Develops and evaluates machine learning models to predict solar and wind energy production in France based on environmental and operational data from 2020 to 2023.
- **Optimization Algorithms:** Implements optimization algorithms designed to maximize electricity output while considering sustainability constraints specific to the French energy market.
- **Data Analysis & Visualization:** Includes tools for analyzing and visualizing trends in renewable energy data within France, offering insights into key factors influencing energy production over the past three years.
- **Performance Evaluation:** Assessed model accuracy using metrics such as MAE, RMSE, and R² to ensure the reliability and precision of the predictions.
- **Comparative Studies:** Conducts comparative studies of different machine learning models to determine the most effective approaches for energy prediction and optimization in the French context.


### Project Structure

- **assets/**: Contains deliverables and results of the project.
  - **deliverables/**:
    - `Video_Presentation.mp4`: A video presentation summarizing the project.
  - **result/**:
    - `Table-Performance Results of All Classifiers.jpg`: A table summarizing the performance results of all classifiers used in the project.
    - `Technical design and approach.jpg`: An image detailing the technical design and approach of the project.

- **data/**: Contains the dataset used for analysis and modeling.
  - `courbes-de-production-mensuelles-eolien-solaire-complement-de-remuneration.csv`

- **notebooks/**: Jupyter notebooks containing the exploratory data analysis (EDA) and machine learning models.
  - **EDA/**:
    - `EDA_Renewable_Energy.ipynb`: Notebook for exploratory data analysis of renewable energy data.
  - **ML_Algorithms/**:
    - `Solar_Wind_Energy_Prediction_BaggingRegressor.ipynb`: Implementation of the Bagging Regressor algorithm for predicting solar and wind energy production.
    - `Solar_Wind_Energy_Prediction_KNN.ipynb`: Implementation of the K-Nearest Neighbors (KNN) algorithm for predicting solar and wind energy production.
    - `Solar_Wind_Energy_Prediction_LightGBM.ipynb`: Implementation of the LightGBM algorithm for predicting solar and wind energy production.
    - `Solar_Wind_Energy_Prediction_RSM.ipynb`: Implementation of the Regularized Smoothing Method (RSM) for predicting solar and wind energy production.
    - `Solar_Wind_Energy_Prediction_RandomForest.ipynb`: Implementation of the Random Forest algorithm for predicting solar and wind energy production.
    - `Solar_Wind_Energy_Prediction_XGBoost.ipynb`: Implementation of the XGBoost algorithm for predicting solar and wind energy production.

- **README.md**: Documentation for the project, providing an overview, structure, and usage instructions.

### Conclusion

Ultimately, the Random Forest model demonstrated superior performance, achieving a 98% accuracy rate. This result underscores the significant potential of the Random Forest model for precise prediction of solar and wind energy production, making it a highly effective tool in optimizing renewable energy outputs.


