# Image-Classification-CatVsNon-cat-app

The whole project is here: https://drive.google.com/drive/u/0/folders/1n6OTCihXoN9pAbT-B9J1y1VVABHkXXSq

TF Lite real time app on Android for Image Classification CatVsNon-cat.

Dataset description:

Train - 20 970
Test - 10 334
The original datasets from which I made my own:
1) https://storage.googleapis.com/openimages/web/index.html
2) https://www.kaggle.com/c/dogs-vs-cats
3) https://cocodataset.org/
4) https://www.kaggle.com/huanghanchina/pascal-voc-2012?
Properties:
1) There are photos of cats from different angles, from different distances, as well as with other animals
2) Close-up photos of cats prevail, since dogs Vs cats are the most voluminous
3) All pictures, except cats, from pascal-voc are taken as non-cat
4) Rarely, but there are erroneous labels in coco-dataset and open-image. For example, a photo of a dog, but it is labeled as a cat


What can be improved:

1) Carry out the parametr-tunning with Keras Tuner and compare the results not only on the validation set, but also on the test set
2) Use data augmentation
3) Try Transfer learning
