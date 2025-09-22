# TP02 WebAR - Exercice 1 : Scène 3D avec A-Frame

## Objectif
Créer une scène 3D interactive en utilisant le framework A-Frame pour le développement WebAR.

## Réalisation

### Structure du projet
- **Fichier principal** : `index.html`
- **Framework utilisé** : A-Frame (version 1.4.0) via CDN
- **Dépôt GitHub** : https://github.com/hpaziaud/webAR.git

### Éléments de la scène 3D

#### 1. Trois boîtes colorées
- **Boîte bleue** (`#4CC3D9`) : position (-2, 2, 0)
- **Boîte rouge** (`#EF2D5E`) : position (0, 2, 0)  
- **Boîte jaune** (`#FFC65D`) : position (2, 2, 0)

Toutes les boîtes lévitent à 2 unités au-dessus du plan de base.

#### 2. Plan de base
- **Surface verte** (`#7BC8A4`) de 10x10 unités
- Positionné à (0, 0, 0) avec rotation -90° sur l'axe X
- Sert de sol pour la scène

#### 3. Caméra
- **Position** : (0, 10, 15)
- **Hauteur** : 10 unités
- **Distance** : 15 unités du centre
- **Orientation** : Vers le centre du plan pour une vue d'ensemble

#### 4. Éclairage
- **Éclairage ambiant** : Lumière douce générale
- **Éclairage directionnel** : Lumière principale pour les ombres

## Technologies utilisées
- **A-Frame** : Framework HTML pour la réalité virtuelle/augmentée
- **WebGL** : Rendu 3D via Three.js (intégré dans A-Frame)
- **HTML5** : Structure de base

## Résultat
Une scène 3D fonctionnelle accessible via navigateur web, avec trois objets colorés lévitant au-dessus d'un plan, vue depuis une caméra positionnée pour offrir une perspective optimale de la scène.

## Conclusion
L'exercice démontre la simplicité d'utilisation d'A-Frame pour créer rapidement des expériences 3D web. Le framework permet de développer des scènes interactives avec une syntaxe HTML intuitive, facilitant l'apprentissage du développement WebAR.
