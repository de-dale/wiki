---
title: Corpus Essentiel
description: Règles nécessaires pour comprendre le Sphérier, en dépit de tout le découpage en cartes
published: true
date: 2021-04-27T13:32:59.050Z
tags: premiers pas, règles
editor: markdown
dateCreated: 2020-04-07T13:55:23.186Z
---

# Mécanismes de jeu
## Lancers de dés

Vos personnages sont des aventuriers, qui utiliseront leurs **[Capacités][]** pour accomplir quelque chose de difficile, d’extraordinaire ou de risqué. Lorsque que le succès n'est pas garanti, vous effectuez un **Test**, dont le résultat déterminera si vous réussissez ou si vous échouez dans votre entreprise.

Vous utilisez votre **[Compétence][]**, et récupérez votre **Maîtrise** et votre **Limite**. 

Vous lancez alors les dés, et vous cherchez à obtenir un résultat suffisant pour égaler ou surpasser le **Degré de Difficulté**, abrégé en "**DD**", et parfois appelé "*Seuil*".
Si le résultat du lancer de dés est supérieur ou égal au **DD**, le test est une **Réussite**, sinon, c'est un **Échec**. 

Le mode du calcul du résultat, et le degré de difficulté, dépendent du **système de jeu** que vous choisissez d'utiliser.
  
### Marge

La **Marge** est la différence entre le résultat d'un **Test de Compétence**, et le **DD** associé. Elle traduit le degré de réussite ou d'échec d'un personnage, sur l'action entreprise et sera toujours positive. 

Si le test est une réussite, on parlera de "**Marge de Réussite**", sinon il s'agira de la "**Marge d'Échec**".

## <a id="dice-engines"></a> Systèmes de jeu

Le Sphérier devrait pouvoir encaisser deux systèmes de jeu en parallèle

