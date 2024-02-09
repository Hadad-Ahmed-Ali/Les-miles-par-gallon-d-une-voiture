# Les-miles-par-gallon-d-une-voiture
Prédire les miles par gallon d'une voiture selon un certains variables.

Les données sont les spécifications téchniques des voitures publiées à l'origine en 1983 pour
l'American Statistical Association Data Expo. Dans ce projet, nous allons essayer de prédire les miles par
gallon d'une voiture en utilisant la régression linéaire multiple. Les miles par gallon (mpg) d'une voiture
mesurent jusqu'où une voiture peut aller avec un gallon de carburant. Partout au monde où l'utilisation
de voitures est très courante, les consommateurs tiennent parfois compte de l'efficacité et de
l'économie de carburant de la voiture qu'ils souhaitent acheter avant de l'acheter. Tout le monde veut
acheter une voiture qui peut voyager loin et consommer moins de carburant. Dans ce cadre, supposez
que nous travaillons pour une entreprise qui vend des voitures et on nous a chargé en tant que
scientifiques des données d'analyser ces données et de produire un bon modèle qui peut
prédire/estimer les miles par gallon d'une voiture avec une erreur minimale comptent tenu des autres
caractéristiques de la voiture. Le fichier est divisé en trois sous fichiers qu'on nous propose de
reconstituer et ensuite de mettre en place un modèle de prédiction que nous utiliserons pour prédire
les « mpg » du fichier auto-mpg-a-predire. Pour cela, nous aurons besoin de faire quelques analyses et
représentations graphiques.

# Présentation du projet
Vous trouverez ci-joint ma présentation de ce travaille rédiger sous l’éditeur LaTeX, on nous a demandé de 
faire le minimum de rédaction qui va se focaliser sur les miles par gallon. Donc tout est minimiser. 
Tout au long du travail, on a implémenté plusieurs algorithmes ( dans SAS) pour la création du meilleur
fichier de prédiction, toute fois le code SAS ci-joint pressente les implémentations qui nous ramene au meilleur modèle.
Les différents données sont à votre dispositions ( ci-joints) vous pouvez donc prendre le code SAS ci-joint et l’exécuter 
sous SAS pour bien visualiser le travail.

# PLan
       1 Modélisation du fichier prédictif
          1.1 Introduction . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .
          1.2 Données à analyser . . . . . . . . . . . . . . . . . . . . . . . . . .
          1.3 Analyse descriptive des données . . . . . . . . . . . . . . . . . .
             1.3.1 Statistique descriptive . . . . . . . . . . . . . . . . . . . .
          1.4 Création du fichier prédictif . . . . . . . . . . . . . . . . . . . . .
             1.4.1 Rajout des variables continue . . . . . . . . . . . . . . . .
             1.4.2 Elimination des valeurs atypiques . . . . . . . . . . . . . .
             1.4.3 Corrélation entre les variable . . . . . . . . . . . . . . . .
             1.4.4 Variables significative . . . . . . . . . . . . . . . . . . . .
             1.4.5 Élimination des eléments influant négativement le modèle
          1.5 Explication du nouveau modèle prédictif . . . . . . . . . . . . . .
             1.5.1 Analyse du modèle . . . . . . . . . . . . . . . . . . . . . .
             1.5.2 Analyse descriptive du fichier prédictif selon le mpg . . .
             1.5.3 Analyse histogramme de la variable mpg . . . . . . . . . .
       2 Prédiction d’un mpg d'une nouvelle voiture 
          2.1 Construire le fichier à prédire . . . . . . . .
          2.2 prédiction . . . . . . . . . . . . . . . . . . .
          2.3 Conclusion générale . . . . . . . .
          
# Conclusion
Sur l’analyse descriptive du fichier prédictif, on a vu qu’en générale les voiture ont en moyenne
22.8943182 Km/mg ceci nous déconseille d’acheter une voiture d’un mpg moins de 22.8943182
km/mg et on a vu encore que c’est en Asie qu’il y’a l’mpg le plus grand et une moyenne d’mpg
significatif égale à 31.28km/mg, ceci dit que vaut mieux acheter une voiture Asiatique de plus qui à
un mpg supérieure ou égale à 31.28km/mg . On peut facilement constater ces résultat au niveau de
la table à prédire où les deux voiture Asiatique ont un mpg significatif que les autres voitures. Ainsi,
selon ce fichier qu’on a prédit, on voit que mieux est l’mpg pour une voiture de moins de poids,
mieux est l’mpg pour une voiture d’une petite cylindre, mieux est l’mpg pour une voiture de
moins de puissance.
