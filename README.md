## Machine Learning Model Tracking with MLflow for Random Forest Based Classification Problem 

### Step 1 : Creating numerous versions of the classifier and tracking their logged hyperparameters, metrices, pickle file of the model and other artifacts.

### Step 2 : Visualization of the artifacts of the best version of classification the model produced in research environment through MLflow UI.

### Step 3 : Visualization of the validation code generated for both Spark and Pandas framework through MLflow UI.

### Step 4 : Different stages of the model available for serving (staging, production and archieved) after using sqlite as a backend source for artifact storage.

### Important commands necessary to run MLflow on Anaconda3.
#### 1. Command to use file system to fecth data and project it onto MLFlow UI
`mlflow ui --backend-store-uri file:///C:\Users\bishw\OneDrive\Desktop\Source_codes\Machine_Learning_Model_Life-Cycle_With_MLflow\Machine_Learning_Model_Tracking\mlruns`
#### 2. Command to use sqlite db connection to fetch data and project it onto MLFlow UI
`mlflow server --backend-store-uri sqlite:///C:\Users\bishw\OneDrive\Desktop\Source_codes\Machine_Learning_Model_Life-Cycle_With_MLflow\Machine_Learning_Model_Tracking\mlflow.db --default-artifact-root file:///C:\Users\bishw\OneDrive\Desktop\Source_codes\Machine_Learning_Model_Life-Cycle_With_MLflow\Machine_Learning_Model_Tracking\artifacts`
