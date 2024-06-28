# Groupe-5 : Rapport du Projet Final Programmation Avancée en Python et Introduction à R

# Membres du groupe et leur participation :
    AGOSSOU Enagnon Etienne (10%)
    AIZONOU Dèpkatin Espoir Célibert (18%)
    ASSOUROKO Obed Kadoukpè (5%)
    BACHABI Abdel Alim Adébayo (14%)
    BOKO Delys (10%)
    DOSSOU Marolle Orétan Estelle (5%)
    FALETI Jospin (4%)
	  NAHOU Périclès Sèhui Lionel (16%)
	  TALEHOU Roberto Junior Mahugnon (0%)
    TINMITONDE Pernel Djahou (4%)
	  ZOHOUN Amédée Ange-Marie Kpèdido (14%)


# Introduction :
Ce rapport présente les résultats du projet final pour le cours de Programmation Avancée en Python et Introduction à R. Le projet final a pour objectif de permettre aux étudiants d'appliquer les concepts appris en classe de manière pratique. Le projet est composé de trois tâches principales, réalisées en équipes de 7 à 11 étudiants.


## Tâche 1 : Implémentation d'un sous-ensemble de NumPy en Python Pur
 # Objectifs :
  * Créer une classe Array en Python pour répliquer certaines fonctionnalités de base de la bibliothèque NumPy.
  * Supporter la création de tableaux à une ou deux dimensions et les opérations suivantes :
  * Création d'un array à partir d'une liste Python.
  * Opérations élément par élément sur les matrices : Addition, Soustraction, Multiplication, Division.
  * Produit scalaire de deux arrays.
  * Recherche d'éléments.
  * Indexage et Slicing.
  * Support de la fonction len.
  * Support de l'attribut shape.
  * Lever des erreurs explicites pour les opérations non supportées.
  * Annotations de Type, toutes les fonctions doivent inclure des annotations de type pour pratiquer l'utilisation des type hints en Python.
* Fichier de Code : Tout le code sera dans un seul fichier numpy.py.


## Tâche 2 : : Tracé de Graphiques et Analyse de Données
  # Objectifs :
   * Réaliser une analyse de données basique en utilisant à la fois Python et R.
   * Créer deux graphiques :
     * Un histogramme.
     * Un graphique nuage de points (scatter plot).
     * Analyse
     * Pour chaque graphique, une courte analyse expliquant les tendances ou les corrélations possibles doit être fournie.
 * Données :
   * Le jeu de données fourni sera un fichier CSV sur les prix de l'immobilier. Les colonnes utilisées seront :
   * Histogramme : bedrooms.
   * Graphique de dispersion : area (en abscisse) et price (en ordonnée).
   * Bibliothèques Utilisées
   * Python : Matplotlib.
   * R : ggplot2.
   ### Histogramme pour la colonne 'bedrooms' :
   ![Bedroms histogram](/task%202/result/histogram.png "Bedroms histogram")
    L'histogramme des chambres à coucher montre que la majorité des logements ont 3 chambres, suivis par ceux ayant 2 et 4 chambres. Il y a très peu de logements avec 1, 5 ou 6 chambres. Cela suggère que les configurations de 3 chambres sont les plus populaires dans l'échantillon analysé.
   ### Graphique de dispersion pour 'area' et 'price' :
   ![Scatter Plot area-price](/task%202/result/scatter_plot.png "Scatter Plot area-price")
    Le graphique de dispersion "Surface vs Prix" montre une tendance générale à l'augmentation du prix des logements avec l'augmentation de leur surface. Cependant, la dispersion des points indique qu'il existe une variabilité significative des prix pour des surfaces similaires, ce qui suggère que d'autres facteurs influencent également le prix des logements.
* Fichier de Code : Les fichiers de code seront main.py(contenant le hist.py, scatter.py) et main.r(contenant le hist.R et scatter.r)


## Tâche 3 : Petit Programme GUI en Python avec Tkinter
  # Objectifs :
   * Créer une application GUI en utilisant Tkinter en Python.
   * Permettre à l'utilisateur de saisir une description textuelle et de générer une image correspondante à l'aide d'un modèle pré-entraîné de Hugging Face.
 * Fonctionnalités :
  * Une zone de texte pour saisir la description.
  * Un bouton pour générer l'image.
  * Une zone d'affichage pour montrer l'image générée avec la légende.
  * Un spinner (indicateur de chargement) qui apparaît pendant la génération de l'image.
 * Modèle Utilisé :
  * Utilisation du modèle léger tiny-stable-diffusion-pipe de Hugging Face.
  * Possibilité d'utiliser le modèle tiny-sd (il suffit de commenter la ligne de chargement du modèle tiny-stable-diffusion-pipe et de décommenter la ligne de chargement du modèle tiny-sd dans le code du fichier app.py(au début du code)).
* Fichier de Code : Le fichier de code sera app.py.

## Contributions de chaque membre du groupe :
* ZOHOUN Amédée Ange-Marie Kpèdido : Implémentation de la classe Array et des opérations élémentaires (Tâche 1).
* NAHOU Périclès Sèhui Lionel : Création des graphiques en Python (Tâche 2).
* NAHOU Périclès Sèhui Lionel : Analyse des données et création des graphiques en R (Tâche 2).
* BACHABI Abdel Alim Adébayo : Développement de l'interface GUI avec Tkinter (Tâche 3).
* BOKO Delys : Aide à la réalisation de la tâche 3 au niveau de l'interface (Tâche 3).
* AIZONOU Dèpkatin Espoir Célibert : Implémentation du code et Intégration du modèle de Hugging Face en python (Tâche 3).
* AGOSSOU Enagnon Etienne : Documentation et rapport final.
* AIZONOU Dèpkatin Espoir Célibert : Test, correction des erreurs et validation du code.


# Conclusion :
Ce projet final a permis de mettre en pratique les concepts avancés de Python et les bases de R appris durant le cours. Le travail en équipe a été encouragé pour exploiter les compétences de chacun et réaliser les tâches de manière efficace.
