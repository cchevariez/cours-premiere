---
chapitre: 1
tags:
  - maths/premiere-bac-pro
---

# Statistiques à deux variables

## Activité d'introduction

> [!rituel] Rituel
> Vérifier si la valeur proposée est bien la solution de l'équation, sinon donner la bonne valeur.
> 1. $10x=16$ a pour solution $x=1,6$.
> 2. $8x=5$ a pour solution $x=1,6$.
> 3. $x+3=2$ a pour solution $x=-1$.
> 4. $x-5=12$ a pour solution $x=7$.

> [!correction] Correction
> 1. Vrai.
> 2. Faux : $x = \dfrac{5}{8}$.
> 3. Vrai.
> 4. Faux : $x = 12+5=17$.

Les États-Unis sont encore de loin la première puissance économique mondiale. Mais pas pour toujours. L'économie chinoise progresse plus vite que celle des États-Unis. Résultat : la Chine devrait détrôner les États-Unis en 2032. (Source : L'Expansion)

**Problématique :** Cette prévision est-elle exacte ?

![[usachina.jpg]]

Pour répondre à cette question vous disposez des données suivantes (source : Banque Mondiale). Les PIB sont données en billions (millier de milliards) de dollars.

| Année | Chine | États-Unis |
|---|---|---|
| 2001 | 1.3 | 10.6 |
| 2002 | 1.5 | 10.9 |
| 2003 | 1.7 | 11.5 |
| 2004 | 2.0 | 12.2 |
| 2005 | 2.3 | 13.0 |
| 2006 | 2.8 | 13.8 |
| 2007 | 3.6 | 14.5 |
| 2008 | 4.6 | 14.7 |
| 2009 | 5.1 | 14.4 |
| 2010 | 6.1 | 15.0 |
| 2011 | 7.6 | 15.5 |
| 2012 | 8.5 | 16.2 |
| 2013 | 9.6 | 16.8 |
| 2014 | 10.5 | 17.5 |
| 2015 | 11.1 | 18.2 |
| 2016 | 11.2 | 18.7 |
| 2017 | 12.3 | 19.5 |
| 2018 | 13.9 | 20.6 |
| 2019 | 14.3 | 21.4 |
| 2020 | 15.0 | 21.3 |
| 2021 | 18.2 | 23.7 |
| 2022 | 18.3 | 26.0 |
| 2023 | 18.4 | 27.7 |

*Évolution comparée du PIB Chine / États-Unis (2001–2023).*

> [!travail] Travail
> 1. Dans le repère ci-dessous, l'évolution du PIB américain et chinois sous la forme d'un nuage de points.
>
> ![[reperepib.png]]
>
> 2. Généralement le PIB d'un pays croît tous les ans. Y a-t-il une ou des exceptions dans le graphique que vous avez construit ? Si oui, donner une explication à ces exceptions.
> 3. Compte tenu du contexte actuel, se pourrait-il que ce phénomène de décroissance se reproduise ?
> 4. À votre avis le PIB chinois va-t-il dépasser le PIB américain ? (Justifier votre réponse)
> 5. Construire une méthode de votre cru pour répondre à la problématique et y répondre.
>
>> [!aide] Aide
>> Pour le moment, vous ne disposez pas d'outils mathématiques pour répondre à la question. Il faut que vous trouviez un moyen de vous débrouiller avec le nuage de points obtenu à la question 1. La méthode que vous trouverez sera de toute façon approximative.
>
> 6. Mettre en œuvre votre méthode afin de répondre à la problématique.

> [!rituel] Rituel
> Résoudre les équations suivantes :
> 1. $4x=5$.
> 2. $0,5x=9$.
> 3. $-5x=2$.
> 4. $3+x=0.5$.
> 5. $x-5=1$.

> [!correction] Correction
> 1. $x = \dfrac{5}{4}$.
> 2. $x = \dfrac{9}{0.5} = 18$.
> 3. $x = \dfrac{2}{-5}=-0.4$.
> 4. $x = 0.5-3 = -2.5$.
> 5. $x = 1+5 = 6$.

| Compétences | Capacités |
|---|---|
| **S'approprier** | Comprendre la problématique liée au problème et le vocabulaire associé. |
| **Analyser / Raisonner** | Reconnaître les cas où un ajustement linéaire est pertinent.<br>Décrire les étapes de résolution d'un problème utilisant une régression. |
| **Réaliser** | Déterminer l'équation de la droite d'ajustement.<br>Tracer un nuage de points.<br>Déterminer $R^2$. |
| **Valider** | Valider une hypothèse en utilisant l'ajustement linéaire.<br>Juger de la corrélation de deux séries en fonction de $R^2$. |
| **Communiquer** | Répondre à la problématique en utilisant le vocabulaire adéquat. |

