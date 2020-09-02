# examen_nlp
Rattrapage Examen 2
Bonjour Mikael,

Tu trouveras dans le zip les fichiers suivants :

helpers.py              Ton fichier helpers pour les dendogrammes
news                    Répertoire avec les Data
news_clean.csv          L'ensemble des datas que j'ai nettoyé dans un script a part (cela prend plusieurs heures)
README.txt
TP_A58-Rattrapge.html   Mon Notebook au format html
TP_A58-Rattrapge.ipynb  Mon notebook

Tu trouveras dans le notebook pourquoi j'ai choisi ce jeu de données non préparé et le lien pour trouver les données à la source (kaggle).

Le notebook éxécute les algos du cours sur un sous ensemble de données (800 article).
Le vrai jeu complet est décomposé en trois fichiers de plus de 100000 articles.

J'ai pris un échantillon car :
1) cela prenait trop de temps d'exécuté les algo sur l'ensemble
2) Avec Sklearn j'ai été frappé des problèmes de mémoire

La version avec 800 articles ne pose aucun problème.

En complément mais ne figure pas dans le zip, j'ai essayé d'exécuter l'algo CURE (donc pour les grands volumes) en partant de plusieurs sources.
Mais rien n'a été probant.
Exemple : pylcusting https://github.com/annoviko/pyclustering/tree/master/pyclustering
Mais le chargement des données est un vrai problème et la doc rare.
Je réessayerai lorsque j'aurai un peu plus de temps.

Merci !

