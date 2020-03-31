---
title: Règles de base
description: 
published: true
date: 2020-03-31T12:48:00.243Z
tags: 
---

# Carte

Tout élément du Sphérier, peut être représenté par une **Carte**.
Une **Carte** est un élément de jeu, qui présente les éléments nécessaires et suffisants, pour expliquer un point de règle.

Physiquement, elle se matérialise par une carte à jouer. 

Afin de favoriser la concision, les cartes utiliseront au maximum, des **[Mots-clés](https://trello.com/c/R9XMDT9T)** et des **[Symboles](https://trello.com/c/R9XMDT9T)**.

## Mot clé 

Un mot-clé est un terme clair et précis, qui correspond à une unique définition, ou un unique point de règle.

Un mot clé est défini sur une carte.

La carte en question devrait être au plus proche de celui qui l'utilise : elle doit être dans le Sphérier du personnage qui en a besoin. 

**Conception du Sphérier**

Lorsqu'un terme utilisé dans un point de règle n'est pas clair, il faut l'expliquer et le définir comme un mot-clé, sur une carte dédiée.

**Glossaire**

Les mots-clés sont référencés dans le [Glossaire](https://trello.com/c/2sDoyFea) 

## Symbole

Un symbole est l'unique représentation graphique d'un mot-clé.

## Légende

**[Mot-clé]()**
Les mot-clés sont affichés en gras, avec un lien vers leur définition.

**`[Compétence]`**
Un jet de la compétence précisée.

**`R°`**
Une réaction

**`A°`**
Une action

**`[Compétence](DD)`**
Jet de compétence nécessitant au moins `DD` succès. (DD pour degré de difficulté).

**`[Compétence][Compétence du defenseur]`**
Jets de compétence opposés.

**`<Compétence>`**
Valeur brute de la Compétence

Idées :

> **+3** en **Volonté**
> **Volonté<+3>**
> **Limite<12>** en **Volonté**.

# Concept

## Test de Compétence 

Lorsque vous faites appel à vos **[Capacités](https://trello.com/c/EUJsvYrZ)** pour accomplir quelque chose de difficile, d’extraordinaire ou de risqué, afin de déterminer si vous réussissez ou si vous échouez, vous effectuez un **Test de Compétence**.

Vous utilisez votre **[Compétence](https://trello.com/c/udzuobSo)**, et récupérez votre **Maîtrise** et votre ~~Expertise~~ **Limite**. Vous lancez alors les dés, et vous cherchez à obtenir un résultat suffisant pour égaler ou surpasser le **Degré de Difficulté**, abrégé en "**DD**", et parfois appelé "_Seuil_".

Si le résultat des dés est supérieur ou égal au **DD**, le test est une **Réussite**, sinon, c'est un **Échec**. 

Le mode du calcul du résultat, et le degré de difficulté, dépendent du système de jeu que vous choisissez d'utiliser.

### Limite

La **Limite** sur un **Test de Compétence** correspond au plafond du résultat
qu'il est possible d'obtenir sur ce test.

Chaque **Compétence** possède sa propre La **Limite**.

> **NB:**
La **Limite** permet de pallier à un manque d'équilibrage dans le jeu, en limitant la puissance des joueurs par des palliers.
Elle est peut-être amenée à disparaître ; il faut voir comment les joueurs font évoluer leurs personnages avec/sans le plafond de puissance.

> Deux options envisagées :
> - ( ) Limiter le nombre de dés lancés
> - (x) Limiter le nombre de succès (cf.SR5)

### Marge

Une Marge est la différence entre le résultat d'un **Test de Compétence**, et le **DD** associé. Elle traduit le degré de réussite ou d'échec d'un personnage, sur l'action entreprise et sera toujours positive. 

Si le test est une réussite, on parlera de "**Marge de Réussite**", sinon il s'agira de la "**Marge d'Échec**".

# d6 - Dés à succès

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

Le DD pour une action:
> **Facile:**                1
> **Moyenne:**          2
> **Difficile:**             3
> **Très difficile:**    4

## Limite

La limite impose un plafond sur le nombre de succès que l'on obtient sur le **Test de Compétence**. Si le nombre de succès dépasse la **Limite**, les succès excédentaires sont ignorés. 

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

# d20

> Système D&D like. Cest le système que l'on utilise pour jouer à D&D3.5 et Pathfinder.

> _Chaque fois que vous lancez les dés, vous cherchez à obtenir un score suffisant pour égaler ou surpasser un seuil, correspondant au total minimal à atteindre pour réussir ce que vous essayez de faire._

Dans ce système, le personnage lance 1d20, additionne  son degré de maîtrise dans la compétence utilisée, ses bonus, soustrait ses malus,  puis compare le résultat au degré de difficulté. S'il a plus, son action aboutit,  sinon elle échoue. 

En résumé :
> **[Compétence]** = somme (1d20 + "<Compétence> + Bonus - Malus") 

Le DD pour une action:
> **Facile:**                 5
> **Moyenne:**         10
> **Difficile:**            15
> **Très difficile:**   20

### Tests et limites

>  **Test de réussite**
> **`[Dressage](10)`**
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
> `[Mecanique](50, 1h)`
> Compétence                    Limite           Score total, 
> utilisée dans                 applicable       Intervalle entre
> le test                                                       deux tests 

A chaque test consécutif, on applique un malus de -1 sur le prochain jet.
Une fois que tous la somme des malus égale le degré de maîtrise du personnage dans la compétence utilisée, on ne peut plus poursuivre le test. 
> Cf. Artisanat 

### Tests d'équipe

>  **Test de réussite**
> `[Dressage](32)`
> Compétence                   Limite         DD
> utilisée dans                applicable
> le test
> **+2 par succès        +1 par assistant avec
> des assistants            1 succès ou plus**