## Réaliser

> [!definition] Définition — Statistique à deux variables
> Lorsque l'on étudie conjointement deux caractères quantitatifs on obtient alors une série statistique quantitative à deux variables. Les valeurs prises par le premier caractère sont notées $x_1,x_2,\ldots,x_n$ et celles prises par le deuxième caractère sont notées $y_1,y_2,\ldots,y_n$.

> [!remarque] Remarque
> On dit qu'une série est chronologique lorsque l'on étudie les valeurs prises par un caractère au cours du temps.

> [!exemple] Exemple
> Voici une étude statistique permettant de relier le budget publicitaire d'une entreprise à son CA.
>
> | Budget publicitaire en milliers d'euros $x_i$ | 8 | 10 | 12 | 14 | 16 | 18 |
> |---|---|---|---|---|---|---|
> | Chiffre d'affaire en milliers d'euros $y_i$ | 32 | 55 | 55 | 70 | 75 | 95 |

> [!definition] Définition — Nuage de points
> Dans un repère, l'ensemble des points de coordonnées $(x_i;y_i)$ forment le nuage de points représentant cette série statistique à deux variables.

![[pubca.png]]

> [!definition] Définition — Ajustement affine ou régression linéaire par la méthode des moindres carrés
> Effectuer un ajustement affine d'un nuage de points consiste à déterminer une fonction affine $y=ax+b$ dont la droite représentative $d$ passe « au plus près » de tous les points.

![[pubcareg.png]]

L'équation de la droite est $y=5,57x-8,76$

> [!exercice] Exercice 1
> Dans l'équation ci-dessus :
> - Que représente la variable $y$ ?
> - Que représente la variable $x$ ?
> - Déterminer une estimation du CA attendu si on a un budget publicitaire de 30000 euros.
> - Déterminer une estimation du budget publicitaire nécessaire pour obtenir un CA de 250000 euros.

