# End-to-end-ML-Project-with-MLflow


### Project work flow

1. update config.yaml
2. update schema.yaml
3. update params.yaml
4. update the entity
5. update the configuration manager in src config
6. update the components
7. update the pipeline
8. update the main.py
9. update the app.py


# How to run?
### STEPS:

Clone the repository

```bash
https://github.com/MannShrestha/End-to-end-ML-Project-with-MLflow
```
### STEP 01- Create a conda environment after opening the repository

```bash
conda create -n mlproject python=3.8 -y
```

```bash
conda activate mlproject
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

[Documentation](https://mlflow.org/docs/latest/getting-started/index.html)


##### cmd
- mlflow ui

### dagshub
[dagshub](https://dagshub.com/)

MLFLOW_TRACKING_URI=https://dagshub.com/MannShrestha/End-to-end-ML-Project-with-MLflow.mlflow
MLFLOW_TRACKING_USERNAME=MannShrestha
MLFLOW_TRACKING_PASSWORD=41f801ddadfd672ed6133c408cdff17b1a85368b
python script.py

Run this to export as env variables:

```bash

export MLFLOW_TRACKING_URI=https://dagshub.com/MannShrestha/End-to-end-ML-Project-with-MLflow.mlflow

export MLFLOW_TRACKING_USERNAME=MannShrestha 

export MLFLOW_TRACKING_PASSWORD=41f801ddadfd672ed6133c408cdff17b1a85368b

```

