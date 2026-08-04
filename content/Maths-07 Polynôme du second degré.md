---
chapitre: 7
tags:
  - maths/premiere-bac-pro
---

# Polynôme du second degré

## Appropriation

> [!definition] Définition — Polynôme du second degré
> On appelle polynôme du second degré toutes les expressions du type $ax^2+bx+c$ où $a,b$ et $c$ sont des nombres.

> [!exemple] Exemple
> Voici quelques exemples de polynômes du second degré :
> - $4x^2-6x+2$ est un polynôme du second degré où $a=4$, $b=-6$ et $c=2$
> - $-6x^2+2x-4$ est un polynôme du second degré où $a=-6$, $b=2$ et $c=-4$

> [!propriete] Propriété
> La représentation graphique d'un polynôme du second degré est une parabole. Son sens dépend du signe de $a$.
> - Si $a>0$ :
>
> ![[para1.png]]
>
> - Si $a<0$ :
>
> ![[para2.png]]

> [!definition] Définition — Racines
> On appelle racine d'un polynôme les valeurs de $x$ telles que :
> $$ax^2+bx+c=0$$

> [!propriete] Propriété
> Un polynôme du second degré peut avoir :
> - Aucune racine
>
> ![[rac0.png]]
>
> - Une seule racine : $x=2$
>
> ![[rac1.png]]
>
> - Deux racines $x \approx -1.25$ et $x \approx 5.2$
>
> ![[rac2.png]]

> [!exercice] Exercice 1
> Voici la représentation de plusieurs polynômes, déterminer graphiquement la valeur de leurs racines si il y en a.
>
> ![[rrac1.png]]
>
> ![[rrac2.png]]
>
> ![[rrac2.png]]

> [!travail] Travail
> Voici un programme de recherche de racines. Votre travail consiste à écrire un texte expliquant dans le détail le fonctionnement de ce programme.
>
> https://replit.com/@CdricChevarier/rac?v=1
>
> ```python
> # Definition du polynome du second degre
> def f(x):
>   return 4*x**2-6*x+2
>
> # Definition de l interval de recherche et de la resolution
>
> xmin = 0
> xmax = 2
> resolution = 0.1
>
> #Initialisation du signe. Pour ce faire on prend le signe de la premiere valeur de l'intervalle de recherche.
> if f(xmin)>0 :
>   signe = "positif"
> else:
>   signe = "negatif"
>
> #Affichage de l'interval de recherche
>
> print("Interval de recherche",numpy.arange(xmin,xmax,resolution,float))
>
> #...
> print("Debut de la recherche")
> for i in numpy.arange(xmin,xmax,resolution,float) :
>   if f(i)>0 :
>     signe_courant = "positif"
>   else:
>     signe_courant = "negatif"
>   if(signe_courant != signe):
>     print("\n")
>     print("Detection d'une racine entre",i-resolution,"et",i)
>     print("\n")
>   else:
>     print("Aucune racine detectee entre",i-resolution,"et",i)
>   signe = signe_courant
> ```

## Réaliser

> [!exercice] Exercice 2
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

> [!propriete] Propriété
> Soit $ax^2+bx+c$ un trinôme du second degré et $x_1$ et $x_2$ les racines de ce trinôme alors :
> - $x_1 + x_2 = \dfrac{-b}{a}$
> - $x_1 \times x_2 = \dfrac{c}{a}$

> [!propriete] Propriété
> Soit la parabole $f$ d'équation $f(x)=ax^2+bx+c$, $f$ atteint son sommet pour $x=\dfrac{-b}{2a}$

> [!travail] Travail
> Une entreprise produit et vend des composants électroniques. Sa capacité mensuelle de production est comprise entre 2 000 et 18 000 pièces. On suppose que toute la production est commercialisée.
> Le responsable des ventes veut étudier la rentabilité de son entreprise. $x$ est le nombre de pièces produites, en milliers, les coûts de production sont donnés en fonction de $x$ par $p(x)= 2x^2-26x+102$. Le PVHT d'un composant est de 14€.
>
> **Problématique :** Le chef d'entreprise désirerait déterminer pour quel intervalle de production, l'entreprise est rentable. Il voudrait aussi déterminer pour quelle production la rentabilité est maximale.
