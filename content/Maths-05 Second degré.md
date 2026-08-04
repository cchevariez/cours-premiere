---
chapitre: 5
tags:
  - maths/premiere-bac-pro
---

# Second degré

## Définition

> [!definition] Définition — Équation du second degré
> On appelle équation du second degré toute équation de la forme $ax^2+bx+c=0$ où $a,b$ et $c$ sont des nombres et $x$ une inconnue.

> [!definition] Définition — Racine d'une équation
> On appelle racine d'une équation toute valeur de $x$ qui satisfait l'équation $ax^2+bx+c=0$.

> [!exercice] Exercice 1
> Parmi ces équations, identifier les équations du second degré. Si les équations sont du second degré, donner les valeurs de $a,b$ et $c$.
> 1. $6x^2-3x-9=0$
> 2. $3x - 4 =0$
> 3. $2x^2 + 6 =0$
> 4. $-2x^2+6x-9=0$
> 5. $3x^2 +7x = 12$
> 6. $4x^2 -5x +30 = 6x -2$
> 7. $-2x^2 -2x -22 = 3x^2 -2x +12$

## Méthode de résolution

### Méthode graphique

> [!methode] Méthode
> Nous allons résoudre graphiquement les équations :
> - $2x^2-5x+2 = 0$
> - $4x^2-12x+9 = 0$
> - $x^2+x+1 = 0$
>
> 1. Construire dans les repères ci-dessous les courbes des fonctions :
>   - $f(x) = 2x^2-5x+2$
>   - $g(x) = 4x^2-12x+9$
>   - $h(x) = x^2+x+1$
>
> ![[graphsecond.png]]
>
> 2. Résoudre graphiquement les équations :
>   - $2x^2-5x+2 = 0$
>   - $4x^2-12x+9 = 0$
>   - $x^2+x+1 = 0$
>
>   Décrire votre méthode.

### Méthode algébrique

> [!methode] Méthode
> Pour résoudre une équation du type $ax^2+bx+c=0$, il faut dans un premier temps calculer le discriminant noté $\Delta$ tel que $\Delta = b^2 - 4ac$.
>
> - Si $\Delta < 0$, l'équation n'a pas de solution.
> - Si $\Delta = 0$, alors il y a une racine (solution) qui est $\dfrac{-b}{2a}$
> - Si $\Delta > 0$, alors il y a deux racines $x_1 = \dfrac{-b + \sqrt{\Delta}}{2a}$ et $x_2 = \dfrac{-b - \sqrt{\Delta}}{2a}$
>
> 1. Résoudre l'équation $2x^2-5x+2 = 0$
> 2. Résoudre l'équation $4x^2-12x+9 = 0$
> 3. Résoudre l'équation $x^2+x+1 = 0$

> [!exercice] Exercice 2
> Résoudre les équations suivantes :
> 1. $6x^2-3x-9=0$
> 2. $2x^2 + 6 =0$
> 3. $-2x^2+6x-9=0$
> 4. $3x^2 +7x = 12$
> 5. $4x^2 -5x +30 = 6x -2$
> 6. $-2x^2 -2x -22 = 3x^2 -2x +12$

## Exercices

> [!exercice] Exercice 3
> La distance de freinage $d$ d'une voiture dépend de la vitesse d'un véhicule. Elle s'exprime par la relation :
> $$d = 0,007v^2+0,8v$$
> où $v$ désigne la vitesse en $km/h$ et $d$ la distance de freinage en $m$.
> 1. Calculer la distance $d$ lorsqu'on roule à 90 $km/h$.
> 2. Résoudre l'équation :
> $$0,007v^2+0,8v = 50$$
> 3. Donner une interprétation du résultat obtenu à la question précédente.

