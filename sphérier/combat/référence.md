---
title: 📖 Documentation de référence
description: :book: Documentation de référence du combat
published: true
date: 2020-05-04T21:17:13.875Z
tags: combat, référence
---

<span style="background:#cceeee;padding:5px;border-radius:10px;">:baby_bottle: **[Tutoriels]**</span> <span style="background:#aaddaa;padding:5px;border-radius:10px;">:gear: **[Guide pratique]**</span> <span style="background:#ccccee;padding:5px;border-radius:10px;">:book: **[Référence]**</span> <span style="background:#eeccee;padding:5px;border-radius:10px;">:sparkles: **[Concepts]**</span>

[Tutoriels]: /sphérier/combat/premiers-pas
[Guide pratique]: /sphérier/combat/guides
[Référence]: /sphérier/combat/référence
[Concepts]: /sphérier/combat/concepts

---

# :book: Le déroulement du combat
<span style="background:#ccccee;padding:5px;border-radius:10px;">:book: **[Référence]**</span>

Un **Combat** suit un déroulé bien précis. Afin de simplifier la gestion de la temporalité, il se découpe en tours de jeu.
<a id="initiative-préparation"></a>
## Préparation de l'initiative
[Préparation de l'initiative]: #initiative-préparation

L'initiative, c'est à dire l'odre dans lequel les joueurs jouent, n'edst pazs défini en avance. L'ordre est déterminié par la pioche des Cartes Actions de chaque [Acteur].
Au début de chaque tour, tous les [Acteurs] mettent en commun leurs **Cartes d'Action** pour constituer le [Deck d'initiative].
Le tour commence dès que ce **[Deck d'Initiative]** est constitué.

> :warning: TODO : Worder cette étape.
{.is-warning}

## Déroulement d'un tour

Un tout se déroule de la manière suivante :

1. **Piocher**
2. **Agir**
3. **Répondre**

Quand le [Deck d'initiative] est vide au moment de [Piocher], c'est la fin du Tour(\*). 
Le [Deck d'initiative] est remélangé, et c'est le début d'un nouveau tour.

<a id="pioche"></a>
### Piocher
[Pioche]: #piocher
[Piocher]: #piocher

La première carte du [Deck d'Initiative] est révélée par un joueur, que l'on appellera le **[Decker]**. Son possesseur est alors appelé **[Acteur principal]**. Il ajoute les [Points d'Action] correspondant à sa réserve, et applique les eventuels autres effets de la carte.

Il peut ensuite **[Agir]**.

<a id="agir"></a>
### Agir
[Agir]: #agir
[Jouer]: #jouer
[Passer]: #passer

Lorsqu'un [Acteur] peut [Agir] : il a le choix entre [Jouer] ou [Passer].
<a id="jouer"></a>
1. **Jouer**
Il peut consommer tout ou partie de ses **[Points d'Action]**, pour activer **une unique** capacité (se déplacer, attaquer, lancer un sort, etc).
**Jouer** ouvre la possibilité aux adversaires de l'[Acteur principal] de [Répondre].
<a id="passer"></a>
2. **Passer**
Il ne fait rien et conserve ses **Points d'Action** pour plus tard.
C'est alors la fin de son tour, et on enchaîne avec une nouvelle **[Pioche]**

<a id="répondre"></a>
### Répondre
[Répondre]: #répondre
[Réponse]: #répondre

Une fois que l'[Acteur Principal] a fini, le Narrateur/MJ donne la main à une [Faction] adverse. Celle-ci désigne un [Acteur], qui peut désormais [Agir]. Ce dernier dispose des mêmes choix décris ci-dessus ; **Jouer** ou **Passer**, avec les différences suivantes :

1. **Jouer**
Il peut consommer tout ou partie de ses **[Points d'Action]**, pour activer **une unique** capacité.
2. **Passer**
Il ne fait rien et conserve ses **Points d'Action** pour plus tard.

Une fois la réponse terminée, l'[Acteur principal] peut de nouveau [Agir].

> **Remarque :**
Dans le cas où il y à plus de deux **Factions**, c'est au Narrateur/MJ de décider quelle **Faction** peut **Agir**.
Préférentiellement, il s'agira de la **Faction** agressée, mais ce n'est pas automatique.

> :information_source: Si un [Acteur] passe, lors d'une [Réponse], il pourra toujours jouer plus tard, dans le même tour.
{.is-info}

#### Exemple par un diagramme

Pour un combats en 1vs1 entre :
- Alice, qui pioche
- Bob

```mermaid
stateDiagram
	state "Alice : Acteur principal" as Alice
  state "Bob : Adversaire d'Alice" as Bob

	[*] --> Alice : Alice pioche

	Alice --> Bob : Alice joue
	Bob --> Alice : Bob joue
  Bob --> Alice : Bob passe
  
  Alice --> [*] : Alice passe
```

## <a id="initiative-fin"></a> L'Initiative prend fin
[l'initiative prend fin]: #initiative-fin

Lorsque le [Decker] n'a plus de Carte Action à révéler dans le [Deck d'Initiative], alors, **[l'initiative prend fin]**.
À ce moment, tous les effets qui se déclenchent "_à la fin du tour_" ou "_lorsque l'initiative prend fin_", sont activés dans l'ordre dans lequel ils ont été créées.

Si le combat n'est pas terminé, on recommence la [Préparation de l'initiative].

## <a id="combat-fin"></a> Fin du combat

> Fin du combat
{.is-danger}

# :book: Autres aspects du combat

## <a id="réagir"></a> Réagir

La **Réaction (à un événement)** est une **Action** qui s'effectue en dehors du flux normal de l'initiative.
Un **Protagoniste** peut **Réagir** face à un **Événement** ; il peut consommer tout ou partie de ses **Point de Réaction** pour activer **une unique** capacité pouvant se déclencher face à l'**Événement**

Exemple (inspiré de D&D) :
- Événement: Alice se déplace dans un espace contrôlé par Bob
- Réaction: Bob porte une "attaque d'opportunité" à Alice (version D&D )
    - En détail : Bob possède une Capacité de type "Attaque", permettant de "Réagir face aux déplacements des adversiares dans l'espace qu'il contrôle"n qu'il active car il possède suffisement de Point de Réaction pour le faire.

Un **Protagoniste** peut **Réagir** face à un **Evénement** ; il peut consommer tout ou partie de ses **Point de Réaction** pour activer **une unique** capacité pouvant se déclencher face à l'**Evenement**
- la **réaction:** où une équipe effectue une action, hors du flot normal d'initiative (c'est une mécanisme de pile)
  -> ça peut être le déclenchement d'une action préparée
  -> ça peut être le déclenchement d'une réaction générique face à un événement prévu par une capacité du personnage (exemple D&D: un déplacement d'un personnage A dans une case contrôlé par un personnage B provoque une attaque d'opportunité de B vers A)

> **Préparer son action**
Impossible.
La possibilité d'utiliser une Capacité "en réaction à un événement" est propre à chaque Capacité.

## <a id="surprise"></a>  Surprise

> modulo la surprise, qui fait partie du combat, mais pour laquelle l'initiative n'est parfois pas encore lancée

# Détails techniques du combat

## <a id="effet"></a> Effet
[Effet]: #effet
[Effets]: #effet

Un [Effet] représente quelque chose qui mofifie l'état du jeu.

Exemples d'effets :

- <Compétence>
   [Compétence]
- Valeurs : fixe ou lancer. 
    Ex: Marqueur (Cumul, [Pistolet], Attaque)
- Application :
    +/-1 A° (Accélération, Étourdissement, Paralysie) 
    +/-1 R°
    +/-1 Attaque (Rage, Nova, Affaiblir) 
    +/-1 Dégât

### Durée de l'Effet
Une Effet peut être instantané ou persistant.

Un Effet instanténé applique ses modifications, et disparaît du jeu. Les modifications restent.
Un Effet persistant applique ses modifications, et reste en jeu. Quand il disparaît, les modifications qu'il entraîne, disparaissent avec lui. La durée d'un Effet persistant n'engage que lui, elle peut être éphémère (durée du comabt), durable ( une journée), permanente, ou encore spécifique (ex: "<Compétences> minutes")

### Types d'Effets

#### Cumul

Les Effets de Cumul se cumulent entre eux : on additionne tous leurs Effets pour en déterminer un Effet résultant.
Quel que soit leur nombre, ils sont tous effectifs en même temps.

#### Puissance

Les Effets de Puissance ne se cumulent pas entre eux, seul le plus puissant est pris en compte.
Les Effets de Puissance ne se cumulent pas avec les Effets Cumulés. En cas de conflit, l'Effet résultant du Cumul est comparé avec l'Effet de Puissance pourt déterminer quel effet est effetif.

  ## <a id="action"></a> Action

> **Coût:** cf. Capacité
**Déclencheur:** décision du joueur
**Effet:** cf. Capacité

> L'**Action**, correspond à l'activation consciente d'une **Capacité**.

**Action :** Le **[Personnage](https://trello.com/c/j5txrEnh)** choisit une **[Capacité Active](https://trello.com/c/seeagtHL)** et paie son **Coût**, pour en déclencher ses **Effets**.

Le **[Personnage](https://trello.com/c/j5txrEnh)** peut effectuer une **Action**:
- lors d'une **Passe d'initiative**, quand il **possède l'initiative**
- lors d'une **Passe d'initiative**, en **Réponse** à un adversaire. 

Le coût d'une **Action** s'exprime en "**Point d'Action**" (Carte Action, Initiative) : **`A°`**

## <a id="réaction"></a> Réaction

> **Coût:** cf. Capacité
> **Déclencheur:** Événement propice (cf. Capacité) et décision du joueur
> **Effet:** cf. Capacité

> Une **Réaction** est une **Action**, que l'on ne peut faire qu'en réponse à un **Événement spécifique**. 

**Réaction :** Le **[Personnage](https://trello.com/c/j5txrEnh)** peut effectuer une **[Action](https://trello.com/c/MPbgE0oE)** en réponse à un **Événement spécifique**, en payant le coût de Réaction à la place du coût d'Action. 

Un **[Personnage](https://trello.com/c/j5txrEnh)** ne peut effectuer de **Réaction**, que s'il possède une **[Capacité Active](https://trello.com/c/seeagtHL)**, permettant de répondre à l'**Événement spécifique**

Le coût d'une **Réaction** s'exprime en "**Point de Réaction**" (Carte Réaction, Initiative) : **`R°`**.

## <a id="marque"></a> Marque

Une Marque représente un [Effet] se déclenchant automatiquement face à un Evenement Spécifique. 
Une Marque peut permettre de représenter des Effets à différer dans la temporalité du jeu.

Une Marque porte les données suivantes :

- Nom
- Cible
- Déclencheurs
- Effets

> Variantes :
> - L'Effet produit par une Marque peut dépendre du nombre de Marque de même nom
> - Une Marque peut avoir un nombre minimal de Marques à dépenser pour déclencher l'Effet.
> - Une Marque peut avoir un nombre maximal de Marques à consommer pour un même déclenchement. 

### Déclencheurs et Evénements Spécifiques

Un **Déclencheur** décrit un contexte, ou un événement qui permet/force le possesseur du marqueur à le consommer.

Exemples d'événements Spécifiques 

- La Cible de la Marque utilise une Capacité d'Attaque
- Les Points de vie de la Cible descendent sous un certain seuil.
- La Cible de la Marque est touchée par une Capacité activée par un Rôle "Epéiste"

## <a id="rôle"></a> Rôle

Dans le Sphérier, les personnages n'ont pas de classe. En revanche, s'ils en ont la **Capacités**, ils peuvent endosser un **Rôle** répondant à leurs besoins. Certaines Capacités ne s'activent que si le personnage à endossé le Rôle adéquat, de même que certains Declencheurs dans les combos de Formation de Combat. 

**Changer de Rôle** au cours du combat est possible, mais demande du temps et de la concentration (PA + éventuellement un équivalent à "Incanter"). 

Certaines Capacités permettent de simuler un Rôle différents du Rôle endossé par le personnage. 

Exemples de rôle :
- Formation "Classique" : Tank, Healer, Damager, Support
- Formation "ToG": Pêcheur, Lancier, Veilleur, Éclaireur, Contrôleur de Mana
Elizeur

## <a id="posture"></a> Postures

Techniquement, la Posture et le Rôle fonctionnent de la même manière, et cohabitent : un personnage peut en même temps, endosser un Rôle et adopter une Posture. 
Quelques différences:
- on peut commence le combat adversaire un Rôle, mais pas avec une Posture
- il est plus facile de prendre ou de changer de Posture que de Rôle
- prendre ou maintenir une Posture peut demander des Ressources

# <a id="glossaire"></a> Glossaire
[Glossaire]: #glossaire
<span style="background:#ccccee;padding:5px;border-radius:10px;">:book: **Référence**</span> La liste des termes utilisés dans cette documentation.

<a id="acteur"></a>
### Acteur
[Acteur]: #acteur
[Acteurs]: #acteur
[Acteur principal]: #acteur

Les [Acteurs] correspondent aux individus ou aux groupes, pouvant intervenir au cours d'un combat.
Pour un individu, personnage ou monstre, on parlera de [Protagoniste], pour un groupe, il s'agira d'une [Faction].

L'[Acteur principal] correspond à l'[Acteur] dont la Carte d'Action a été révélée lors de la [Pioche].

<a id="carte-action"></a>
### Carte d'Action
[Carte Action]: #carte-action

Carte d'un [Acteur] lui octroyant des [Points d'Action], et éventuellement dispensant des effets.

<a id="deck-initiative"></a>
### Deck d'Initiative
[Deck d'Initiative]: #deck-initiative

Le **_Deck d'Initiative_** contient toutes les **Cartes Actions** de tous les **Protagonistes** d'un combat.
Il est constitué au début du tour.
_Alt: "Pioche d'Initiative"_

<a id="decker"></a>
### Decker
[Decker]: #decker

Le joueur qui révèle les cartes du **Deck d'Initiative** est appelé le **_Decker_**.
Ce rôle peut être endossé par le Narrateur, s'il le souhaite.

> Terme alternatif : Donneur

<a id="faction"></a>
### Faction
[Faction]: #faction
[Factions]: #faction

Une **[Faction]** regroupe plusieurs [Protagonistes], qui cherchent la même issue dans le combat, qui partagent le même objectif.
Chaque **Protagoniste** est rattaché à une unique **Faction**.

<a id="pioche"></a>
#### Piocher
[Pioche]: #piocher
[Piocher]: #piocher

La **Pioche** est la première étape d'un tour de combat
Un joueur, que l'on appellera le [Decker], révèle à l'assemblée, la première carte du [Deck d'initiative].

* L'[Acteur] propriétaire de la carte devient l'[Acteur principal].
* Il applique immédiatement les effets de sa **[Carte Action]**, généralement un gain en **[Point d'Action]**
* Il peut ensuite **[Agir]**.

<a id="point-action"></a>
### Point d'Action
[Point d'Action]: #point-action
[Points d'Action]: #point-action
[Ressource] permettant d'activer les Capacités actives.

<a id="point-réaction"></a>
### Point de Réaction
[Point de Réaction]: #point-réaction
[Ressource] permettant d'activer les Capacités ré-actives.

<a id="protagoniste"></a>
### Protagoniste
[Protagoniste]: #protagoniste
[Protagonistes]: #protagoniste

Un **Protagoniste** désigne n'importe quel personnage, joueur ou non-joueur, intervenant dans le combat.

<a id="ressource"></a>
### Ressources
[Ressource]: #ressources
Terme méta désigantun élément de jeu qu'il est possible de consommer dans le combat.

Les ressources utilisables en combat :
- Point de vie: PV (et dérivés : Lucidité, Bouclier, PV temporaires, etc.) 
- Point d'Action: PA
Nécessaires pour activer des capacités et faire des actions.
- Point de Réaction : PR
A fusionner avec les PA
- Autres ressources, spécifiques à chaque build
Ça peut être des ressources nécessaires (munitions ou mana) ou des ressources pour altérer des capacités existantes (Actions héroïque)

# :gear: Guide pratique
<span style="background:#aaddaa;padding:5px;border-radius:10px;">:gear: **[Guide pratique]**</span>

### Altération
### Combo
### Marque

# :sparkles: Concepts
<span style="background:#eeccee;padding:5px;border-radius:10px;">:sparkles: **[Concepts]**</span>
### Questions spécifiques

> Questions (à mettre dans les Concepts):
> - Si un `protagoniste` passe au cours d'une passe d'action, est-ce qu'il peut rejouer plus tard dans la même passe d'initiative ?
>    - **Pro:** risque pris récompensé, possibilité de rattraper une situation qui dégénère. Empêcher de rejouer fera tourner le combat en tentative de bloquer les réponses adverses. De plus le nombre de réponse serait une ressource directement indexée le la quantité de protagonistes dans chaque camp. 
>    - **Cons:** peut ralentir la passe d'init, ralenti la détermination du `protagonistes` possédant l'initiative. 
>    - **Décision:** oui, s'il passe dans une passe d'initiative, un protagoniste peut répondre plus tard dans la même passe. 

> :warning: Si un **Protagoniste** passe, dans une **Passe d'initiative**, il pourra toujours jouer plus tard, dans la même Passe, si celle-ci se poursuit.
{.is-info}

> **Points d'Action vs Points de Réaction**
TODO : lien vers les Concepts :sparkles: 
Décision : **Points d'Action == Points de Réaction**. Pas de raison de faire deux réserves différentes.
{.is-warning}

---
<span style="background:#cceeee;padding:5px;border-radius:10px;">:baby_bottle: **[Tutoriels]**</span> <span style="background:#aaddaa;padding:5px;border-radius:10px;">:gear: **[Guide pratique]**</span> <span style="background:#ccccee;padding:5px;border-radius:10px;">:book: **[Référence]**</span> <span style="background:#eeccee;padding:5px;border-radius:10px;">:sparkles: **[Concepts]**</span>