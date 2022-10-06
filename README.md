# Employee Turnover prediction

<p>Employee turnover prediction is a project done as a solution for the kaggle competition "Employee Attrition", from PRASHANT PATEL, available on: <https://www.kaggle.com/datasets/patelprashant/employee-attrition?datasetId=12204&sortBy=voteCount>, and published as a poster on the 8º Simtec Event on Unicamp.</p>

## <ins>Goals</ins>

<p>This project was done for academic purposes and aims to predict the employee turnover. The independent variables used were the level of responsability of the employee, how many hours it works per week, if it works overtime and if it is single.</p>

## <ins>Objectives of the project</ins>

- Understand the Dataset and cleanup unnecessary features (if required).
- Compare different algorithms for the same problem.
- Show technical scores: R2, RMSE, etc.

## <ins>Strategic plan of action</ins>

1. Frame the problem.
2. Get the Data.
3. Data Cleaning (Removal of unnecessary features).
4. Explore the Data.
5. Prepare the Data (Preprocessing and feature selection).
6. Train the ML Algorithm (Linear Regression).
7. Evaluate using technical scores.

## <ins>Experiment protocol</ins>

- The dataset was divided into training and testing parts in the ratio 80:20, that means 80% of the database will be used for training and 20% for testing.
- Preprocessing was required because the dataset contains redundant information such as "EmployeeCount", "Over18" and "StandardHours". There was not any null data on the dataset.
- Results were evaluated using the coefficient of determination and the mean error.

## <ins>Technologies</ins>

- Python.
<p>Made on Google Colab.</p>

## <ins>How to use </ins>

- Download the "BeerConsumptionPrediction.ipynb" file on this repository and import it on google colab.
- Download the Dataset at "https://www.kaggle.com/dongeorge/beer-consumption-sao-paulo" and import it on the "sample_data" folder on google colab.
- Run it.

## <ins>Heatmap of the correlation between variables and the confusion matrix</ins>

![Correlações-Limpo (1)](https://user-images.githubusercontent.com/67275098/194402529-cf977a29-5723-451d-9c73-c345cca293db.png)

![download (1)](https://user-images.githubusercontent.com/67275098/194402301-00fbcc3e-b9f7-4a38-a8e3-8d5faf1b8104.png)

## <ins>Credits</ins>

<p> The ideia to work on this project and it's structure was shared by the teacher of Artificial Intelligence at Facamp, Carlos Caetano.</p>
<p> Other team members:</p>

- Fábio Seiji Sakai Iwashima.
