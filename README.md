# This is my end to end project 

# first initializing the git

```
git init
```
```
git add abc.txt
git add .
```
```
git commit -m "this is my first commit"
```
```
bash file_name.sh
```

```
python setup.py install    
```

# another way we can mention -e . in our requirement file and we can run 

```
pip install -r requirements.txt
```

```
COPY . ./    
copy from current directory to working directory
```

```
in .yaml we write the configuration in key:value form 
ECR- Elastic Container Registry 
```

## MLflow

[Documentation](https://mlflow.org/docs/latest/index.html)


##### local cmd
- mlflow ui

### dagshub
[dagshub](https://dagshub.com/)

MLFLOW_TRACKING_URI=https://dagshub.com/surajpanigrahi296/FSDSendtoend.mlflow \
MLFLOW_TRACKING_USERNAME=surajpanigrahi296 \
MLFLOW_TRACKING_PASSWORD=58da4d0d0052c4651825aa12247e91ffcaeef929 \
python script.py

Run this to export as env variables:

```bash

export MLFLOW_TRACKING_URI=https://dagshub.com/surajpanigrahi296/FSDSendtoend.mlflow

export MLFLOW_TRACKING_USERNAME=surajpanigrahi296
export MLFLOW_TRACKING_PASSWORD=58da4d0d0052c4651825aa12247e91ffcaeef929

```


### DVC cmd
- dvc init
- dvc repro
- dvc dag
