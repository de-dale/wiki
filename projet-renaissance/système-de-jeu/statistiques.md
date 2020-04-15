---
title: Statistiques générales
description: 
published: true
date: 2020-04-15T11:44:36.600Z
tags: 
---

# Récapitulatif
> Les personnages disposent des statistiques suivantes à leur création. Les pouvoirs et capacités qu'il sélectionnent peuvent venir modifier ces quantités :
**PA : 6**
**PR : 1**
**PM : 4**
**Santé : 3**
**PV : 30**
**PV tempo : Max 10**
{.is-warning}

# Actions
Pour plus de détails sur la mécanique d'action : [Organisation d'un affrontement](http://de-dale.hd.free.fr/fr/projet-renaissance/syst%C3%A8me-de-jeu/actions).
## Points d'Action
Lors d'une rencontre, les actions des personnages sont régulées. Ils ne peuvent accomplir qu'un certain nombre d'actions par tour, chacune de ces actions consommant des Points d'Action (PA).
Un personnage dispose de **6 PA** à sa création.
## Points de Réaction
De même que pour les actions, ils ne peuvent réagir à une action qu'une nombre limité de fois à chaque tour en utilisant des Points de Réaction (PR).
Un personnage dispose de **1 PR** à sa création.
## Point de Mouvement
Enfin, lorsqu'un personnage choisit de faire une action de mouvement pour se déplacer, il peut se déplacer d'un nombre maximum de case égal à ses Points de Mouvement (PM).
Un personnage dispose de **1 PM** à sa création.
# Vie
La vie d'un personnage est sa ressource la plus précieuse. Si un personnage peut mourir, il a plusieurs statistiques qui représentent sa résilience naturelle à la mort. Elles se distinguent en 2 catégories : 
* Résilience temporaire : Elle commence à 0 et est simple à générer pendant l'aventure, mais présente une limite dans le temps.
* Résilience vitale : Elle commence au maximum et est difficile à régénérer en dehors des Repos. Elle est par contre permanente.

Lorsqu'un personnage subit des dégâts, il perd d'abord de sa résilience temporaire puis de la vitale. Elles sont présentées ci-dessous dans l'ordre d'utilisation, de la plus éphémère et la moins critique, à la plus pérènne et la plus critique. Par contre, lorsqu'il est précisé que les dégâts ne concernent qu'un résilience, seule celle-ci est affectée.
> **Exemple :**
Alice dispose de 6 PV temporaires, 30 PV et 3 Points de Santé.
Elle subit une première attaque qui lui inflige 3 dégâts. Elle retire donc 3 PV temporaires. *Il lui reste 3 PV tempoaires.*
Une seconde attaque la touche avec un effet particulier : elle inflige 5 dégâts aux PV temporaires puis elle inflige 1 dégât. Alice retire donc les 3 PV temporaires qui lui restent, mais ne touche pas à ses PV sur cette partie de l'attaque. Elle retire ensuite 1 PV car elle n'a plus de PV temporaire. *Elle dispose donc de 29 PV.*
C'est à elle de jouer. Elle utilise une première capacité qui lui génère 2 PV temporaires puis une seconde qui lui demande de perdre 3 PV pour génerer 9 d'Absorption. Comme celle-ci précise le type de résilience impactée, elle ne peut pas utiliser ses PV temporaires pour amoindrir l'effet. Elle perd donc 3 PV. *Elle dispose donc de 9 d'Absorption, 2 PV tempoaires et 26 PV.*
Une 3 attaque la touche violemment et lui inflige 10 dégâts. Alice retire donc ses 9 d'Absorption et 1 PV temporaire. *Elle finit le tour avec 1 PV temporaire et 26 PV.*
{.is-info}

Les chiffres donnés ci-dessous sont ceux dont disposent un personnage à sa création et peuvent être modifiés par  leurs objets, capacités, entraînements et ainsi de 
## Résilience temporaire
### Absorption
L'Aborption est la première couche de résilience. Elle représente une protection très éphèmère (quelques secondes) et généralement puissante. Elle ne dure que jusqu'à la fin du tour. Les personnages ne disposent pas d'Absorption naturellement, elle se génère au travers de leurs capacités.
### Points de vie temporaires
Les PV temporaires représentent la seconde couche de résilience. Ils durent plus longtemps que l'Absorption (quelques minutes) mais sont plus limités. Les PV temporaires durent jusqu'à ce que le temps passe. Les personnages disposent d'un maximum de 10 PV temporaires et commencent leur journée d'aventure à 0, mais pourront en générer grâce à leurs capacités. Les PV temporaires gagnés au dela de cette limite sont perdus.
## Résilience vitale
### Points de vie
Les PV sont la principale source de résilience des personnages. Ils ont pour objectif de protéger les Points de Santé et de mesurer dans quelle forme est le personnage.
Les personnages disposent d'un maximum 30 PV de base et commencent leur journée d'aventure au maximum de leurs PV. Les PV se régènèrent notamment lors des Repos courts (1d6 PV) et des Repos longs (jusqu'à leur maximum).
Lorsque les PV d'un personnage tombent à 0 et perd 1 Point de Santé automatiquement. Tant qu'il est à 0 PV, il est KO et ne peut agir.
**Etat blessé**
Lorsqu'un personnage a perdu 50% ou plus de ses PV maximaux, il est alors considéré comme blessé. C'est un état visible donc ses alliés et ennemis le savent immédiatement. Certaines capacités sont plus efficaces sur des personnages blessés, notamment provenant des bêtes sauvages, il est donc dangereux de rester dans cet état en territoire hostile.
Le seuil auquel un personnage est considéré comme blessé peut être modifié comme pour le reste de ses statisitques, mais il ne peut jamais dépasser ses **PV max - 1**.
### Points de Santé
Les Points de Santé sont la dernière barrière d'un personnage. Il est difficile de s'en prendre directement à eux, sauf avec des effets qui devraient directement tuer un personnage.
Les personnages disposent de base 3 Points de Santé qui se régénèrent après un Repos long uniquement. Ils ne se décomptent pas comme les autres résiliences ; un personnage perd 1 Point de Santé dans les cas suivants uniquement :
* Ses PV tombent à 0
* Il est KO et subit des dégâts non-fixes (quelque soit le montant de dégâts)

Cela signifie qu'une fois qu'un personnage est à terre avec 0 PV, il faudra encore 2 attaques sur lui pour l'achever. Il est possible de le soigner dans l'intervale pour lui rendre des PV, mais s'il repasse à 0 PV, il perdra de nouveau 1 point de Santé.

Lorsqu'un personnage tombe à 0 Point de Santé, il tombe dans le coma. Il ne pourra plus reprendre l'aventure avant d'en être sorti, ce qui prend longtemps et demande des soins suivis généralement incompatible avec un bivouac. Il faut considérer que le personnage n'est plus en capacité à poursuivre l'aventure.

# Réduction de dégâts
Les personnages vont subir toute sorte d'attaque durant leur aventure
