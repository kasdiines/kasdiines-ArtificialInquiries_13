# Artificial Inquiries — Exercice 13

## 1. Présentation de l'exercice

**Ex13 - Setting Up the Example** consiste à étudier une œuvre choisie comme exemple afin de comprendre pourquoi elle est considérée comme pertinente.

Pour cet exercice, j'ai choisi **Wikipédia**, une encyclopédie collaborative et libre.

Ce choix permet d'étudier plusieurs dimensions :

- le contexte dans lequel Wikipédia a été créé ;
- les pratiques mises en œuvre par les contributeurs ;
- les valeurs défendues par le projet ;
- les standards et règles utilisés pour produire et vérifier les contenus.

L'objectif est ensuite de transformer cette analyse en un outil numérique permettant de structurer les informations recueillies.

## 2. L'œuvre choisie : Wikipédia

Wikipédia est un projet d'encyclopédie collaborative accessible sur Internet. Les contenus sont produits et modifiés par des contributeurs.

Je considère Wikipédia comme un exemple intéressant pour cet exercice car son fonctionnement repose sur la collaboration, le partage des connaissances et des règles permettant d'organiser et de contrôler la qualité des contenus.

### Contexte

Wikipédia s'inscrit dans le développement des projets collaboratifs sur Internet. Son fonctionnement repose sur la participation de nombreux utilisateurs qui peuvent créer, modifier et améliorer les articles.

### Pratiques

Les principales pratiques que je peux identifier sont :

- la rédaction collaborative ;
- la modification des articles ;
- la vérification des informations ;
- l'utilisation de sources ;
- les échanges entre contributeurs ;
- la discussion autour des modifications.

### Valeurs

Les valeurs que je peux associer à Wikipédia sont notamment :

- le partage des connaissances ;
- l'accès libre à l'information ;
- la collaboration ;
- la vérifiabilité des informations ;
- la neutralité dans la présentation des sujets.

### Standards professionnels

Même si Wikipédia n'est pas une organisation professionnelle classique, son fonctionnement repose sur différentes règles et pratiques concernant la qualité de l'information.

Par exemple :

- citer les sources ;
- permettre la vérification des informations ;
- respecter certaines règles éditoriales ;
- maintenir une organisation cohérente des articles.

## 3. Objectif de l'outil numérique

L'objectif est de transformer l'exercice d'analyse en un outil numérique permettant de créer une fiche pour une œuvre exemplaire.

Pour Wikipédia, l'outil doit permettre de renseigner :

- le nom de l'œuvre ;
- son contexte ;
- ses pratiques ;
- ses valeurs ;
- ses standards professionnels ;
- les preuves permettant de justifier les observations ;
- les sources utilisées ;
- une analyse personnelle permettant d'expliquer les différents liens.

L'objectif est donc de passer d'une analyse principalement textuelle à une représentation structurée des informations.

## 4. Données principales

Le modèle de données contient plusieurs éléments :

- **Œuvre** : l'exemple étudié, ici Wikipédia ;
- **Pratique** : une pratique mise en œuvre par l'œuvre ;
- **Valeur** : une valeur représentée ou défendue par l'œuvre ;
- **Standard professionnel** : une règle ou un standard associé au fonctionnement de l'œuvre ;
- **Preuve** : un extrait ou une source permettant de justifier une observation ;
- **Analyse** : l'interprétation permettant d'expliquer les relations entre l'œuvre et les différents éléments.

Une œuvre peut être associée à plusieurs pratiques, valeurs, standards professionnels et preuves.

## 5. Solution technique

Le modèle de données est représenté avec un **diagramme de classes réalisé avec Mermaid**.

Le diagramme se trouve dans le fichier :

`diagram_class.md`

Pour la gestion des données et des ressources documentaires, **Omeka S** est utilisé comme environnement de travail local.

L'installation repose sur :

- Apache ;
- PHP ;
- MySQL ;
- Omeka S.

## 6. Fonctionnement envisagé

Le fonctionnement de l'outil est le suivant :

1. Sélectionner l'œuvre étudiée.
2. Renseigner ses informations générales.
3. Décrire son contexte.
4. Identifier les pratiques associées.
5. Identifier les valeurs représentées.
6. Identifier les standards professionnels concernés.
7. Ajouter les preuves et les sources.
8. Ajouter une analyse permettant de justifier les observations.
9. Consulter les informations sous une forme structurée.

## 7. Évolution possible

Dans une première version, l'outil permet de renseigner les principales informations concernant Wikipédia et son fonctionnement.

Par la suite, il pourrait être amélioré afin de permettre :

- la recherche dans les différentes œuvres étudiées ;
- l'ajout de nouvelles œuvres exemplaires ;
- la consultation des sources associées ;
- la comparaison des pratiques et des valeurs entre plusieurs œuvres ;
- une meilleure organisation des preuves et des analyses.
