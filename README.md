Welcome to the Demo Code Repository for MLFlow
==============================================
To install the mlflow conda environment in the project folder, inside your terminal navigate to the project folder and then run the conda command:

conda env create -f mlflow_env.yaml
This command will install environment with name mlflow and then you can activate the environment by using command:

conda activate mlflow

Things to take care - MLFlow in Jupyter environment:
===========================================================
Run the logging code in the same cell in the notebook.
Do not do Partial logging or logging parameters before the model training.
Running the server before hand before running the logging code inside your notebook.
Use get_params() method to obtain list of all parameters instead of writing manually