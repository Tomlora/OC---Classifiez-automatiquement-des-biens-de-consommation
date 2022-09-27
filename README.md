## Projet OC (P6) : Classifiez automatiquement des biens de consommation

Le but du projet est d'aider une entreprise qui souhaite lancer une marketplace e-commerce.

Afin d'y parvenir, elle souhaite automatiser l'attribution de la catégorie de chaque article.

Notre rôle est de réaliser une étude de faisabilité d'un moteur de classification d'articles, en se basant sur une image et une description.

### Contraintes du projet :

#### Classification texte :
- Deux approches de type bag-of-words (__comptage simple de mots__ et __Tf-idf__)
- Trois approches de type sentence embedding (__Word2Vec__ / __BERT__ / __USE__)

### Classification image
- Un algorithme de type __SIFT__ / __ORB__ / __SURF__
- Un algorithme de type __CNN Transfert Learning__

### Compétences évaluées :

- Prétraiter des données textes pour obtenir un jeu de données exploitable
- Prétraiter des données image pour obtenir un jeu de données exploitable
- Représenter graphiquement des données à grandes dimensions
- Mettre en oeuvre des techniques de réduction de dimension

### Ressources (non-exhaustif) :
- Pandas
- Numpy
- __Sklearn.cluster__ (KMeans)
- __Sklearn.feature_extraction__ (CountVectorizer, TfidfVectorizer)
- __NTLK__ (tokenize, stem, lemmatizer, stopwords)
- __Tensorflow__ (BERT, USE)
- __Keras__ (Preprocessing / Layers / Metrics / Models / Applications (VGG16, VGG19, Resnetv50, InceptionV3 pour du transfert learning))
- pyLDAvis (algorithme pour identifier des thèmes et les mots clés de chaque thème dans un corpus de texte)
- PCA / TSNE
- __OpenCV__ (pour SIFT)
- Torch
- __Pillow__ (Faire une visualisation des images du T-SNE)
