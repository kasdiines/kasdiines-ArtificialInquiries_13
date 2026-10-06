# Artificial Inquiries — Exercice 13

## 1. Présentation de l'exercice

**Ex13 - Setting Up the Example** consiste à étudier une œuvre choisie comme exemple afin de comprendre pourquoi elle est considérée comme pertinente.

L'exercice permet d'observer plusieurs dimensions de cette œuvre :

- son contexte ;
- les pratiques qu'elle met en œuvre ;
- les valeurs qu'elle représente ;
- les standards professionnels auxquels elle peut être associée.

L'objectif est de transformer cet exercice d'enquête en un outil numérique permettant de structurer ces informations.

## 2. Objectif de l'outil numérique

L'outil doit permettre de créer une fiche pour une œuvre exemplaire et de renseigner les différentes informations liées à son analyse.

Pour chaque œuvre, il est possible de prévoir :

- le titre ;
- l'auteur ou le créateur ;
- une description ;
- le contexte ;
- les pratiques identifiées ;
- les valeurs associées ;
- les standards professionnels concernés ;
- les preuves ou extraits utilisés ;
- les sources utilisées.

L'objectif est de passer d'une analyse sous forme de texte à une représentation plus structurée des informations.

## 3. Données principales

Le modèle de données contient plusieurs éléments :

- **Œuvre** : l'exemple étudié ;
- **Pratique** : une pratique mise en œuvre par l'œuvre ;
- **Valeur** : une valeur représentée par l'œuvre ;
- **Standard professionnel** : un standard auquel l'œuvre peut être associée ;
- **Preuve** : un extrait ou une source permettant de justifier une observation ;
- **Analyse** : l'interprétation et la justification des liens entre l'œuvre et les différents éléments.

Une œuvre peut être associée à plusieurs pratiques, valeurs, standards professionnels et preuves.

## 4. Solution technique

Le modèle de données est représenté avec un diagramme de classes réalisé avec **Mermaid**.

Le diagramme se trouve dans le fichier :

`diagram_class.md`

Pour la gestion des données et des ressources documentaires, **Omeka S** est utilisé comme environnement de travail local.

L'installation repose sur :

- Apache ;
- PHP ;
- MySQL ;
- Omeka S.

## 5. Fonctionnement envisagé

Le fonctionnement de l'outil est le suivant :

1. Choisir une œuvre exemplaire.
2. Renseigner ses informations générales.
3. Décrire son contexte.
4. Identifier les pratiques associées.
5. Identifier les valeurs représentées.
6. Identifier les standards professionnels concernés.
7. Ajouter des preuves et des sources.
8. Ajouter une analyse permettant de justifier les observations.
9. Consulter les informations sous une forme structurée.

## 6. Organisation du repository

```text
ArtificialInquiries_13/
│
├── README.md
│
└── diagram_class.md
```

## 7. Évolution possible

Dans une première version, l'outil peut permettre de renseigner les informations principales de l'exercice.

Il pourra ensuite être amélioré avec une recherche dans les œuvres, une consultation des sources et une meilleure organisation des relations entre les pratiques, les valeurs, les standards professionnels et les preuves.*
