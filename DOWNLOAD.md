Dataset **Bangladeshi License Plate Recognition: Character Recognition** can be downloaded in [Supervisely format](https://developer.supervisely.com/api-references/supervisely-annotation-json-format):

 [Download](https://assets.supervisely.com/remote/eyJsaW5rIjogImZzOi8vYXNzZXRzLzI4NDZfQmFuZ2xhZGVzaGkgTGljZW5zZSBQbGF0ZSBSZWNvZ25pdGlvbjogQ2hhcmFjdGVyIFJlY29nbml0aW9uL2JhbmdsYWRlc2hpLWxpY2Vuc2UtcGxhdGUtcmVjb2duaXRpb246LWNoYXJhY3Rlci1yZWNvZ25pdGlvbi1EYXRhc2V0TmluamEudGFyIiwgInNpZyI6ICI5cUxINm5MWWNUbWRkQWE4TnhXVzhjSWdiUjg0WnBpUHBMYVBLNmNqQlRrPSJ9)

As an alternative, it can be downloaded with *dataset-tools* package:
``` bash
pip install --upgrade dataset-tools
```

... using following python code:
``` python
import dataset_tools as dtools

dtools.download(dataset='Bangladeshi License Plate Recognition: Character Recognition', dst_dir='~/dataset-ninja/')
```
Make sure not to overlook the [python code example](https://developer.supervisely.com/getting-started/python-sdk-tutorials/iterate-over-a-local-project) available on the Supervisely Developer Portal. It will give you a clear idea of how to effortlessly work with the downloaded dataset.

The data in original format can be [downloaded here](https://www.kaggle.com/datasets/syednahinhossain/bangladeshi-license-plate-recognition-dataset/).