> [!exercice] Exercice 4
> Une entreprise produit et vend des composants électroniques. Sa capacité mensuelle de production est comprise entre 2 000 et 18 000 pièces. On suppose que toute la production est commercialisée.
> Le responsable des ventes veut étudier la rentabilité de son entreprise. $x$ est le nombre de pièces produites, en milliers, les coûts de production sont donnés en fonction de $x$ par $p(x)= 2x^2-26x+102$. Le PVHT d'un composant est de 14€.
> 1. Exprimer, en fonction de $x$, le CA $c(x)$ de l'entreprise.
> 2. Expliquer pourquoi la fonction $c(x)-p(x)$ traduit la rentabilité correspondant à la fabrication de $x$ milliers de composants électroniques.
> 3. On admet que le bénéfice mensuel de l'entreprise est modélisé par la fonction $f$ définie sur $[2;18]$ par $f(x)=-2x^2+40x-102$ où $x$ est le nombre de milliers de pièces produites. Un tracé de sa courbe représentative est donné ci-dessous.
>
> ![[graphsecond2.png]]
>
>   1. Déterminer graphiquement le seuil de rentabilité.
>   2. Retrouver ce résultat par le calcul en résolvant $f(x)=0$.

> [!exercice] Exercice 5
> Une entreprise a besoin d'une zone de stockage de $120m^2$ pour sa marchandise. Pour pouvoir circuler et déplacer les colis aisément, on laisse une zone de circulation comme indiquée sur le schéma ci-dessous.
>
> ![[stockage.png]]
>
> On cherche à déterminer la surface d'entrepôt nécessaire pour stocker la marchandise.
> 1. Exprimer en fonction de $x$ la longueur et la largeur de la zone de stockage.
> 2. Montrer que l'expression de $A(x)$ de l'aire de la zone de stockage peut s'écrire :
> $$A(x)=4x^2-22x+24$$
> 3. Dans cette question, on va déterminer $x$ tel que l'aire de $A(x)$ soit égale à $120m^2$.
>   1. Montrer que cela revient à résoudre $4x^2-22x-86=0$
>   2. Calculer les valeurs des deux solutions de cette équation et les arrondir au centième.
>   3. En déduire les dimensions de la surface d'entrepôt nécessaire.

> [!exercice] Exercice 6
> En appliquant une marge unitaire de 20€, un commerçant peut espérer écouler 50 articles. Chaque euro de baisse de sa marge lui permettrait de vendre 10 articles de plus.
>
> **Problématique :** Le commerçant souhaite savoir le montant de la baisse accordée sur la marge de chaque article pour espérer réaliser une marge totale de 1500€.
>
> 1. Calculer la marge totale qu'il peut obtenir en vendant les articles sans accorder aucune baisse de la marge unitaire.
> 2. Compléter le tableau suivant :
>
> ![[tabmarge.png]]
>
> 3. Il est autorisé pour un commerçant de vendre à perte uniquement pendant les périodes de soldes. D'après les résultats du tableau précédent, expliquer à l'aide d'une phrase si le commerçant pourra appliquer une baisse de 25€ sur sa marge unitaire en dehors des périodes de soldes.
> 4. Proposer une démarche afin de répondre à la problématique.
> 5. On admet que la résolution de l'équation $-10x^2+150x+1000=1500$ permet de répondre à la problématique.
>   1. Transformer l'équation afin de pouvoir la résoudre par la méthode du discriminant.
>   2. Résoudre l'équation par un calcul détaillé.
> 6. À partir des résultats précédents, rédiger une phrase donnant le montant de la baisse à accorder sur la marge de chaque article pour espérer réaliser une marge totale de 1500€.
> 7. Le commerçant aimerait obtenir une marge globale encore supérieure. Il cherche la baisse à appliquer à la marge unitaire pour parvenir à une marge globale de 1600€.
>   1. Donner l'équation permettant d'obtenir la valeur de la baisse de la marge unitaire à appliquer afin d'obtenir une marge globale de 1600€.
>   2. On suppose que cette équation conduit à : $-10x^2+150x-600=0$. Résoudre cette équation.
>   3. Rédiger une phrase pour dire si le commerçant pourra obtenir une marge de 1600€.
