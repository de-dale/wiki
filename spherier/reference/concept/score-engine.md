---
title: Système de Score sur 1d20
description: 
published: true
date: 2020-04-07T14:05:33.108Z
tags: 
---

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

## Types de test

### Tests de réussite

Le test le plus basique. On confronte un lancer de dés à un socre et on regarde s'il s'agit d'une réussite.
Exemple de test de réussite: 

    [Dressage](10)
    
où :
- `[Dressage]` : Compétence utilisée dans le test 
- ` ` : Limite applicable 
- `10` : DD

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