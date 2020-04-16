---
title: Combat
description: 
published: true
date: 2020-04-16T12:46:59.726Z
tags: 
---

:warning: A reworder complètement.

> La violence est le dernier recours de l'incompétence.
> _Salvor Hardin_
{.is-warning}

> Ça y'est!  Vous êtes entrés dans une phase de négociation musclée.
Il est temps de se mettre sur la figure, : le combat commence.
{.is-info}

Lorsque les joueurs, ou le maître du jeu, décident qu'il est temps de réduire l'ennemi en petits bouts plus ou moins comestibles, on déclenche un **Combat**.

~~Lors d'une rencontre entre différents `protagonistes`, c'est à dire des personnages joueurs comme non joueurs, lorsque l'un d'eux montre une velléité de porter atteinte à l'intégrité, physique, ou mentale de l'autre partie, alors on initie une phase de combat.~~

<a id="protagoniste"></a>
**Protagoniste:**
dans un combat, on appelle **Protagoniste**, tout personnage, joueur ou non-joueur, intervenant dans le combat.

**Mise en place :**
On détermine qui peut agir, on rassemble leurs ressources (cartes Action et Réaction) et on se tient prêt pour la première passe d'initiative.

## Tours de combat
Afin de simplifier la gestion de la temporalité, un Combat se découpe en tours.
Un tour de combat se découpe de la manière suivante :

- Préparation
- Passe d'initiative (une ou plusieurs) 
- Fin du tour

Un tour de combat commence avec la **préparation**:

 - on mélange le deck d'initiative
 - on distribue les cartes réactions

Une fois la préparation terminée, le tour **continue**; on entame une passe d'initiative, en révélant une carte.
Tant qu'il y a au moins une carte dans le deck d'initiative, le tour **continue** ; on enchaîne les passes d'initiative.

Le tour se **termine** lorsqu'on tente de révéler une carte d'action dans le deck d'initiative, mais que ce dernier est vide. 
À ce moment, tous les `protagonistes` perdent leurs actions restantes :
 - les cartes action restantes ne peuvent plus être utilisées
 - les cartes réaction restantes ne peuvent plus être utilisées
Si le combat n'est pas terminé, on recommence un tour de combat, avec sa préparation.

### Préparation

Chaque `protagoniste` dispose d'un certain nombre de points d'**`Actions`**,  matérialisés par des cartes nominatives.

Au début du tour de combat, tous les `protagonistes` mettent en commun leurs cartes **`Actions`** que l'on mélange pour constituer le **`Deck d'initiative`** (wording: Deck d'action ?). 

Le tour commence lorsque le MJ (ou n'importe quel autre joueur) révèle la première carte du Deck d'initiative.

## Agir: l'Initiative

Une **`passe d'initiative`** démarre alors.

### Passe d'initiative

Une **`Passe d'initiative`** est la séquence d'événements se déroulants, à partir le moment où une carte du Deck d'initiative est révélée, et ce jusqu'à ce que la passe d'initiative prenne fin.
Une **`Passe d'initiative`** est la séquence d'événements se déroulants, entre deux pioches de cartes du deck d'initiative. Elle commence avec la première pioche, et se finit avant la seconde.

Une **`Passe d'initiative`** se déroule de la manière suivante :

1. la **pioche:** une carte du Deck d'initiative est révélée. La pioche marque le début de la passe. 
1. l'**action** : le `protagoniste` inscrit sur la carte d'action **possède l'initiative**. Il peut alors:
     1. **jouer:** il peut consommer tout ou partie des carte d'actions qu'il possède à cet instant, pour utiliser **une unique capacité** ~~des capacités et effectuer des actions~~
     1. **passer:** il ne fait rien et met alors sa carte d'action face visible devant lui. Il pourra l'utiliser par la suite.  
1. la **réponse:** les adversaires du `protagoniste` venant de jouer, désignent parmi eux, un `protagoniste`. Ce dernier **possède l'initiative** ; il peut **jouer** ou **passer**.
    - TODO: Pas de méthode de désignation actuellement définie
    - Dans le cas où il y à plus de deux factions, le MJ décide quel camp possède la réponse. Préférentiellement, il s'agira de la faction agressée. La réponse à cette réponse suit les mêmes règles. 
