# Chest-Diasease-Classification-from-Chest-CT-Scan-Image

# Workflows 

1. update config.file
2. update params.yaml
3. update the entity
4. update the configuration manager in src config
5. update the componenets
6. update the pipeline
7. update the main.py
8. update the dvc.yaml

## mlflow dagsup connection uri
'''bash
MLFLOW_TRACKING_URI=https://dagshub.com/deepthedeata/mlflow_experiment_demo.mlflow \
MLFLOW_TRACKING_USERNAME=deepthedeata \
MLFLOW_TRACKING_PASSWORD=6248687d47c26e1b9bedb597daea837ccb42340e \
python script.py
'''
## Run from terminal
'''bash
export MLFLOW_TRACKING_URI=https://dagshub.com/deepthedeata/mlflow_experiment_demo.mlflow
export MLFLOW_TRACKING_USERNAME=deepthedeata
export MLFLOW_TRACKING_PASSWORD=6248687d47c26e1b9bedb597daea837ccb42340e