# Wild Code School - Data Engineer - Test Technique

-----

## Partie 1

Télécharger le [dump sql](https://raw.githubusercontent.com/murpi/wilddata/master/test/DataEngineer2022.sql) et l'importer sur une base MySQL.

## Partie 2

Récupérer les données coordonnées géographiques correspondant aux adresses postales de la talbe `address` à l'aide de l'API Nominatim.

## Partie 3

Modifier la table `address` de la base de données pour ajouter les colonnes `latitude` et `longitude`, et y insérer les données correspondantes. Faire un dump de la base de données mise à jour et l'ajouter au repo.

## Partie 4

Faire une requête SQL pour afficher les données suivantes : Nom du client, Prénom, Nombre de locations, Adresses postales, latitude et longitude. Le tout ne doit afficher que le client qui a fait le plus de locations dans la base.

-----

Le fichier sql est le dump de la base de données incluant les nouvelles colonnes de la table addresse.

La requête SQL de la partie 4 se trouve en fin de notebook, et son résultat affiché sous forme de dataframe.
