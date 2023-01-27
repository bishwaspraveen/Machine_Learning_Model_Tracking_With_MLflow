## Machine Learning Model Tracking with MLflow for Random Forest Based Classification Problem 

### Step 1 : Creating numerous versions of the classifier and tracking their logged hyperparameters, metrices, pickle file of the model and other artifacts.
![mlflow1](https://user-images.githubusercontent.com/79660080/215022139-6a0f8d4c-57dd-4b4d-abf0-4a320707aa6f.PNG)

### Step 2 : Visualization of the artifacts of the best version of classification the model produced in research environment through MLflow UI.
![mlflow2](https://user-images.githubusercontent.com/79660080/215022227-1865f678-65f2-4933-b4ad-1c80f3578746.PNG)

### Step 3 : Visualization of the validation code generated for both Spark and Pandas framework through MLflow UI.
![mlflow3](https://user-images.githubusercontent.com/79660080/215022282-a5ab8c37-d848-4915-8b1f-28743da201d4.PNG)

### Step 4 : Different stages of the model available for serving (staging, production and archieved) after using sqlite as a backend source for artifact storage.
![mlflow4](https://user-images.githubusercontent.com/79660080/215022312-b8f7e61a-7a9b-4368-a1e8-cf6e7865b177.PNG)

### Important commands necessary to run MLflow on Anaconda3.
#### 1. Command to use file system to fecth data and project it onto MLFlow UI
`mlflow ui --backend-store-uri file:///C:\Users\bishw\OneDrive\Desktop\Source_codes\Machine_Learning_Model_Life-Cycle_With_MLflow\Machine_Learning_Model_Tracking\mlruns`
#### 2. Command to use sqlite db connection to fetch data and project it onto MLFlow UI
`mlflow server --backend-store-uri sqlite:///C:\Users\bishw\OneDrive\Desktop\Source_codes\Machine_Learning_Model_Life-Cycle_With_MLflow\Machine_Learning_Model_Tracking\mlflow.db --default-artifact-root file:///C:\Users\bishw\OneDrive\Desktop\Source_codes\Machine_Learning_Model_Life-Cycle_With_MLflow\Machine_Learning_Model_Tracking\artifacts`
