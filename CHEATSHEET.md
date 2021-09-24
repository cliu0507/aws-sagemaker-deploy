
```
BENTO_BUNDLE=$(bentoml get BodyParser:latest --print-location -q)

```

```
python deploy.py $BENTO_BUNDLE my-first-sagemaker-deployment sagemaker_config.json
```