1. Les phases de **réponses** se succèdent à moins que deux `protagonistes` passent consécutivement: La passe d'initiative prend fin.

Exemples : passe d'initiative possible pour un combats en 1 vs1 entre Alice et Bob. Alice pioche et possède l'initiative.

- ☑ *Alice pioche, Alice passe, Bob passe, fin de la passe.*
- ☑ *Alice pioche, (Alice passe, Bob joue,)^n Alice passe, Bob passe, fin de la passe.*
- ☑ *Alice pioche, Alice joue, Bob passe, Alice passe, fin de la passe*
- ☑ *Alice pioche, (Alice joue, Bob passe,)^n Alice passe, fin de la passe.*
- ☑ *Alice pioche, Alice joue, Bob joue, Alice passe, Bob passe, fin de la passe.*
- ☑ *Alice pioche, (Alice joue, Bob joue,)^n Alice passe, Bob passe, fin de la passe.*

```
            
    Pioche --> Action: Alice 
                      Joue ---> Réponse: Initiative Bob
                               Joue -> Réponse Alice
                               Passe -> Réponse Alice
                      Passe ---> Réponse: Initiative Bob
        Initiative Alice 
    
```

Questions:

- Si un `protagoniste` passe au cours d'une passe d'action, est-ce qu'il peut rejouer plus tard dans la même passe d'initiative ?
    - Pro: risque pris récompensé, possibilité de rattraper une situation qui dégénère. Empêcher de rejouer fera tourner le combat en tentative de bloquer les réponses adverses. De plus le nombre de réponse serait une ressource directement indexée le la quantité de protagonistes dans chaque camp. 
    - Cons: peut ralentir la passe d'init, ralenti la détermination du `protagonistes` possédant l'initiative. 
    - **Décision:** oui, s'il passe dans une passe d'initiative, un protagoniste peut répondre plus tard dans la même passe. 

~~
Récupération de "Agir".

## Initiative
### Lancer de dé
Les acteurs d'un combat lancent un jet d'initiative. Ils jouent ensuite leur tour de combat, dans l'ordre décroissant des initiatives.
Au début de son tour, un acteur récupère tous ses points d'Action et de Réaction.

### Deck d'actions.
Les `Actions` des acteurs d'un combat sont représentées par des cartes nominatives. On mélange toutes les cartes et on les tire une par une. 

Lorsqu'une carte est révélée, elle est rendue à son possesseur. Celui-ci acquiert "la main"/l'initiative sur le combat.
Il peut alors dépenser sa ou ses `Actions` pour activer une `Capacité` connue. Sinon, il peut garder ses Actions pour les dépenser plus tard dans le tour.

Une fois le Deck vidé, c'est la fin du tour. On récupère toutes les cartes, même celles qui n'ont pas été jouées, et on les mélange.

**Actions sur plusieurs tours :** Sais pas 😑
**Acteur ayant toutes ses cartes en main :** Sais pas 😑
~~

## Fin du Tour

Le tour se **termine** lorsqu'on tente de révéler une carte d'action dans le deck d'initiative, mais que ce dernier est vide.

À ce moment, tous les `protagonistes` perdent leurs actions restantes :
 - les cartes action restantes ne peuvent plus être utilisées
 - les cartes réaction restantes ne peuvent plus être utilisées
Si le combat n'est pas terminé, on recommence un tour de combat, avec sa préparation.

## Réagir

La réaction est une interruption du flux normal du combat. Un protagoniste réagit à un **événement** et dépense des **Réaction s** pour intervenir.

Chaque `protagoniste` dispose d'un certain nombre de points de **`Réactions`**,  matérialisés par des cartes nominatives. 
Au début du combat, tous les `protagonistes` récupèrent devant eux, autant de carte **`Réactions`** que leur maximum leur permet. 

- la **réaction:** où une équipe effectue une action, hors du flot normal d'initiative (c'est une mécanisme de pile)
  -> ça peut être le déclenchement d'une action préparée
  -> ça peut être le déclenchement d'une réaction générique face à un événement prévu par une capacité du personnage (exemple D&D: un déplacement d'un personnage A dans une case contrôlé par un personnage B provoque une attaque d'opportunité de B vers A)


## Surprise

