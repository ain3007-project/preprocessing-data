
Data Preprocessing Notebooks that we used

1. [Panda Dataset Processor](panda-dataset-processor.ipynb): This notebook is used to process the Panda dataset. And convert tiff images to resized png images. And upload them to the our HuggingFace Account.
2. [Train Dataset Processor](preprocess-project-data.ipynb): This notebook downloads the raw dataset files one by one and processes them, and uploads the results to the our Huggingface account.
3. [Test Dataset Processor](preprocess-project-test-data.ipynb): This notebook downloads the raw dataset files one by one and processes them, and uploads the results to the our Huggingface account.


Note: These notebooks have been run on Kaggle. Because of the need for high internet download and upload speeds. And also ease of access to the Panda dataset.


These notebooks are using our own custom python package [project-utils](https://github.com/ain3007-project/project-utils). This project is not on PYPI servers. Because of the narrow scope of the project. But you can install it from the github repository.

```bash
pip install git+hhttps://github.com/ain3007-project/project-utils.git
```
