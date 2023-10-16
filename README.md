# Projet - Lien entre éruptions volcaniques, crashs d'avions et tremblements de terre

## Objectifs

L'objectif de ce projet est de vérifier si les éruptions volcaniques ont un lien avec les crashs d'avions et/ou les tremblements de terre.

## Données

Les données utilisées pour ce projet ont été trouvées sur le site web Kaggle. Il s'agit de trois bases de données :

* **Earthquake** : données sur les tremblements de terre
* **Airplane Crash** : données sur les crashs d'avions
* **Eruption** : données sur les éruptions volcaniques

## Traitement des données

Les données ont été traitées dans le logiciel Pentaho. Les traitements effectués ont été les suivants :

* **Earthquake** : traitement de la date, récupération de l'année et création d'une colonne avec cette donnée, traitement et récupération des pays manquants
* **Airplane Crash** : récupération de l'année et création d'une colonne avec cette donnée, suppression des espaces se trouvant devant les éléments de différentes colonnes, récupération des pays qui se trouvent après une virgule dans la colonne "Location"
* **Eruption** et **Volcanoes on earth** : traitement des bases de données afin de pouvoir les fusionner, création de la base de données "All volcanoes"

## Modèle Pentaho

Le modèle Pentaho est composé de cinq tables de dimensions et d'une table de fait.

* **Table de fait** : "PROJECT_FAIT"
* **Tables de dimensions** :
    * "PROJECT_VOLCANOES"
    * "PROJECT_OPERATOR"
    * "PROJECT_PLANE"
    * "PROJECT_CRASH"
    * "PROJECT_EARTHQUAKE"

## Conclusion

Les résultats du projet seront présentés dans des rapports individuels par les membres de l'équipe.
