---
title: Concept
description: 
published: true
date: 2020-04-07T14:25:17.281Z
tags: 
---

# Test de Compétence 

Lorsque vous faites appel à vos **[Capacités](https://trello.com/c/EUJsvYrZ)** pour accomplir quelque chose de difficile, d’extraordinaire ou de risqué, afin de déterminer si vous réussissez ou si vous échouez, vous effectuez un **Test de Compétence**.
Vous utilisez votre **[Compétence](https://trello.com/c/udzuobSo)**, et récupérez votre **Maîtrise** et votre ~~Expertise~~ **Limite**. Vous lancez alors les dés, et vous cherchez à obtenir un résultat suffisant pour égaler ou surpasser le **Degré de Difficulté**, abrégé en "**DD**", et parfois appelé "_Seuil_".

Si le résultat des dés est supérieur ou égal au **DD**, le test est une **Réussite**, sinon, c'est un **Échec**. 

Le mode du calcul du résultat, et le degré de difficulté, dépendent du système de jeu que vous choisissez d'utiliser.

## Limite

La **Limite** sur un **Test de Compétence** correspond au plafond du résultat
qu'il est possible d'obtenir sur ce test.

Chaque **Compétence** possède sa propre La **Limite**.

> **NB:**
La **Limite** permet de pallier à un manque d'équilibrage dans le jeu, en limitant la puissance des joueurs par des palliers.
Elle est peut-être amenée à disparaître ; il faut voir comment les joueurs font évoluer leurs personnages avec/sans le plafond de puissance.

> Deux options envisagées :
> - ( ) Limiter le nombre de dés lancés
> - (x) Limiter le nombre de succès (cf.SR5)

## Marge

Une Marge est la différence entre le résultat d'un **Test de Compétence**, et le **DD** associé. Elle traduit le degré de réussite ou d'échec d'un personnage, sur l'action entreprise et sera toujours positive. 

Si le test est une réussite, on parlera de "**Marge de Réussite**", sinon il s'agira de la "**Marge d'Échec**".

# Systèmes de jeu

- [Succès *Compter le nombre de succès sur une brouette de d6*](success-engine)
- [Score *Compte le score total sur 1d20 et ses modificateurs*](score-engine)
{.links-list}

<a id="success-engine"></a>
##  d6 - Dés à succès

> Système SR5 like
> **A ma préférence**

> **SR5:**
_Chaque fois que vous lancez les dés, vous cherchez à obtenir assez de succès pour égaler ou surpasser un seuil, qui est le nombre de succès dont vous avez besoin pour faire ce que vous essayez de faire._

Pour effectuer un **Test de Compétence**, on constitue la **Réserve de Dés**, c'est à dire, le nombre de dés à lancer.
Ce nombre est égal au **degré de maîtrise**, de la compétence utilisée, ajusté par les différents modificateurs, bonus et malus.

> **RD** = <Compétence> + Bonus - Malus

Un **succès** correspond à un 5 ou un 6 sur le résultat d'un dé. On compare ensuite le nombre de succès au DD, pour déterminer si le test est une réussite ou un échec.

En résumé :
> **[Compétence]** = succès{5,6}(<Compétence> + Bonus - Malus × d6) 

> Le DD pour une action:
> - **Facile:** 1
> - **Moyenne:**          2
> - **Difficile:**             3
> - **Très difficile:**    4

> Système D&D like. Cest le système que l'on utilise pour jouer à D&D3.5 et Pathfinder.

> _Chaque fois que vous lancez les dés, vous cherchez à obtenir un score suffisant pour égaler ou surpasser un seuil, correspondant au total minimal à atteindre pour réussir ce que vous essayez de faire._

Dans ce système, le personnage lance 1d20, additionne  son degré de maîtrise dans la compétence utilisée, ses bonus, soustrait ses malus,  puis compare le résultat au degré de difficulté. S'il a plus, son action aboutit,  sinon elle échoue. 

En résumé :

 **[Compétence]** = somme (1d20 + "<Compétence> + Bonus - Malus") 

> Une échelle de DD pour une action:
>- **Facile:** 5
>- **Moyenne:** 10
>- **Difficile:** 15
>- **Très difficile:** 20


# Types de tests

## Tests de réussite

Le test le plus basique. On confronte un lancer de dés à un socre et on regarde s'il s'agit d'une réussite.

Exemple : 

    [Dressage](10)
    
où :
- `[Dressage]` : Compétence utilisée dans le test 
- ` ` : Limite applicable 
- `10` : DD

## Tests opposés

Test où deux acteurs confrontent leiurs compétences respective, pour déterminer qui a la plus grosse.

Exemple :

    [Bluff][Psychologie]
       
où :
- `[Bluff]` : Compétence utilisée dans le test 
- ` ` : Limite applicable 
- `[Psychologie]` : Compétence utilisée par l'opposant
- ` ` : Limite appliquée à l'opposant


## Tests étendus

Tests où l'on cherche à accomplir quelque chose en plusieurs fois, sur la durée.

Exemple:

    [Mecanique](2, 10, 1h)
    
où :
- `[Mecanique]` : Compétence utilisée dans le test 
- ` ` : Limite applicable 
- `2` : DD minimal à atteindre pour faire avancer le score total
- `10` : Score total à atteindre à l'issue du test 
- `1h` : Intervalle entre deux tests 

**Système à succès**
A chaque test consécutif, on retire un dé de la réserve. 
Une fois que tous les dés sont retirés, on ne peut plus poursuivre le test.

**Système au score de d20**
A chaque test consécutif, on applique un malus de -1 sur le prochain jet.
Une fois que tous la somme des malus égale le degré de maîtrise du personnage dans la compétence utilisée, on ne peut plus poursuivre le test. 
> Cf. Artisanat 

## Tests d'équipe
WIP
>  **Test de réussite**
> `[Dressage](2)`
> Compétence                   Limite         DD
> utilisée dans                applicable
> le test
> **+1 par succès        +1 par assistant avec
> des assistants            1 succès ou plus**


### Tests d'équipe

>  **Test de réussite**
> `[Dressage](32)`
> Compétence                   Limite         DD
> utilisée dans                applicable
> le test
> **+2 par succès        +1 par assistant avec
> des assistants            1 succès ou plus**