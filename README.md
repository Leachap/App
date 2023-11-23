# Projet WEB + Android

*10/12/2023, Pierre-Elliot Monsch - Lea Chapellon*

## Sommaire

1. Presentation de l'API
2. Résumé des consignes

## Presentation de l'API

*[lien du site des données](https://odre.opendatasoft.com/explore/dataset/bornes-irve/information/?disjunctive.region&disjunctive.departement)*

*[lien de la documentation sur l'API](https://help.opendatasoft.com/apis/ods-explore-v2/explore_v2.1.html)*

Nous avons choisi pour ce projet une API de borne de recharche pour véhicules électriques de la base ODRE (OpenData Réseau Energie)

Bien que l'API contienne des données sur des bornes partout dans le monde, nous nous concentrons sur celles situées en France.

## Consignes

- [x] Repository GitHub
- [x] README.md
- [x] API avec Nest JS
  - [x] Format JSON
  - [ ] champ correspondant à l’url d’une image
  - [x] champ correspondant à une latitude/longitude
  - [x] API chargée lors du démarrage
  - [x] Charger les données OpenData dans l’API Nest lors de son démarrage
  - [x] Exposer des URLs pour faire des requêtes permettant de :
    - [x] Récupérer un résumé de toutes les données
    - [x] Récupérer le détail d’une donnée
    - [x] Mettre une donnée en favori ou non.
    - [x] Deployée sur Clever Cloud
  - [ ] *Bonus :*
    - [ ] *Ajouter un endpoint pour créer de nouvelles données*
    - [ ] *Ajouter un endpoint de recherche*
    - [ ] *Gérer la pagination des données sur le endpoint retournant le résumé des données*
- [x] Application Android
  - [x] Récupération des données de l'API
    - [x] Affichage sur une carte
    - [x] Affichage dans une liste
    - [ ] Affichage sur un écran avec le détail d'une donnée
  - [x] Possibilité de mettre en favoris certains éléments
  - [x] 3 Fragments
    - [x] liste
    - [x] Map
    - [x] Info
  - [ ] 2 activity
  - [ ] Toolbar avec rafraichissement
  - [ ] *Bonus :*
    - [ ] Mise en place d’une base de données locale 
    - [ ] Utilisation de LiveData ou d’Observable pour la récupération de données dans la BDD
