# BeepBeep-StravaWorker

The other repo of data-service is [https://github.com/giacomodeliberali/BeepBeep-DataService](https://github.com/giacomodeliberali/BeepBeep-DataService)

## Development

To start the celery worker type:
```
source key.sh
celery worker -A datapump.datapump -B
```

## Test

To run pytest launch `pytest --cov-config .coveragerc --cov datapump`