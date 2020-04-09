---
title: Mécanique de base
description: 
published: true
date: 2020-04-09T19:38:42.088Z
tags: 
---

# Mécanique de base

Vos personnages sont des aventuriers, qui utiliseront leurs **[Capacités][][][Capacités.trello]** pour accomplir quelque chose de difficile, d’extraordinaire ou de risqué. Lorsque que le succès n'est pas garanti, vous effectuez un **Test**, dont le résultat déterminera si vous réussissez ou si vous échouez dans votre entreprise.

Vous utilisez votre **[Compétence][][][Compétence.trello]**, et récupérez votre **Maîtrise** et votre **Limite**.

Vous lancez alors les dés, et vous cherchez à obtenir un résultat suffisant pour égaler ou surpasser le **Degré de Difficulté**, abrégé en "**DD**", et parfois appelé "_Seuil_".
Si le résultat des dés est supérieur ou égal au **DD**, le test est une **Réussite**, sinon, c'est un **Échec**. 

Le mode du calcul du résultat, et le degré de difficulté, dépendent du **système de jeu** que vous choisissez d'utiliser.
- [Succès *Compter le nombre de succès sur une brouette de d6*](#success-engine)
- [Score *Compter le score total sur 1d20 et ses modificateurs*](#score-engine)

{.links-list}

## Limite

La **Limite** sur un **Test de Compétence** correspond au plafond du résultat
qu'il est possible d'obtenir sur ce test.

Chaque **Compétence** possède sa propre **Limite**.

> **Note d'équilibrage:** _(à déplacer dans la partie "Discussion" de la Doc)_
> La **Limite** permet de pallier à un manque d'équilibrage dans le jeu, en limitant la puissance des joueurs par des palliers.
Elle est peut-être amenée à disparaître ; il faut voir comment les joueurs font évoluer leurs personnages avec/sans le plafond de puissance.
> 
> Deux options envisagées :
> - [ ] Limiter le nombre de dés lancés
> - [x] Limiter le nombre de succès (cf.SR5)


## Marge

La **Marge** est la différence entre le résultat d'un **Test de Compétence**, et le **DD** associé. Elle traduit le degré de réussite ou d'échec d'un personnage, sur l'action entreprise et sera toujours positive. 

Si le test est une réussite, on parlera de "**Marge de Réussite**", sinon il s'agira de la "**Marge d'Échec**".

# Systèmes de jeu

<a id="success-engine"></a>
##  d6 - Dés à succès

_**Shadowrun:** Chaque fois que vous lancez les dés, vous cherchez à obtenir assez de succès pour égaler ou surpasser un seuil, qui est le nombre de succès dont vous avez besoin pour faire ce que vous essayez de faire._

Pour effectuer un **Test de Compétence**, on constitue la **Réserve de Dés**, c'est à dire, le nombre de dés à lancer.
Ce nombre est égal au **degré de maîtrise**, de la compétence utilisée, ajusté par les différents modificateurs, bonus et malus.

> **RD** = <Compétence> + Bonus - Malus

L’objectif quand on lance les dés est d’obtenir des **succès**. Un succès correspond à un 5 ou un 6 sur le résultat d'un dé.
Le nombre de succès obtenus est comparé au DD, pour déterminer si le test est une réussite ou un échec.


En résumé :

    [Compétence] = succès{5,6}(<Compétence> + Bonus - Malus × d6)

> Une échelle de DD pour une action:
> - **Facile:** 1
> - **Moyenne:** 2
> - **Difficile:** 3
> - **Très difficile:** 4
{.is-info}

<a id="score-engine"></a>
## d20 - Score de dé

_**Donjon&Dragons:** Chaque fois que vous lancez les dés, vous cherchez à obtenir un score suffisant pour égaler ou surpasser un seuil, correspondant au total minimal à atteindre pour réussir ce que vous essayez de faire._

Dans ce système, le personnage lance 1d20, additionne  son degré de maîtrise dans la compétence utilisée, ses bonus, soustrait ses malus,  puis compare le résultat au degré de difficulté. S'il a plus, son action aboutit,  sinon elle échoue. 

En résumé :

    [Compétence] = somme (1d20 + "<Compétence> + Bonus - Malus") 

> Une échelle de DD pour une action:
> - **Facile:** 5
> - **Moyenne:** 10
> - **Difficile:** 15
> - **Très difficile:** 20
{.is-info}


# Types de tests

## Tests simple

Le test le plus basique : le lancer de dés est confronté au DD et on regarde s'il s'agit d'une réussite ou d'un échec. 

Exemple : 

    [Dressage](10)
    
où :
- `[Dressage]` : Compétence utilisée dans le test 
- `10` : DD

## Tests opposés

Test où deux acteurs confrontent leiurs compétences respective, pour déterminer qui a la plus grosse.

Exemple :

    [Bluff][Psychologie]
       
où :
- `[Bluff]` : Compétence utilisée dans le test 
- `[Psychologie]` : Compétence utilisée par l'opposant

## Tests étendus

Tests où l'on cherche à accomplir quelque chose en plusieurs fois, sur la durée.

Exemple:

    [Mecanique](2, 10, 1h)
    
où :
- `[Mecanique]` : Compétence utilisée dans le test 
- `2` : DD minimal à atteindre pour faire avancer le score total
- `10` : Score total à atteindre à l'issue du test 
- `1h` : Intervalle entre deux tests 

**Système à succès**
A chaque test consécutif, on retire un dé de la réserve. 
Une fois que tous les dés sont retirés, on ne peut plus poursuivre le test.

**Système au score de d20**
A chaque test consécutif, on applique un malus cummulatif de -1 sur le prochain jet.
Une fois que le malus cumulé égale le degré de maîtrise du personnage dans la compétence utilisée, on ne peut plus poursuivre le test. 

## Tests d'équipe

Tests où plusierus personnage cherchent à réussir ensembe une action.
On désigne un "Leader", les autres personnage seront alors les "Assistants".

Exemple:

    [Rituel satanique](10,  2)
    
où :
- `[Rituel satanique]` : Compétence utilisée dans le test 
- `10` : DD à atteindre par le Leader pour réussir son jet
- `2` : DD à atteindre par un Assistant pour "Réussir à aider correctement"
- '?' : Nombre maximum d'Assistants 
- '?' : Nombre minimal de  d'Assistants 

**Système à succès**
On ajoute à la réserve de dé du Leader, tous les succès excedentaires des Assistants.
La Limite du Leader pour ce test, augmente 1 par Assistant ayant 1 réussi à aider correctement.

**Système au score de d20**
On ajoute +2 par assistant ayant réussi à aider correctement.
La Limite du Leader pour ce test, augmente de 1 par Assistant ayant réussi à aider correctement.

[Capacités]: /sphérier/référence/capacités
[Capacités.trello]: https://trello.com/c/EUJsvYrZ
[Compétence]: /sphérier/référence/compétences
[Compétence.trello]: https://trello.com/c/udzuobSo