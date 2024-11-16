## End to End Data science project  

import dagshub
dagshub.init(repo_owner='saurabhwalde2', repo_name='ml-project', mlflow=True)

import mlflow
with mlflow.start_run():
  mlflow.log_param('parameter name', 'value')
  mlflow.log_metric('metric name', 1)


MLFLOW_TRACKING_URI= https://dagshub.com/saurabhwalde2/ml-project.mlflow \
MLFLOW_TRACKING_USERNAME=saurabhwalde2 \

MLFLOW_TRACKING_PASSWORD=22973bad5ea2ced3f368b49f4b3d2ef6d919979f  \

python script.py