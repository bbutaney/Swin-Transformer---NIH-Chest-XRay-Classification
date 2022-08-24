# Swin-Transformer---NIH-Chest-XRay-Classification
The two uploaded notebooks were run in Google Colab to train/test a Swin Transformer using PyTorch, NumPy, and other python packages. The model is used for image classification on the ~100k image NIH Chest X-ray Dataset.

This is a multiclass, multilabel problem, with images being classified as showing one or more of 15 diseases.

The files used in this notebook can be downloaded here: https://www.kaggle.com/datasets/nih-chest-xrays/data. A description of the data can be found here: https://www.nih.gov/news-events/news-releases/nih-clinical-center-provides-one-largest-publicly-available-chest-x-ray-datasets-scientific-community.

Achieved accuracy of ~80% trained from scratch. SoTA is ~82%
