---
title: Concept
description: 
published: true
date: 2020-04-07T14:09:54.673Z
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

# Types de tests

## Types de tests

### Tests et limites

>  **Test de réussite**
> `[Dressage](2)`
> Compétence                  Limite          DD
> utilisée dans               applicable
> le test 

### Tests opposés

>  **Tests opposés**
> `[Dressage][Dressage]`
> Compétence                  Limite          Compétence
> utilisée dans               applicable         opposée
> le test 

### Tests étendus

> **Réussite de test étendu**
> `[Mecanique](10, 1h)`
> Compétence                    Limite           Score total, 
> utilisée dans                 applicable       Intervalle entre
> le test                                                       deux tests 

A chaque test consécutif, on retire un dé de la réserve. 
Une fois que tous les dés sont retirés, on ne peut plus poursuivre le test. 

### Tests d'équipe

>  **Test de réussite**
> `[Dressage](2)`
> Compétence                   Limite         DD
> utilisée dans                applicable
> le test
> **+1 par succès        +1 par assistant avec
> des assistants            1 succès ou plus**

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
