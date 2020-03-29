---
title: Mermaid
description: Bac à sable pour mermaid JS
published: true
date: 2020-03-29T14:29:49.276Z
tags: 
---

# C'est quoi
> Voir la documentaiont en ligne https://mermaid-js.github.io/mermaid/#/

graph LR
   a --> b & c--> d


```mermaid
graph TD
A[Square Rect] -- Link text --> B((Circle))
A --> C(Round Rect)
B --> D{Rhombus}
C --> D
```


<div class="mermaid">
graph LR
    A --- B
    B-->C[fa:fa-ban forbidden]
    B-->D(fa:fa-spinner);
</div>
<script>mermaid.initialize({startOnLoad:true});</script>