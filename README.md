# ComputerVisionIASD
__Abstract__
##
Dans ce projet, nous nous concentrons sur la classification d'images en utilisant des techniques de deep learning sur le jeu de données STL-10. Les images du jeu de données ont une taille de 96x96x3, ce qui signifie qu'elles sont en couleur (RGB) et ont une résolution de 96 pixels de largeur et de hauteur.

Nous commencerons par explorer des approches classiques en utilisant des réseaux de neurones à convolution (CNN). Ces réseaux sont bien adaptés à la classification d'images en raison de leur capacité à extraire des caractéristiques à différentes échelles spatiales. Nous évaluerons une architectures de CNN sur STL-10. Cette architecture Nous servira de base pour la suite.

Ensuite, nous améliorerons notre modèle de base en ajoutant une couche d'attention. Cette couche permettra au modèle de se concentrer sur les parties les plus informatives des images et de mieux discriminer les différentes classes. Nous évaluerons l'impact de l'ajout de cette couche d'attention sur les performances de classification.

De plus, nous introduirons un mécanisme de résidu dans notre modèle. Les connexions résiduelles permettent d'améliorer la propagation du signal et de faciliter l'apprentissage profond en évitant les problèmes de disparition du gradient. Nous évaluerons l'efficacité de l'ajout de ces connexions résiduelles sur les performances de notre modèle.

Nous aborderons la question de l'augmentation des données. L'augmentation des données est une technique couramment utilisée pour augmenter la taille du jeu de données d'entraînement en appliquant des transformations telles que la rotation, le redimensionnement, l'ajout de perspective, etc. Nous évaluerons l'impact de l'augmentation des données sur les performances de notre modèle.

Ensuite, nous explorerons une approche de self-supervised learning en utilisant un autoencodeur. Nous utiliserons l'autoencodeur pour extraire des caractéristiques pertinentes à partir des images et les utiliserons ensuite pour la phase de classification. Cette approche permet d'apprendre des représentations utiles sans avoir besoin d'étiquettes supervisées.

Enfin nous utiliserons un modèle pré entrainé pour effectuer l'extraction de features. Nous avons choisi d'utiliser le modèle CLIP. CLIP (Contrastive Language-Image Pretraining) est un modèle développé par OpenAI qui permet la compréhension croisée des images et du texte. Il combine un transformateur visuel (ViT) et un transformateur de langage pour apprendre des représentations conjointes des images et du texte. CLIP peut être utilisé pour diverses tâches, notamment la classification d'images, l'apprentissage sans étiquette et la recherche texte-image. Suite à l'extraction des features, nous réaliserons un classification à l'aide d'algorithmes de machine learning classique (RandomForest et LogisticRegression).

En résumé, ce projet vise à explorer différentes approches de deep learning pour la classification d'images sur le jeu de données STL-10. Nous évaluerons l'efficacité des architectures de CNN classiques, ainsi que l'impact de l'ajout de couches d'attention et de connexions résiduelles. Nous étudierons également l'importance de l'augmentation des données et testerons une approche de self-supervised learning avec un autoencodeur pour extraire des caractéristiques pertinentes. Une approche utilisant un modèle pré entrainé pour l'extraction des features sera également explorée. Les résultats obtenus nous permettront de mieux comprendre les meilleures pratiques en matière de classification d'images en deep learning.
