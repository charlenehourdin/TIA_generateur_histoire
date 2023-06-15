# TIA - Générateur d'histoire pour enfant 

## Description

Développement d’une application de génération de texte sous forme d’histoires pour enfant.

Cette solution tend à générer des histoires en anglais et en français.

Le but de cette application est de créer une histoire avec l’aide d’une intelligence artificielle, cette application permet aux utilisateurs de :
— Développer l’imagination et la créativité,
— Leurs faire aimer la lecture,
— Apprendre à utiliser un clavier et des outils numériques.

## Objectifs
La lecture peut être définie comme une activité psychosensorielle qui vise à donner un sens à des signes graphiques recueillis par la vision et qui implique à la fois des traitements per- ceptifs et cognitifs. Les capacités cognitives de notre corps nous aident à mieux comprendre le monde qui nous entoure, il est possible d’appliquer ce principe à l’apprentissage machine.
Le besoin exprimé pour mon projet est que de plus en plus d’enfants développent des troubles d’apprentissage en lecture et en écriture appelée le plus souvent trouble dyslexique (trouble de l’apprentissage du langage écrit).

Le plus souvent, suite à leurs troubles, ces enfants développent une phobie de la lecture. Pour les aider, je souhaite développer un outil permettant de générer des histoires en permettant à l’utilisateur de débuter une histoire.

Cet outil peut également convenir à plusieurs cas d’usage :

— Un auteur qui présente un syndrome de leucosélophobie (syndrome de la page blanche)
— Un enseignant qui souhaite créer un nouvel exercice basé sur une histoire (par exemple création d’un dessin en fonction de l’histoire lue)
— Un parent ou un enfant qui souhaite créer une histoire unique.

 ## Données

L’objectif du projet étant de pouvoir générer des histoires, il est nécessaire de disposer d’un volume important d’histoires.

J’ai donc initiée une recherche de sources de données répondant aux critères suivants :

— Données disponible faisant partie du domaine public (les données venant d’un au- teur font partie du domaine public 50 ans après sa mort.)
— Données appropriées aux enfants (sans contenus injurieux, etc.)

Pour le projet, j’ai besoin de données en français et en anglais. Les données utilisées pour ce projet peuvent être la propriété de créateur de contenu, dans mon cas des auteurs, j’ai décidé d’utiliser un ensemble de données accessible au public contenant différentes histoires. J’ai récupéré l’ensemble des données en effectuant du web scraping via une API pour les da- tasets des contes de Grimms en Français et j’ai récupéré les datasets des contes d’Andersen en français et en anglais ainsi que les contes de Grimms en anglais sur le projet Github d’un utilisateur ayant utilisé ses ensembles de données pour un projet traitant du NLP (Natural language preprocessing)

L’ensemble des données utilisés dans ce projet sont :  

— Les contes de Grimms :  
  — 115 histoires en français ;   
  — 201 histoires en anglais.  
— Les contes d’Andersen :   
  — 53 histoires en français ;  
  — 156 histoires en anglais.  

Ces données faisant partie du domaine public, je me prémunis contre les conséquences juridiques potentielles relatives à un droit d’auteur en cours ou à un recours intensif au web scraping dont la légalité est discutable.
