
# La data dans tous ses états


#### La fabrique des données 


###### de leur acquisition à leur usage...

---

## Quelques définitions de départ

## Processus: de la donnée à l'information

---

## Définitions

----

### DATA


`data` de datum 

*littéralement ce qui est donné* = "données"

> en réalité ce qui est collecté/capturé/reçu

----

* Unité minimale d'information stockable et transmissible. &#11035;≠ &#128161; & &#128712; 

* Ce terme ne caractérise rien du tout (surtout donnée brute): une donnée en elle même/isolée ne veut rien dire.
* Elle ne peut être saisie et comprise que dans un ensemble (cf. dataset).
* On ne peut la caractériser que par ses ***métadonnées*** ( la notice de ce à quoi ca correspond) ou par la matérialité de son support de transmission et de stockage (le ***format**)

> C'est pour ça qu'on y ajoute des choses: opendata, dataset, données personnelles, données de santé

----

#### Types de données selon le format

- linked data
- données tabulaires
- données en arbres
- données en graphes 
- séries temporelles
- ... 

---

### METADATA

`metadata` métadonnées: données qui décrivent d'autres données. Le mode d'emploi ou la notice de ces données

> Exemple: coordonnées GPS d'une photo, notice de livre, catalogue

----

#### Formalisme des métadonnées

----

### DATASET

`dataset` jeu de données, ensemble de données collectées et ordonné. Cet ordre peut s'apparenter à un `schema` soit des métadonnées
qui décrivent les données: leur sens, leur ordre et leur format.

> Exemple: La manière la plus simple de concevoir ce qu'est un jeu de données c'est d'envisager un jeu de données à partir de son format de stockage. 

----

Le plus célèbre étant le fichier Excel soit des données rangées dans un tableau.

| champ  | champ   |  
|--------|---------|
| valeur | valeur  |

---

## Processus

### De la donnée à l'information

--- 

### COLLECTER

> DataMining: littéralement 'miner la donnée'

Action de récupérer des données, les nettoyer, les formater, les valider: 80% du temps de travail  

Méthodes de collecte varie en fonction des données de départ (~données brutes~) de leur type, de la source, de leur format et de leur taille. Le but étant très simplement de récupérer des données et de consituer un ensemble de ressource sur un sujet donné qu'on va organiser selon les besoins (cf data management)

----

Différentes méthodes de récupération de données

* Manuel
* Automatique:
  * Fouille et scrapping de site web, document ()
  * Requetes sur une BDD ou API
  * Moissonnage de site
  
---

1. Identifier et analyser les données de départ
2. Récupérer la ressource
3. Parcourir
4. Extraire
5. Transformer: nettoyer, convertir, formater
6. Structurer: ranger, ordonner, classer


Notions abordées : `sources`, `types de données`, `format`, `méthodes: datamining, datascrapping, crawler, nettoyage, normalization`


> Exemple: web scrapping, crawler, parser

----


---

##### RANGER/STOCKER

> DataManagement, DataIngénierie

Notions abordées : `base de données`, `cloud`, `serveur`, `index`, `entrepôt de données`, `modelisation`


> Exemple: moteur de recherche

----

Base de données et modélisation


---

##### ANALYSER/VOIR/EXPLORER

> DataAnalysis, DataVisualization


----

###### Aparté sur le `big data` 

----

Analyse de la données via des méthodes adaptées aux types de données:
- analyse qualitative
- statistiques quantitatives: descriptives ou inférentiels: analyse par regression, analyse Multifactorielle, analyse par cohortes par cluster par séries temporelles
- analyse de texte: nlp, sentiment analysis
- anayse des relations : graph analysis
- analyse par arbre de décision
- analyse par diagnostic/ analyse prédictive/ analyse prescriptive

----

##### EXPLOITER/CALCULER

> DataIngénierie, DataScience

A partir d'hypothèses de départ

Notions abordées : `algorithme`, `référentiels`, `base de données`, `requête`, `protocole`,`cloud`, `serveur`, `client`, `index`, `IA`

Exemple: Algorithme de recommandation: plusieurs amnières de l'implémenter


----

Aparté sur l'algorithme et implémentation


----

Apparté sur les enjeux de la DataScience et de l'IA 
 
---


datavisualisation représentation graphiques: plots cartography

---

##### ECHANGER/TRANSMETTRE

> DataArchitecture, DataIngénierie

`protocole`, `serveur/client` `référentiel`, `schema`, `standard`, `interopérabilité`, `API`, `opendata`


Exemple le protocole HTTP et le site web

----

Protocole HTTP


---- 

Interopérabilité


----

API