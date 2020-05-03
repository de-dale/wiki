---
title: Mermaid
description: Bac à sable pour mermaid JS
published: true
date: 2020-05-03T12:12:03.458Z
tags: 
---

# C'est quoi
> Voir la documentaiont en ligne https://mermaid-js.github.io/mermaid/#/

# Mermaid

Mermaid est un outil JavaScript permettant de générer des images de diagrammes à partir d'une structure texte assez compréhensible.
Il permet de générer une image représentant le graphe des Facettes dans la représentation des Sphères. 

Documentation : https://mermaidjs.github.io/#/flowchart

Exemple :
```
    ```mermaid
    graph TD
      A[Square Rect] -- Link text --> B((Circle))
  	  A --> C(Round Rect)
      B --> D{Rhombus}
      C --> D
    ```
```

```mermaid
	graph TD
		A[Square Rect] -- Link text --> B((OH YEAH!))
		A --> C(Round Rect)
		B --> D{Rhombus}
		C --> D
```

Avec des icones issues de [Font Awesome Icons](fontawesome.com/icons)

```
    ```mermaid
	  graph LR
      A --- B
      B-->C[fa:fa-ban forbidden]
      B-->D(fa:fa-spinner);
    ```
```

<link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.3.1/css/all.css" crossorigin="anonymous">

```mermaid
graph LR
    A --- B
    B-->C[fa:fa-ban forbidden]
    B-->D(fa:fa-spinner);
```

```mermaid
graph TD
  Feu --> (Métal)
  Métal --> (Ténèbres)
  Ténèbres --> (Poison)
  Poison --> (Pierre)
  Pierre --> (Feu)
  %%Ténèbres --> Feu
  %%Feu --> Poison
  %%Poison --> Métal
  %%Métal --> Pierre
  %%Pierre --> Ténèbres
```

# Récupérer le diagramme sous forme d'iamage

Utiliser l'éditeur en ligne : mermaid-js.github.io/mermaid-live-editor/
Copier/coller la définition de votre diagramme dans l'éditeur.
Cliquer sur "Download SVG" ou "Download PNG"