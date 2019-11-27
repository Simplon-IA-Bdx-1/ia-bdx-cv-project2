# Brief suite Computer Vision (journée 2)

Note : nous reprendrons la suite du brief 1 la semaine prochaine une fois davantage familiarisés avec les réseaux de neurones artificiels.

* Retour sur les ateliers de lundi (réduction de dimensionnalité et classification avec SVM et XGBoost) :
    - Petit sondage pour vérifier la complétion des projets
    - Confrontation des résultats (clustering 2D pour l'atelier 1 et accuracy pour atelier 2, matrice de confusion ?)
    - Explication de 3 codes par leurs auteurs et questions/réponses
    - Identification des points de blocage les plus courants
* Intermède : créer son compte Azure gratuit

Pour mieux comprendre tSNe : [ici](https://distill.pub/2016/misread-tsne/)
Pour mieux comprendre UMAP (pas juste de la visualisation) : [ici](https://pypi.org/project/umap-learn/) 
Pour la différence entre PCA et ICA : [ici](http://compneurosci.com/wiki/images/4/42/Intro_to_PCA_and_ICA.pdf)

** Preprocessing des images : un petit tour par OpenCV

Travail en binôme
* Installer la librairie OpenCV pour Python
* Choisir une image quelconque
* La charger
* Essayer les fonctions décrites [ici](https://www.analyticsvidhya.com/blog/2019/03/opencv-functions-computer-vision-python/)

** Tracking d'objet avec OpenCV GoTurn

* Choisir une courte vidéo
* Appliquer GoTurn

** Data Augmentation

* Choisir une image quelconque
* Générer des variantes avec les fonctions de Data Augmentation de Keras

Note : le Data Augmentation n'est pas une technique réservée aux problèmes de CV