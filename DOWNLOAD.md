Dataset **BLPR: Character Recognition** can be downloaded in [Supervisely format](https://developer.supervisely.com/api-references/supervisely-annotation-json-format):

 [Download](https://assets.supervisely.com/supervisely-supervisely-assets-public/teams_storage/8/B/Ew/HbllFT2SBdE5732WbVDdOSYmhokiIbXnVF6clRJm01NSFc32DfYvD0w8Gsketi2VZAc76ZysLMNT1wEHkR4jcqQfiqix8U0BbIqHBLq4wephEePGMwqsuWvgotAu.tar)

As an alternative, it can be downloaded with *dataset-tools* package:
``` bash
pip install --upgrade dataset-tools
```

... using following python code:
``` python
import dataset_tools as dtools

dtools.download(dataset='BLPR: Character Recognition', dst_dir='~/dataset-ninja/')
```
Make sure not to overlook the [python code example](https://developer.supervisely.com/getting-started/python-sdk-tutorials/iterate-over-a-local-project) available on the Supervisely Developer Portal. It will give you a clear idea of how to effortlessly work with the downloaded dataset.

