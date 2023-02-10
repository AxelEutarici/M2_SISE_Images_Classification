# Classification d'Images avec Pytorch et Torchvision

Disponible également en français : <br>
[![fr](https://img.shields.io/badge/lang-english-red.svg)](https://github.com/AxelEutarici/M2_SISE_Images_Classification/blob/main/README.fr.md)

## Summary

 - [Etat de l'art](#Etat-de-l-art)
 - [Fichiers GitHub](#Github-files)

## Etat de l'art 

Le travail fourni est une continuation des travaux faits par Cao and Choe dans leur papier de 2018 "Deep Learning Based Damage Detection on Post-Hurricane Satellite Imagery" . Au lieu d'utiliser keras  Instead of using keras (and tensorflow) we used pytorch and torchvision to create our our CNN and implement pre trained models. <br>
You can find their work and the datasets used here : https://github.com/qcao10/DamageDetection.


## GitHub Files
You'll find 4 notebooks in our GitHub separating our work in different parts  

`/1_Transform_keras_model_to_pytorch` contains the code to transform the best model found by Cao & Choe from keras to pytorch <br>
`/2_Original_code_in_pytorch` contains the code to redo their entire code but in pytoch to cross results ans become familiar with the package<br>
`/3_Finetuning_pretrained_models` contains the code that uses pretrained model (VGGNet, ResNet, AlexNet) with new data, modifying them also with new layers<br>
`/4_Extract_features_DL_for_ML` contains the code to extract features from pretrained model and passing the featurized data through a ML model<br>

