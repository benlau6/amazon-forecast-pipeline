# amazon-forecast-pipeline
Predicting best billing hour daily. It is achieved by applying billing success rate hourly forecast, and then select the best time within same time period (a day).
Most of the sensitive data are removed.

## Project Architecture
![Alt text](Puretech_Project_Framework.png?raw=true)

## Model deployment by AWS Glue Workflow for cheapest cost
![Alt text](GlueJobWorkFlow.png?raw=true)

## FYI 
Explanatory data analysis - EDA.ipynb \
Evaluation of model performance - Evaluation.ipynb \
Clean up all existing and recreation - CleanUp.ipynb \
Check for forecast result - ForecastResult.ipynb\
*(no need in model deployment)

## Model deployment 
Create model - ModelCreation.ipynb \
Update model - ModelUpdate.ipynb

## Workflow
First time - ModelCreation.ipynb \
Periodically update - ModelUpdate.ipynb \
Looking for details - EDA.ipynb / Evaluation.ipynb / ForecastResult.ipynb


