# OUEDRAOGO P Mahomed
# Data Processing - Data Viz / mini_projet_data_analysis
Le but de cet exercice est d'extraire un sous-ensemble de données à partir d'une base de données plus grande.<br>
Supposons que vous ayez besoin de réaliser une application qui prend en entrée, des noms de lieux du Burkina Faso, avec des informations telles que la latitude/longitude.<br>
Pour ce faire, nous décidons d'extraire ces informations à partir du server de référencement géoname (http://www.geonames.org/). <br>Vous allez procéder de la façon suivante :
<br>1 - Exporter la base de données qui recense les informations sur le Burkina Faso (https://download.geonames.org/export/dump/).
<br>Pour ce faire, reférez-vous au Readme, décrit à la fin de la page pour identifier le code iso correspondant au Burkina Faso
<br>2 - Télécharger le fichier zip correspondant
<br>3 - Appliquer les opérations de prétraitement et filtres nécessaires à ce fichier, pour:
<br> 3.1 Ne garder que les colonnes correspondantes Identifiants, Noms de lieux, latitudes, longitudes
<br> 3.2 Renommez les avec les noms suivants : 'ID', 'location_name', 'lat', 'long'
<br> 3.3 Sauvegarder ces données dans un fichier CSV, nommez-le burkina_location.csv
<br> 4 - Opérations sur le fichier CSV burkina_location.csv.
<br> 4.1 Extraire les données contenant le nom 'gounghin', enregistrez-le sous le fichier gounghin.csv
<br> 4.2 extraire la sous-partie de la base de données (fichier burkina_location.csv), dont les noms les premières lettres des noms de lieux sont compris entre 'A' et 'P' (ordre alphabétique)
<br> 4.3 Identifiez respectivement, la latitude, la longitude minimale et les noms de lieux correspondants
<br> 4.4 Quels sont les lieux dont les coordonnées sont comprises entre (lat >= 11 et lon <= 0.5)
<br>5 - Sorties Excel
<br>À partir des extractions de l'étape 4 :
<br> 5.1 Créer un fichier Excel et nommer le : mini_projet
<br> 5.2 Créer une feuille dans ce fichier, du nom gounghin et enregistrer les données contenant le nom 'gounghin' obtenues dans 4.1
<br> 5.3 Créer une second feuille dans ce même fichier, du nom A_to_P et enregistrer les données de 4.2
