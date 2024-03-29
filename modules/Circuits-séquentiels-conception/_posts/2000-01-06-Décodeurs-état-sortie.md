---
title: Décodeurs d'état et de sortie
---

## Décodeur d'état

Après avoir décidé d'une assignation, on refait le tableau d'état
simplifié en remplaçant les étiquettes d'états symboliques par les
codes binaires correspondants. On obtient ainsi un **tableau de
transition**, qui permet d'élaborer les expressions logiques pour le
décodeur de prochain état. Le type de bascules à utiliser déterminera
les sorties nécessaires pour le décodeur d'état, en se basant sur les
tableaux caractéristiques de la section [Tableaux caractéristiques]({{site.baseurl}}{% post_url modules/Circuits-séquentiels/2000-01-07-Tableau-et-équation-caractéristique %}).


## Décodeur de sortie

Une fois que le codage d'état est établi, la conception du décodeur de
sortie est directe. Un tableau de vérité avec comme entrées les
valeurs binaires d'états et comme sorties les valeurs de sorties
externes permet de déterminer les fonctions combinatoires à
implémenter.

