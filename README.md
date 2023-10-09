# Kidney-Disease-Classification-MLflow-DVC

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

```bash
C:/Users/pichapati.vijay/AppData/Local/anaconda3/Scripts/activate
```

### STEPS:

Clone the repository
```bash
https://github.com/vkreddy317/Kidney-Disease-Classification-MLflow-DVC.git
```

### STEP 01- Create a conda environment after opening the repository
```bash
conda create -n kidney python=3.8 -y
```


```bash
conda activate kidney
```

### STEP 02- install the requirements

```bash
pip install -r requirements.txt
```

### dagshub
[dagshub](https://dagshub.com/)

MLFLOW_TRACKING_URI=https://dagshub.com/vkreddy317/Kidney-Disease-Classification-MLflow-DVC.mlflow \
MLFLOW_TRACKING_USERNAME=vkreddy317 \
MLFLOW_TRACKING_PASSWORD=aea730237e91c1097f0ab21d04495809812ad696 \
python script.py

Run this to export as env variables:
```bash
set MLFLOW_TRACKING_URI=https://dagshub.com/vkreddy317/Kidney-Disease-Classification-MLflow-DVC.mlflow 

set MLFLOW_TRACKING_USERNAME=vkreddy317

set MLFLOW_TRACKING_PASSWORD=aea730237e91c1097f0ab21d04495809812ad696 

```

### ECR url
304697532705.dkr.ecr.eu-north-1.amazonaws.com/kidney