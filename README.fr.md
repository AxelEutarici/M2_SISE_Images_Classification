# Classification d'Images avec Pytorch et Torchvision

Also available in English : <br>
[![en](https://img.shields.io/badge/lang-english-red.svg)](https://github.com/AxelEutarici/M2_SISE_Images_Classification/blob/main/README.fr.md)

## Sommaire

 - [Etat de l'art](#Etat-de-l-art)
 - [Fichiers GitHub](#Github-files)

## Etat de l'art 

Le travail fourni est une continuation des travaux faits par Cao and Choe dans leur papier de 2018 "Deep Learning Based Damage Detection on Post-Hurricane Satellite Imagery" . Au lieu d'utiliser keras (and tensorflow) nous avons utilisé pytorch et torchvision pour créer nos propres CNN et implémenter des modèles pré entrainés. <br>
Vous pouvez trouver les jeux de données de l'article de base ici : https://github.com/qcao10/DamageDetection.


## Fichiers GitHub
Sur le GitHub vous trouvez 4 qui divisent notre travail en différentes parties.
`/1_Transform_keras_model_to_pytorch` contient le code pour transformer le meilleur modèle de Cao et Choe de keras à PyTorch<br>
`/2_Original_code_in_pytorch` contient le code pour recréer leur code en PyTorch pour croiser les résultats et se familiariser avec le package <br>
`/3_Finetuning_pretrained_models` contient le code qui charge les modeles pré entrainés (VGGNet, ResNet, AlexNet) et prend en input des nouvelles données. Nous avons également modifié certaines couches<br>
`/4_Extract_features_DL_for_ML` contient le code pour extraire les features des modèles pré entrainés et passer les données featurisées dans un modèle de ML<br>