> [!remarque] Remarque
> Un tutoriel sur la régression linéaire est disponible dans deux vidéos très courtes (moins d'une minute).
> - [Vidéo 1 — régression linéaire](https://www.youtube.com/watch?v=uPIjhsm6JsE)
> - [Vidéo 2 — régression linéaire](https://www.youtube.com/watch?v=iX7Kg5FkkX8)

> [!exercice] Exercice 2
> Vous disposez du tableau de données suivant :
>
> | Âge en mois $(x_i)$ | 3 | 6 | 9 | 12 | 15 |
> |---|---|---|---|---|---|
> | Taille en cm $(y_i)$ | 59 | 65 | 70 | 74 | 77 |
>
> - À l'aide des vidéos tutoriel tracer le nuage de points.
> - Déterminer l'équation de la droite de régression.
> - À l'aide de l'équation de la droite de régression déterminer :
>   - Une estimation de la taille d'un bébé de 27 mois.
>   - Une estimation de l'âge d'un bébé mesurant 94 cm.
>   - Vérifier vos résultats grâce à l'outil Numworks.
>   - Combien de mois avez-vous ?
>   - Quelle devrait être votre taille ?
>   - Critiquer le résultat obtenu.

> [!rituel] Rituel
> Pour cet exercice, vous disposez d'une équation à deux inconnues. On vous donne la valeur d'une inconnue, à vous de trouver la valeur de la deuxième.
> 1. $y=9x+2$ et $x=7$.
> 2. $y = -6x +2$ et $x=-2$.
> 3. $y = 2x - 3$ et $y=10$.
> 4. $y = -3x +5$ et $y=12$.

> [!correction] Correction
> 1. $y = 9\times7+2 = 65$.
> 2. $y = -6\times(-2) + 2 = 14$.
> 3. $10 = 2x -3 \Rightarrow x = \dfrac{13}{2} = 6.5$.
> 4. $12 = -3x +5 \Rightarrow x = \dfrac{7}{-3}$.

## Équation de droite

Nous utilisons la notion d'équation de droite. Pour la suite du chapitre, nous avons besoin de maîtriser totalement cette notion. Cette partie a pour objectif de revenir sur cette notion mathématique.

> [!definition] Définition — Équation de droite
> Une équation de droite est une équation permettant de décrire l'ensemble des points appartenant à cette droite. Cette équation est de la forme $y=ax+b$ où $x$ et $y$ sont des coordonnées de point et $a$ et $b$ deux nombres.

> [!exemple] Exemple
> Soit $D$ la droite d'équation $y=0,5x+2$.
>
> ![[droite.png]]
>
> Les points $A$ et $B$ appartiennent à la droite, en effet leurs coordonnées vérifient l'équation de la droite.
> - Pour $A(1;2,5)$ si on remplace $x$ par 1 (abscisse de $A$) dans l'équation on obtient $y=0,5 \times 1+2=2,5$ ce qui correspond à l'ordonnée de $A$.
> - Pour $B(-5;0,5)$ on peut répéter le même raisonnement.
> - $C(2;1)$ n'appartient pas à la droite, en effet si on remplace $x$ par 2 dans l'équation de la droite on obtient $y=0,5 \times 2 + 2 = 3$ ce qui ne correspond pas à l'ordonnée de $C$.

> [!exercice] Exercice 3
> On reprend la droite $D$ d'équation $y=0,5x+2$.
> 1. Le point $D(10;7)$ appartient-il à $D$ ?
> 2. Le point $E(-3;0,5)$ appartient-il à $D$ ?
> 3. Le point $F(-10;-4)$ appartient-il à $D$ ?
> 4. Déterminer le point de $D$ dont l'abscisse est égale à 12.
> 5. Déterminer le point de $D$ dont l'ordonnée est égale à -5.

> [!rituel] Rituel
> Augmentations et réductions.
> 1. Un article coûte 50€. Il augmente de 20%. Quel est son nouveau prix ?
> 2. Un article coûte 90€. Il subit une réduction de 10%. Quel est son nouveau prix ?
> 3. Quel est le coefficient multiplicateur associé à une augmentation de 6% ?
> 4. Quel est le coefficient multiplicateur associé à une réduction de 45% ?

> [!correction] Correction
> 1. $PF = 50\times1,20=60$€.
> 2. $PF = 90\times0,90=81$€.
> 3. $1,06$.
> 4. $0,55$.

## Intersection de deux droites

On peut calculer les coordonnées du point d'intersection de deux droites en résolvant un système.

> [!remarque] Remarque
> Si deux droites ont le même coefficient directeur (valeur de $a$), elles sont parallèles. Il n'y a donc pas de point d'intersection.

> [!exemple] Exemple
> Soit $D$ la droite d'équation $y=6x-8$ et $D'$ la droite d'équation $y=-4x+12$. Afin de déterminer le point d'intersection nous allons résoudre le système suivant :
> $$
> \left\{
> \begin{array}{r c l}
> y &=& 6x - 8\\
> y &=& -4x + 12
> \end{array}
> \right.
> $$
> On garde la première ligne telle quelle. Et on remplace le $y$ de la deuxième ligne par l'expression en $x$ de la première.
> $$
> \left\{
> \begin{array}{r c l}
> y &=& 6x - 8\\
> 6x - 8 &=& -4x + 12
> \end{array}
> \right.
> $$
> On garde toujours la première ligne en résolvant l'équation de la deuxième ligne.
> $$
> \left\{
> \begin{array}{r c l}
> y &=& 6x - 8\\
> 10x  &=& 20
> \end{array}
> \right.
> $$
> $$
> \left\{
> \begin{array}{r c l}
> y &=& 6x - 8\\
> x  &=& 2
> \end{array}
> \right.
> $$
> Puis on injecte la valeur de $x$ dans la première ligne.
> $$
> \left\{
> \begin{array}{r c l}
> y &=& 6 \times 2 - 8\\
> x  &=& 2
> \end{array}
> \right.
> $$
> $$
> \left\{
> \begin{array}{r c l}
> y &=& 4\\
> x  &=& 2
> \end{array}
> \right.
> $$
> On obtient donc les coordonnées du point d'intersection qui sont $(2;4)$.

> [!exercice] Exercice 4
> Déterminer les coordonnées du point d'intersection des droites suivantes :
> - $D$ : $y=7x-6$ et $D'$ : $y=-2x-7$
> - $D$ : $y=-2,5x-3$ et $D'$ : $y=-7x+12$

> [!travail] Travail
> Reprendre les données pour les PIB chinois et américains et répondre à la problématique en utilisant la régression linéaire. Vous répondrez ensuite aux questions en identifiant la ou les compétences mises en jeu :
> 1. Pour le PIB chinois, votre régression linéaire vous a donné une équation de droite de la forme $y = ax+b$, que représentent $x$ et $y$ dans ce contexte ?
> 2. Par le calcul, déterminer une estimation du PIB américain en 2050. Vous expliquerez les étapes de votre démarche.
> 3. Par le calcul, déterminer une estimation de l'année où le PIB américain aura dépassé 25 billions de dollars. Vous expliquerez les étapes de votre démarche.

> [!rituel] Rituel
> Calculer le pourcentage que représente la quantité partielle par rapport à la quantité totale.
> 1. Dans une classe de 25 élèves, 5 sont absents. Quel pourcentage d'élèves est absent ?
> 2. Sur 40 bonbons, 8 sont au chocolat. Quel pourcentage de bonbons est au chocolat ?
> 3. 60 élèves ont validé un contrôle sur 80. Quel pourcentage cela représente-t-il ?
> 4. Un panier contient 12 pommes sur 50 fruits. Quel pourcentage de pommes contient le panier ?

> [!correction] Correction
> 1. $\dfrac{5}{25}\times100=20\%$.
> 2. $\dfrac{8}{40}\times100=20\%$.
> 3. $\dfrac{60}{80}\times100=75\%$.
> 4. $\dfrac{12}{50}\times100=24\%$.

## Analyser - Valider

Les prévisions de météo France sont de plus en plus précises. En effet, plus les années passent, plus la base de données météorologique s'agrandit. Voici la dernière activité sur le PIB chinois et américain.

> [!travail] Travail
> Vous disposez ci-dessous des données sur les PIB américain et chinois depuis 1980 (en billions de dollars, source : Banque Mondiale). En utilisant le tableau des compétences, donner une estimation de l'année où le PIB chinois dépassera le PIB américain. Dans la partie « valider », vous critiquerez la pertinence du résultat obtenu. Ce travail est à rendre, au format PDF, sur lms.zone.
>
> | Année | Chine | États-Unis | Année | Chine | États-Unis |
> |---|---|---|---|---|---|
> | 1980 | 0.2 | 2.9 | 2000 | 1.2 | 10.3 |
> | 1981 | 0.2 | 3.2 | 2001 | 1.3 | 10.6 |
> | 1982 | 0.2 | 3.3 | 2002 | 1.5 | 10.9 |
> | 1983 | 0.2 | 3.6 | 2003 | 1.7 | 11.5 |
> | 1984 | 0.3 | 4.0 | 2004 | 2.0 | 12.2 |
> | 1985 | 0.3 | 4.3 | 2005 | 2.3 | 13.0 |
> | 1986 | 0.3 | 4.6 | 2006 | 2.8 | 13.8 |
> | 1987 | 0.3 | 4.9 | 2007 | 3.6 | 14.5 |
> | 1988 | 0.3 | 5.2 | 2008 | 4.6 | 14.7 |
> | 1989 | 0.3 | 5.6 | 2009 | 5.1 | 14.4 |
> | 1990 | 0.4 | 6.0 | 2010 | 6.1 | 15.0 |
> | 1991 | 0.4 | 6.2 | 2011 | 7.6 | 15.5 |
> | 1992 | 0.4 | 6.5 | 2012 | 8.5 | 16.2 |
> | 1993 | 0.4 | 6.9 | 2013 | 9.6 | 16.8 |
> | 1994 | 0.6 | 7.3 | 2014 | 10.5 | 17.5 |
> | 1995 | 0.7 | 7.6 | 2015 | 11.1 | 18.2 |
> | 1996 | 0.9 | 8.1 | 2016 | 11.2 | 18.7 |
> | 1997 | 1.0 | 8.6 | 2017 | 12.3 | 19.5 |
> | 1998 | 1.0 | 9.1 | 2018 | 13.9 | 20.6 |
> | 1999 | 1.1 | 9.6 | 2019 | 14.3 | 21.4 |
>
>> [!aide] Aide
>> Vous pouvez discuter la pertinence de votre droite de régression en mettant en relation l'allure du nuage de points et l'allure de la courbe.

> [!definition] Définition — Coefficient de détermination $R^2$
> Le coefficient de détermination $R^2$ est un indice permettant de juger de la qualité d'une régression. Si cet indice est proche de 1 alors la régression est de bonne qualité, plus il est proche de 0 moins la qualité de la régression est bonne.

> [!exercice] Exercice 5
> Voici une série de trois nuages de points. Si on fait une régression linéaire sur chacun d'eux, quelles seront à votre avis les valeurs de $R^2$ (proche de 0, proche de 1 ou entre 0 et 1) ?
>
> Nuage 1 : ![[nuage1.png|300]]
> Nuage 2 : ![[nuage2.png|300]]
> Nuage 3 : ![[nuage3.png|300]]

> [!definition] Définition — Corrélation
> En mathématiques, on dit que deux séries sont corrélées si leur coefficient de détermination est proche de 1.

> [!remarque] Remarque
> Un tutoriel est disponible sur lms.zone pour vous aider à déterminer la valeur de $R^2$.
> - [Vidéo — déterminer $R^2$](https://youtu.be/b5KSM5Xr-2c)

> [!rituel] Rituel
> Mettre le problème en équation puis la résoudre pour retrouver le prix initial.
> 1. Après une augmentation de 8%, un article coûte 97,20€. Quel était son prix initial ?
> 2. Après une réduction de 15%, un article coûte 68€. Quel était son prix initial ?
> 3. Après une augmentation de 3%, un salaire est de 1751€. Quel était le salaire initial ?
> 4. Après une réduction de 20%, un article coûte 64€. Quel était son prix initial ?

> [!correction] Correction
> 1. $1,08x=97,20 \Rightarrow x = \dfrac{97,20}{1,08}=90$€.
> 2. $0,85x=68 \Rightarrow x = \dfrac{68}{0,85}=80$€.
> 3. $1,03x=1751 \Rightarrow x = \dfrac{1751}{1,03}=1700$€.
> 4. $0,8x=64 \Rightarrow x = \dfrac{64}{0,8}=80$€.

## Applications

> [!travail] Travail
> Vous disposez ci-dessous des données (source INSEE) concernant le taux de mortalité en fonction de l'âge. En vous appuyant sur le tableau des compétences, démontrer que l'âge et le taux de mortalité sont corrélés. Peut-on envisager un lien de causalité ? Dans la partie « s'approprier » vous expliquerez ce qu'est un taux de mortalité ainsi qu'une relation de causalité.
>
> | Tranche d'âge | Taux de mortalité |
> |---|---|
> | 1 à 4 ans | 0.2 |
> | 5 à 9 ans | 0.1 |
> | 10 à 14 ans | 0.1 |
> | 15 à 19 ans | 0.2 |
> | 20 à 24 ans | 0.4 |
> | 25 à 29 ans | 0.5 |
> | 30 à 34 ans | 0.6 |
> | 35 à 39 ans | 0.8 |
> | 40 à 44 ans | 1.3 |
> | 45 à 49 ans | 2.0 |
> | 50 à 54 ans | 3.3 |
> | 55 à 59 ans | 5.1 |
> | 60 à 64 ans | 7.7 |
> | 65 à 69 ans | 10.7 |
> | 70 à 79 ans | 18.3 |
> | 80 à 89 ans | 20.0 |
> | 90 à 110 ans | 22.5 |

> [!travail] Travail
> Vous disposez ci-dessous des données concernant le nombre de prix Nobel pour 10 millions d'habitants en fonction de la consommation de chocolat (kg/habitant/an) de plusieurs pays. En vous appuyant sur le tableau des compétences, discuter de la corrélation et de la causalité entre ces deux séries.
>
> | Pays | Conso de chocolat (kg/habitant/an) | Prix Nobel pour 10 millions |
> |---|---|---|
> | Suisse | 8.8 | 32.771 |
> | Autriche | 8.1 | 25.138 |
> | Allemagne | 7.9 | 13.245 |
> | Irlande | 7.9 | 14.572 |
> | Grande Bretagne | 7.6 | 19.429 |
> | Finlande | 5.4 | 9.021 |
> | Pays-Bas | 5.1 | 11.707 |
> | Nouvelle-Zélande | 5.0 | 6.316 |
> | Australie | 4.9 | 4.844 |
> | République Tchèque | 4.9 | 4.706 |
> | États-Unis | 4.4 | 11.721 |
> | France | 4.3 | 10.664 |
> | Brésil | 1.2 | 0.047 |
> | Japon | 1.2 | 1.887 |
> | Afrique du Sud | 0.9 | 0.697 |
> | Chine | 0.1 | 0.035 |