- [Succès *Compter le nombre de succès sur une brouette de d6*](#dice-engines)
- [Score *Compter le score total sur 1d20 et ses modificateurs*](#dice-engines)
{.links-list}

Les deux sytèmes sont détaillés ci-dessous

### Systèmes de jeu {.tabset}

<a id="success-engine"></a>
#### d6 - Dés à succès

> **Shadowrun-like**
Chaque fois que vous lancez les dés, vous cherchez à obtenir assez de succès pour égaler ou surpasser un seuil, qui est le nombre de succès dont vous avez besoin pour faire ce que vous essayez de faire.

Pour effectuer un **test**, on constitue la **Réserve de Dés**, c'est à dire, le **nombre de dés à lancer**.
Ce nombre est égal au **degré de Maîtrise**, de la **[Compétence][]** utilisée, ajusté par les différents modificateurs, bonus et malus.

    Réserve de Dés = <Compétence> + Bonus - Malus

L’objectif quand on lance les dés est d’obtenir des **succès**. Un succès correspond à un 5 ou un 6 sur le résultat d'un dé.
Le nombre de succès constitue le résultat du lancer.
Ce résultat est plafonné par la **Limite** de la **[Compétence][]** utilisée. 
Dans ce système, la **Limite** est le nombre **maximal de succès** que l'on peut objtenir sur un lancer de dés, en tenant compte des bonus et malus.

En résumé :

    [Compétence] = succès{5,6}("<Degré de Maîtrise> + Bonus - Malus" × d6)
    max [Compétence] = <Limite>
    
Si le résultat du lancer de dés est supérieur ou égal au **DD**, le test est une **Réussite**, sinon, c'est un **Échec**. 

> Une échelle de DD pour une action:
> - **Facile:** 1
> - **Moyenne:** 2
> - **Difficile:** 3
> - **Très difficile:** 4
{.is-info}


<a id="score-engine"></a>
#### d20 - Score de dé

>**Donjon&Dragons-like**
Chaque fois que vous lancez les dés, vous cherchez à obtenir un score suffisant pour égaler ou surpasser un seuil, correspondant au total minimal à atteindre pour réussir ce que vous essayez de faire.

Dans ce système, pour effectuer un **test**, le personnage lance 1d20, additionne son **degré de maîtrise** de la compétence utilisée, et ajuste le résultat avec différents modificateurs, bonus et malus.
La somme totale constitue le résultat du lancer de dés.
Ce résultat est plafonné par la **Limite** de la **[Compétence][]** utilisée. 
Dans ce système, on additionne **20 + Limite** pour connaître le **résultat maximal** que peut obtenir sur un lancer de dés.

En résumé :

    [Compétence] = somme (1d20 + "<Degré de Maîtrise> + Bonus - Malus")
    max [Compétence] = 20 + <Limite>

Si le résultat du lancer de dés est supérieur ou égal au **DD**, le test est une **Réussite**, sinon, c'est un **Échec**. 

> Une échelle de DD pour une action:
> - **Facile:** 5
> - **Moyenne:** 10
> - **Difficile:** 15
> - **Très difficile:** 20
{.is-info}

## Types de tests

#### Tests simple

Le test le plus basique : le lancer de dés est confronté au DD et on regarde s'il s'agit d'une réussite ou d'un échec. 

##### Exemple
##### Déclinaisons {.tabset}

###### d6 - Dés à succès

    [Dressage](2)
    
où :
- `[Dressage]` : Compétence utilisée dans le test 
- `2` : DD

###### d20 - Score de dé

    [Dressage](10)
    
où :
- `[Dressage]` : Compétence utilisée dans le test 
- `10` : DD

#### Tests opposés

Test où deux acteurs confrontent leurs compétences respective, pour déterminer qui a la plus grosse.

##### Exemple
##### Déclinaisons {.tabset}

###### d6 - Dés à succès

    [Bluff][Psychologie]
       
où :
- `[Bluff]` : Compétence utilisée dans le test 
- `[Psychologie]` : Compétence utilisée par l'opposant

###### d20 - Score de dé

    [Bluff][Psychologie]
       
où :
- `[Bluff]` : Compétence utilisée dans le test 
- `[Psychologie]` : Compétence utilisée par l'opposant

#### Tests étendus

Tests où l'on cherche à accomplir quelque chose en plusieurs fois, sur la durée.

##### Exemple
##### Déclinaisons {.tabset}

###### d6 - Dés à succès

    [Mecanique](2, 10, 1h)
    
où :
- `[Mecanique]` : Compétence utilisée dans le test 
- `2` : DD minimal à atteindre pour faire avancer le score total
- `10` : Score total à atteindre à l'issue du test 
- `1h` : Intervalle entre deux tests 

A chaque test consécutif, on retire un dé de la réserve. 
Une fois que tous les dés sont retirés, on ne peut plus poursuivre le test.

###### d20 - Score de dé

    [Mecanique](10, 50, 1h)
    
où :
- `[Mecanique]` : Compétence utilisée dans le test 
- `10` : DD minimal à atteindre pour faire avancer le score total
- `50` : Score total à atteindre à l'issue du test 
- `1h` : Intervalle entre deux tests 

A chaque test consécutif, on applique un malus cummulatif de -1 sur le prochain jet.
Une fois que le malus cumulé égale le degré de maîtrise du personnage dans la compétence utilisée, on ne peut plus poursuivre le test. 

#### Tests d'équipe

Tests où plusieurs personnages cherchent à réussir ensemble une action.
Ils désignent le **"Leader"** du test, les autres personnage seront alors les **"Assistants"**.

##### Exemple
##### Déclinaisons {.tabset}

###### d6 - Dés à succès

    [Rituel satanique](10,  2)
    
où :
- `[Rituel satanique]` : Compétence utilisée dans le test 
- `10` : DD à atteindre par le Leader pour réussir son jet
- `2` : DD à atteindre par un Assistant pour "Réussir à aider correctement"
- '?' : Nombre maximum d'Assistants 
- '?' : Nombre minimal de  d'Assistants 

Tous les succès excedentaires des Assistants sont ajoutés à la réserve de dé du Leader.
La Limite du Leader pour ce test, augmente 1 par Assistant ayant réussi à aider correctement.

###### d20 - Score de dé

    [Rituel satanique](50,  10)
    
où :
- `[Rituel satanique]` : Compétence utilisée dans le test 
- `50` : DD à atteindre par le Leader pour réussir son jet
- `10` : DD à atteindre par un Assistant pour "Réussir à aider correctement"
- '?' : Nombre maximum d'Assistants 
- '?' : Nombre minimal de  d'Assistants 

On ajoute +2 par assistant ayant réussi à aider correctement.
La Limite du Leader pour ce test, augmente de 1 par Assistant ayant réussi à aider correctement.

# Capacités

Les **Capacités** constituent l'ensemble des **options d'action** dont dispose un personnage pour une **Phase de Jeu** donnée.

Les capacités peuvent être **Actives**, ou **Passive**. Lorsqu'elles sont utilisées, elles déclenchent un ou plusieurs **[Effet][]**. L'efficacité d'une capacité est indexée sur la compétence qui lui est associée.

En résumé, une Capacité possède :
- Un Nom
- Une Phase où elle prend effet
- Une compétence associée
- Un Coût en Point d'actions
- un ou plusieurs effets

Une capacité est notée ainsi :

    Capacité<Compétence, Phase>

**Exemple :** 

    Coup d'estoc<Armes(Epées), Combat>

> Consulter aussi la [Liste des Capacités][]
{.is-info}

Une capacité ne prend effet que dans une et une seule **Phase de jeu** donnée. Néanmoins, il existe des capacités de même nom, qui prenent effet dans des Phases de jeu différentes.

**Exemple :** 

    Invisibilité<Furtivité, Combat>
    Invisibilité<Furtivité, Exploration>
    
> **Remarque**
Les **Capacités** déterminent les **Compétences** qu'un personnage possède.
Si un personnage possède une **Capacité**, il possède alors un degré de maîtrise dans la **Compétence** associée.
{.is-info}


### Wordings
Les Capacités peuvent être utilisées :
- Par une action, en activant une Capacité
- En réponse à un adversaire
- En réaction à une action d'attaque



## Capacités Actives

Une **Capacité Active** demande au moins une **Action** ou une **Réaction**, pour déclancher ses effets. Cela implique un choix actif de la part du joueur.

Souvent, les effets d'une **Capacité Active** sont limités dans le temps.

Une Capacité Active consomme généralement des **Point d'Action**, (ressources des personnages pouvant agir, et ré-générée à chaque fois que le "temps passe" (ex: chaque tour de combat)). 

## Capacités Passive

Une **Capacité Passive** applique continuellement ses effets, tant que ses conditions d'activation s'appliquent.

Souvent une **Capacité Passive** ne s'applique qu'au personnage la possédant.

# Compétences

Une **Compétence** est l'indice de la maîtrise et de l'efficacité du **[Personnage][]**, dans l'usage de ses **[Capacités][]**.

Si les **[Capacités][]** déterminent les actions que peut entreprendre un **[Personnage][]**, les **Compétences** déterminent si un personnage accomplit ce qu'il entreprend ou échoue en essayant.

Une Compétence est notée ainsi :

    Compétence<Maîtrise, Limite>

**Exemple :** 

    Bluff<+10, 6>

> **Remarque**
Si un **Personnage** possède une **Compétence**, il peut l'exploiter dans au moins une **Capacité** qu'il possède.
{.is-info}

## Maîtrise

**Maîtrise**, ou ***Degré de Maîtrise***, reflète l'aisance du personnage à réussir ce qu'il entreprend ; plus elle est élevée, plus un personnage réussira fréquement.

Sur un **[Test de Compétence][core]**, il s'agit de la valeur numérique corresponand au bonus principal. Elle utilisée différement en fonction du système de jeu :

- **Succès(d6)**
Le nombre de dés à lancer

- **Score(d20)**
Le bonus sur le d20

Chaque **Compétence** possède sa propre **Degré de Maîtrise**.

## Limite

La **Limite** reflète l'expertise d'un personnage, et son aptitude à réussir des actions hors normes.

Sur un **[Test de Compétence][core]**, elle correspond au plafond du résultat qu'il est possible d'obtenir. Elle utilisée différement en fonction du système de jeu :

- **Succès(d6)**
la Limite est le nombre maximal de succès que l'on peut obtenir sur un lancer de dés

- **Score(d20)**
Le résulat du lancer de dé est plafonné à `20 + Limite`.

Chaque **Compétence** possède sa propre **Limite**.

> **Note d'équilibrage:** _(à déplacer dans la partie "Discussion" de la Doc)_
> La **Limite** permet de pallier à un manque d'équilibrage dans le jeu, en limitant la puissance des joueurs par des palliers.
Elle est peut-être amenée à disparaître ; il faut voir comment les joueurs font évoluer leurs personnages avec/sans le plafond de puissance.
> 
> Deux options envisagées :
> - [ ] Limiter le nombre de dés lancés
> - [x] Limiter le nombre de succès (cf.SR5)

## Capacités génériques aux Compétences

### Trait de compétence
TODO : retrouver de que je voulais mettre ici

### [Maîtriser(Compétence)](https://trello.com/c/vvsCl8rH)

### [Expertise(Grade, Compétence)](https://trello.com/c/0EKOzT2h)

### Compétences groupés

Certaines Compétences peuvent être groupées. Elles partagent alors la même Maîtrise et la même Limite, mais leurs progression sur ces deux axes s'en trouve ralentie.

"**Grouper les Compatences(Liste de Compétences)**" est une Capacité passsive.

### Spécialisation

Certaines compétences peuvent faire l'object de Spécialisation. Dans certaines circonstance, le personnage bénéficie d'un bonus à son Degré de maîtrise, à sa Limite, ou aux deux. 

"**Spécialisation(Compétences, Circonstance)**" est une Capacité passsive.

### TODOS

> TODO:
Reword de Compétence :
**Compétences = Savoir + Limite + ∆Capacités**
**Compétences = Maîtrise + Expertise + ∆Capacités**

# Attributs

Quel que soit leur origine, race, ou profession, tous les personnages commencent le jeu avec des capacités naturelles, et donc des compétences naturelles. Ces compétences, particulières car partagées par tous, sont appelés **Attributs** ou ***Caractéristiques*** des personnages.

- **Vitalité**
Une créature vivante est... Vivante.
À ce titre, elle possède de la force vitale lui permettant d'exister, et d'un instinct de survie lui intimant de rester en vie.

- **Vitesse**
Une créature animée possède une vitesse lui permettant de se déplacer. Elle lui permet aussi de reagir pour se sortir d'une situation périlleuse.

- **Volonté / Mentalité / Concience**
Une créature intelligente possède une volonté lui permettant d'agir selon son bon vouloir.

> **Races monstrueuses**
Les joueurs n'ont pas accès aux races monstrueuses comme les morts-vivants. La question de ne pas disposer des attributs ci-dessus ne se pose pas.
{.is-info}

[Capacités]: /sphérier/référence/capacités
[Capacités.trello]: https://trello.com/c/EUJsvYrZ

[core]:/sphérier/core

[Compétences]: /sphérier/référence/compétences
[Compétences.trello]: https://trello.com/c/udzuobSo

[Personnage]: /sphérier/référence/personnages
[Personnage.trello]: https://trello.com/c/j5txrEnh

[Capacités]: /sphérier/référence/capacités
[Capacités.trello]: https://trello.com/c/EUJsvYrZ
[Compétence]: /sphérier/référence/compétences
[Compétence.trello]: https://trello.com/c/udzuobSo

[Liste des Capacités]: /sphérier/référence/liste-capacités
[Capacités]: /sphérier/référence/capacités
[Capacités.trello]: https://trello.com/c/EUJsvYrZ

[core]:/sphérier/référence/core

[Compétences]: /sphérier/référence/compétences
[Compétences.trello]: https://trello.com/c/udzuobSo

[Effet]: /sphérier/référence/effet

[Personnage]: /sphérier/référence/personnages
[Personnage.trello]: https://trello.com/c/j5txrEnh