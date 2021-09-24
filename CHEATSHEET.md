# Cheatsheet

## Set up AWS credential
Use Cloudops klams to setup AWS credential. All deployment will use the default profile under ~/.aws/credentials

## How to Deploy to AWS Sagemaker
```
BENTO_BUNDLE=$(bentoml get BodyParser:latest --print-location -q)

```
```
python deploy.py $BENTO_BUNDLE my-first-sagemaker-deployment sagemaker_config.json
```

## How to Delete Existing Deployment on AWS Sagemaker
```
python delete.py $BENTO_BUNDLE my-first-sagemaker-deployment sagemaker_config.json
```