> modulo la surprise, qui fait partie du combat, mais pour laquelle l'initiative n'est parfois pas encore lancée

## Ressources

Les ressources utilisables en combat :
- PV
- (Lucidité) 
- Action
- Réaction
- Réserve de dés


# Action

> **Coût:** cf. Capacité

> **Déclencheur:** décision du joueur

> **Effet:** cf. Capacité

> L'**Action**, correspond à l'activation consciente d'une **Capacité**.

**Action :** Le **[Personnage](https://trello.com/c/j5txrEnh)** choisit une **[Capacité Active](https://trello.com/c/seeagtHL)** et paie son **Coût**, pour en déclencher ses **Effets**.

Le **[Personnage](https://trello.com/c/j5txrEnh)** peut effectuer une **Action**:

- lors d'une **Passe d'initiative**, quand il **possède l'initiative**

- lors d'une **Passe d'initiative**, en **Réponse** à un adversaire. 

Le coût d'une **Action** s'exprime en "**Point d'Action**" (Carte Action, Initiative) : **`A°`**

# Réaction

> **Coût:** cf. Capacité

> **Déclencheur:** Événement propice (cf. Capacité) et décision du joueur

> **Effet:** cf. Capacité

> Une **Réaction** est une **Action**, que l'on ne peut faire qu'en réponse à un **Événement spécifique**. 

**Réaction :** Le **[Personnage](https://trello.com/c/j5txrEnh)** peut effectuer une **[Action](https://trello.com/c/MPbgE0oE)** en réponse à un **Événement spécifique**, en payant le coût de Réaction à la place du coût d'Action. 

Un **[Personnage](https://trello.com/c/j5txrEnh)** ne peut effectuer de **Réaction**, que s'il possède une **[Capacité Active](https://trello.com/c/seeagtHL)**, permettant de répondre à l'**Événement spécifique**

Le coût d'une **Réaction** s'exprime en "**Point de Réaction**" (Carte Réaction, Initiative) : **`R°`**.

# Marque
-> record en "Effet"

Une Marque représente un Effet se déclenchant à un moment du jeu, sans décision. 

Les marqueurs permettent de représenter des Effets à différer dans la temporalité du jeu.

Un marqueur porte les données suivantes :

- Nom
- Type du Marqueur
- Déclencheurs
- Effets

Exemples factices de la syntaxe: 

- **Marqueur (Choc, Cumul, Attaque<+1>, À la prochaine attaque)**
- **Choc: Marqueur(Cumul, Attaque<+1>, À la prochaine attaque)**

## Types de marqueur
Un marqueur possède un, et un seul type. Le type détermine les contraintes de dépense du marqueur, lorsque les conditions de déclenchement sont réunies. 

> Variantes :
> - Le type "Marqueurs" est associé à un nombre minimal de marqueurs à dépenser pour déclencher l'effet.
> - Le type "Marqueurs" est associé à un nombre maximal de marqueurs que l'on peut dépenser pour un même déclenchement. 

### Cumul
> Wordings?: Stack, Canalisation

Les marqueurs de même nom se cumulent entre eux.
Quel que soit leur nombre, ils sont tous dépensés en même temps, pour une unique utilisation et leurs effets se cumulent.

### Pile
> Delay/Répartition/Jauge/Réserve/Bassin/Pile/Dispersion

Les marqueur de même nom forment une pile.
Il sont dépensés un par un, à chaque fois que les conditions de déclenchement sont réunies, suivant une stratégie "premier arrivé, premier parti" (FIFO) . 

## Déclencheurs

Un **Déclencheur** décrit un contexte, ou un événement qui permet/force le possesseur du marqueur à le consommer.

## Effets
> Cumul des effets vs. Effet le plus puissant

Les effets d'un marqueur peuvent varier .
Le plus souvent ils influent comme modificateur de Compétence:

- <Compétence>
   [Compétence]
- Valeurs : fixe ou lancer. 
    Ex: Marqueur (Cumul, [Pistolet], Attaque)
- Application :
    +/-1 A° (Accélération,  Étourdissement, Paralysie) 
    +/-1 R°
    +/-1 Attaque (Rage, Nova, Affaiblir) 
    +/-1 Dégât

> NB: Typer les Compétences/Capacités

## Rôle
## Postures
