# Kidney-Disease-Classification-MLflow-DVC


https://github.com/jonghwan3/Kidney-Disease-Classification-Deep-Learning-Project/assets/97586094/a8881aca-aae8-4fc8-a662-c46c1aed27d1


### This project is based on a [machine learning tutorial](https://www.youtube.com/watch?v=86BKEv0X2xU). The GitHub repo follows the steps from that guide.


## Workflows

1. Update config.yaml
2. Update secrets.yaml [Optional]
3. Update params.yaml
4. Update the entity
5. Update the configuration manager in src config
6. Update the components
7. Update the pipeline 
8. Update the main.py
9. Update the dvc.yaml
10. app.py

# How to run?
### STEPS:

Clone the repository

```bash
https://github.com/krishnaik06/Kidney-Disease-Classification-Deep-Learning-Project
```
### STEP 01- Create a conda environment after opening the repository

```bash
conda create -n cnncls python=3.8 -y
```

```bash
conda activate cnncls
```


### STEP 02- install the requirements
```bash
pip install -r requirements.txt
```

```bash
# Finally run the following command
python app.py
```

Now,
```bash
open up you local host and port
```






## MLflow

- [Documentation](https://mlflow.org/docs/latest/index.html)

- [MLflow tutorial](https://youtu.be/qdcHHrsXA48?si=bD5vDS60akNphkem)

##### cmd
- mlflow ui

### dagshub
[dagshub](https://dagshub.com/)

MLFLOW_TRACKING_URI=https://dagshub.com/entbappy/Kidney-Disease-Classification-MLflow-DVC.mlflow \
MLFLOW_TRACKING_USERNAME=entbappy \
MLFLOW_TRACKING_PASSWORD=6824692c47a369aa6f9eac5b10041d5c8edbcef0 \
python script.py

Run this to export as env variables:

```bash

export MLFLOW_TRACKING_URI=https://dagshub.com/entbappy/Kidney-Disease-Classification-MLflow-DVC.mlflow

export MLFLOW_TRACKING_USERNAME=entbappy 

export MLFLOW_TRACKING_PASSWORD=6824692c47a369aa6f9eac5b10041d5c8edbcef0

```


### DVC cmd

1. dvc init
2. dvc repro
3. dvc dag


## About MLflow & DVC

MLflow

 - Its Production Grade
 - Trace all of your expriements
 - Logging & taging your model


DVC 

 - Its very lite weight for POC only
 - lite weight expriements tracker
 - It can perform Orchestration (Creating Pipelines)




##### cmd
- mlflow ui

### dagshub
[dagshub](https://dagshub.com/)

MLFLOW_TRACKING_URI=https://dagshub.com/jonghwan3/Kidney-Disease-Classification-Deep-Learning-Project.mlflow \
MLFLOW_TRACKING_USERNAME=jonghwan3 \
MLFLOW_TRACKING_PASSWORD=fc19633fab5984c88c31ef74ebc17ebc5feddccc \
python script.py

Run this to export as env variables:

```bash

export MLFLOW_TRACKING_URI=https://dagshub.com/jonghwan3/Kidney-Disease-Classification-Deep-Learning-Project.mlflow

export MLFLOW_TRACKING_USERNAME=jonghwan3

export MLFLOW_TRACKING_PASSWORD=fc19633fab5984c88c31ef74ebc17ebc5feddccc

```

### DVC cmd

1. dvc init
2. dvc repro
3. dvc dag

## About MLflow & DVC

MLflow

 - Its Production Grade
 - Trace all of your expriements
 - Logging & taging your model


DVC 

 - Its very lite weight for POC only
 - lite weight expriements tracker
 - It can perform Orchestration (Creating Pipelines)
