#this is my end to end project

#first initilize the git "# dimondpriceprediction" >> README.md git init git add README.md git commit -m "first commit" git branch -M main git remote add origin https://github.com/vinay250/dimondpriceprediction.git git push -u origin main

#you can .gitignore choose python The purpose of gitignore files is to ensure that certain files not tracked by Git remain untracked. To stop tracking a file that is currently tracked, use git rm --cached to remove the file from the index. gitignore it can do igonre files what we written .gitigonre

CHOOSE THE LICENSE MIT Permissions Commercial use Modification Distribution Private use

how run setup file python setup.py install #another way you can mention -e - in your requirements file and can run pip install -r requirements.txt


## MLflow

[Documentation](https://mlflow.org/docs/latest/index.html)


##### local cmd
- mlflow ui

### dagshub
[dagshub](https://dagshub.com/)

MLFLOW_TRACKING_URI=a/fsdsmendtoend.mlflow \
MLFLOW_TRACKING_USERNAME=\
MLFLOW_TRACKING_PASSWORD= \
python script.py

Run this to export as env variables:

```bash

export MLFLOW_TRACKING_URI=

export MLFLOW_TRACKING_USERNAME=

export MLFLOW_TRACKING_PASSWORD=

```


### DVC cmd
- dvc init
- dvc repro
- dvc dag

