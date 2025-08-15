Dataset **Ant Detection** can be downloaded in [Supervisely format](https://developer.supervisely.com/api-references/supervisely-annotation-json-format):

 [Download](https://assets.supervisely.com/remote/eyJsaW5rIjogInMzOi8vc3VwZXJ2aXNlbHktZGF0YXNldHMvMzUwOF9BbnQgRGV0ZWN0aW9uL2FudC1kZXRlY3Rpb24tRGF0YXNldE5pbmphLnRhciIsICJzaWciOiAiUjNBaWlkazlsN2R1V091UU5EQ3JnZDdJemVDQ0svb3lmOUd2c0xaZXIxdz0ifQ==?response-content-disposition=attachment%3B%20filename%3D%22ant-detection-DatasetNinja.tar%22)

As an alternative, it can be downloaded with *dataset-tools* package:
``` bash
pip install --upgrade dataset-tools
```

... using following python code:
``` python
import dataset_tools as dtools

dtools.download(dataset='Ant Detection', dst_dir='~/dataset-ninja/')
```
Make sure not to overlook the [python code example](https://developer.supervisely.com/getting-started/python-sdk-tutorials/iterate-over-a-local-project) available on the Supervisely Developer Portal. It will give you a clear idea of how to effortlessly work with the downloaded dataset.

The data in original format can be [downloaded here](https://www.kaggle.com/datasets/elizamoscovskaya/ant-2-keypoints-dataset/download?datasetVersionNumber=1).