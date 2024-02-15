Dataset **Ant Detection** can be downloaded in [Supervisely format](https://developer.supervisely.com/api-references/supervisely-annotation-json-format):

 [Download](https://assets.supervisely.com/supervisely-supervisely-assets-public/teams_storage/0/m/sM/TgQ3VLnTy3wFmkZAMmy1lfBrQyGyfobcJlSz8Zjf762SzpegjQ3YF4gkQjq5qqb3ZDtiFpiO1oPqzbciOV1qS8FygB58aieauV0usWDybOtMKV7twGk1Vt66tyZb.tar)

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