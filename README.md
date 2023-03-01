# Object_Detection-Segmentation

La détection et la segmentation d'objets est l'une des applications populaires de l'apprentissage en profondeur (Deep Learning). 
Elle est largement appliquée dans de nombreux domaines. Commençons par considérer un exemple réel. La plupart d'entre vous auraient utilisé Google Photos dans votre 
téléphone, qui classe automatiquement vos photos en groupes en fonction des objets qu'elles contiennent sous l'option « Choses ».  Vous pouvez observer que l'application 
est capable d'identifier des objets à partir d'images et de les utiliser pour les classer dans des catégories plus larges. Ceci est un exemple qui implique la détection 
d'objets.

Dans ce mini projet, j'ai effectué une détection d'objets à l'aide d'un modèle récent et robuste appelé **Detectron2** sous GoogleColab.

Facebook AI Research (**FAIR**) a mis au point cette bibliothèque avancée, qui a donné des résultats étonnants sur les problèmes de détection et de segmentation d'objets. 
Detectron2 est basé sur le benchmark Mask R-CNN. Son implémentation est en PyTorch. Il a été mis au point pour soutenir la mise en œuvre et l'évaluation rapides de 
nouvelles recherches sur la computer vision. Il inclut des implémentations pour les algorithmes de détection et de segmentation d'objets suivants : 
- Mask R-CNN
- RetinaNet
- Faster R-CNN
- RPN
- TensorMask
- PointRend
- DensePose
- and more...

Pour ce projet, l'algorithme  Faster R-CNN peut être appliqué pour la détection alors que Mask R-CNN, qui est une extension de Faster R-CNN, est appliqué pour la 
segmentation.

https://github.com/facebookresearch/detectron2
