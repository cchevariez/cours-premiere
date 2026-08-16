---
chapitre: 3
tags:
  - maths/premiere-bac-pro
---

# Fonctions — Généralités

## Appropriation

### Notion de fonction

Cette partie vise à comprendre la notion et le rôle d'une fonction. Nous allons reprendre un exemple classique de fonction afin d'associer les différentes étapes de son étude aux définitions.

> [!definition] Définition — Fonction
> Une fonction est une procédure permettant d'associer deux grandeurs. On note habituellement une fonction par la lettre $f$.

> [!propriete] Propriété
> Si $f$ est une fonction qui au nombre $x$, associe le nombre $y$, on note $y=f(x)$ (lire $f$ de $x$) ou $f : x \mapsto f(x)$ (lire $f$ qui à $x$ associe $f(x)$).
>
> On dit que $y$ ou $f(x)$ est l'image de $x$ par $f$ et que $x$ est un antécédent de $y$ ou $f(x)$ par $f$.

> [!activite] Activité
> Voici un exemple de la représentation de la fonction $f$ : "distance de freinage" d'une voiture sur sol mouillé.
>
> ![[freinage.png]]
>
> 1. Quelles sont les deux grandeurs qu'associe la fonction distance de freinage ?
> 2. Compléter la phrase suivante :
>
> La fonction distance de freinage représente …… en fonction de …….
>
> 3. Déterminer la distance de freinage d'un véhicule roulant à 60 km/h.
> 4. Déterminer l'image de 120 et donner une interprétation du résultat obtenu.
> 5. Déterminer l'antécédent de 34 et donner une interprétation du résultat obtenu.

> [!rituel] Rituel
> Répondre aux questions suivantes :
> 1. Résoudre $-6x+7=25$
> 2. Calculer 12% de 5200 euros

> [!correction] Correction
> 1. $-6x+7=25 \Rightarrow -6x = 18 \Rightarrow x = -3$.
> 2. $5200 \times 0.12 = 624$.

### Variations d'une fonction

> [!activite] Activité
> On considère la fonction $f(x)=-0.5 x^2+7 x+20$ qui modélise le prix d'un article au cours de ses dix premières années de commercialisation. Voici la représentation graphique de cette fonction :
>
> ![[1CA-fct1.png]]
>
> 1. Quelles sont les grandeurs sur l'axe des abscisses et l'axe des ordonnées ?
> 2. Quel était le prix de lancement de l'article ?
> 3. Sur la période considérée, quel a été le prix maximum de l'article ? (justifier)
> 4. Dresser le tableau de variation de cette fonction.
> 5. À quoi sert un tableau de variations ?
> 6. Par le calcul, déterminer le prix de l'article au bout de 1,5 an.
> 7. Par le calcul, déterminer le prix de l'article au bout de 4 ans et 10 mois.
> 8. Avec l'aide du graphique compléter les égalités suivantes :
>    1. $f(\ldots)=40$
>    2. $f(8)=\ldots$

> [!rituel] Rituel
> On lance un dé à 6 faces. Soit A : "Obtenir un nombre pair" et B : "Obtenir un multiple de 3"
> 1. Déterminer $p(A \cap B)$
> 2. Déterminer $p(A \cup B)$

> [!correction] Correction
> 1. $p(A \cap B) = \dfrac{1}{6}$.
> 2. $p(A \cup B) = \dfrac{4}{6}$.

> [!travail] Travail
> Les revenus d'un réseau social dépendent de son nombre d'utilisateurs. On modélise par la fonction $f$ les revenus en fonction du nombre d'utilisateurs.
> - $x$ correspond au nombre d'utilisateurs en millions
> - $f(x)$ correspond au revenu en €
>
> $$f : x \mapsto 1 + x(x-1)^2$$
>
> **Problématique :** Effectuer une étude de cette fonction. Cette étude devra comporter une courbe, un tableau de variation ainsi qu'une description de la courbe. Vous devrez répondre au questionnement suivant :
> - À partir de quel nombre d'utilisateurs, les revenus seront-ils supérieurs à 500 000 000 € ?
> - Quels sont les revenus générés par un milliard d'utilisateurs ?
>
> Dans la partie valider, vous tracerez la courbe de cette fonction pour un nombre d'utilisateurs compris entre 0 et 2 millions d'utilisateurs. Au vu de la courbe obtenue, vous critiquerez la méthode que vous avez utilisée.
> Pour effectuer ce TP, vous avez à votre disposition sur lms.zone, le programme de tracé utilisé en seconde ainsi qu'un rappel sur la méthode pour obtenir un tableau de variation.

> [!methode] Méthode
> Il est possible d'utiliser la courbe représentative d'une fonction pour obtenir son tableau de variation en suivant la méthode suivante :
> - Étape 1 : distinguer les zones où la fonction est croissante ou décroissante.
> - Étape 2 : pour chacune des zones déterminer l'intervalle des abscisses qui lui est associé (trouver la borne inférieure et la borne supérieure) puis les reporter dans la première ligne du tableau de variations.
> - Étape 3 : Pour chaque intervalle de la première ligne du tableau de variations faire correspondre dans la deuxième une flèche montante lorsque la fonction est croissante et une flèche descendante lorsqu'elle est décroissante.
> - Étape 4 : Utiliser la courbe pour trouver l'image par f de chaque nombre figurant dans la première ligne (cette image correspond à l'ordonnée du point ayant ce nombre pour abscisse) puis, sous chaque nombre, reporter dans la deuxième ligne l'image trouvée (soit l'origine d'une flèche, soit à sa pointe).
>
> Exemple : on souhaite réaliser un tableau de variations à partir de la courbe suivante
>
> ![[var1.jpg]]
>
> **Étape 1 :**
>
> ![[var2.jpg]]
>
> **Étape 2 :**
>
> ![[var3.jpg]]
> ![[var4.jpg]]
>
> **Étape 3 :**
>
> ![[var5.jpg]]
>
> **Étape 4 :**
>
> ![[var6.jpg]]
> ![[var7.jpg]]

## Analyser

Le TP précédent a montré les limites d'une méthode d'analyse à l'aide d'un tracé. Nous allons donc essayer de construire un outil alternatif permettant d'étudier les variations d'une fonction. Pour construire cette méthode nous avons besoin de deux notions.
- Notion d'équation de droite
- Notion de tangente

> [!definition] Définition — Équation de droite
> Une équation de droite est une équation permettant de décrire l'ensemble des points appartenant à cette droite. Cette équation est de la forme $y=ax+b$ où $x$ et $y$ sont des coordonnées de point et $a$ et $b$ deux nombres. $a$ est appelé le coefficient directeur et $b$ l'ordonnée à l'origine.

> [!definition] Définition — Tangente (définition incomplète)
> Droite qui touche une courbe en un seul point au voisinage de ce point.

> [!travail] Travail
> Sur lms, vous disposez d'une animation géogébra. On vous demande de trouver une relation entre la/les tangentes et les variations de la courbe. Une fois la relation trouvée, établir une méthode qui permettrait de connaître les variations d'une courbe à l'aide de la tangente.
> - [Ouvrir l'animation GeoGebra](https://www.geogebra.org/classic/ge3khrr2)

> [!definition] Définition — Nombre dérivé
> Soit $f$ une fonction et $\mathcal{C}_f$ sa courbe représentative. Soit $A(x_A;y_A)$ appartenant à $\mathcal{C}_f$. On appelle nombre dérivé au point $A$, noté $f'(x_A)$ le nombre correspondant au coefficient directeur de la tangente au point $A$.

> [!exercice] Exercice 1
> À l'aide de geogebra, tracer la fonction $f(x)=3x^2+2x+4$ sur l'intervalle $[-3;3]$.
> 1. En indiquant votre méthode, déterminer $f'(-1)$.
> 2. Déterminer $f'(0)$, $f'(-2)$ et $f'(2)$

> [!rituel] Rituel
> Répondre aux questions suivantes :
> 1. Résoudre $12 = -5x + 4$
> 2. Quel est le prix HT d'un article dont le TTC est 85,20 euros (taux de TVA : 20%)

> [!correction] Correction
> 1. $12 = -5x + 4 \Rightarrow -5x = 8 \Rightarrow x = \dfrac{8}{-5}=-1.6$.
> 2. $\dfrac{85.20}{1.20} = 71$ euros.

Nous allons voir à présent une méthode qui nous permet de déterminer le nombre dérivé par le calcul. Pour ce faire, nous allons définir la fonction dérivée.

Voici les règles de calcul de la fonction dérivée :

| Domaine de définition | Fonction $f$ | Fonction dérivée $f'$ | Fonction $f$ | Fonction dérivée $f'$ |
|---|---|---|---|---|
| $\mathbb{R}$ | $ax+b$ | $a$ | $6x+2$ | $6$ |
| $\mathbb{R}$ | $x^2$ | $2x$ | | |
| $\mathbb{R}$ | $ax^2$ | $2ax$ | $-3x^2$ | $-6x$ |

> [!propriete] Propriété
> La dérivée d'une somme est égale à la somme des dérivées.

> [!exercice] Exercice 2
> Soit $f:x \mapsto -3x^2+6x+10$.
> 1. Déterminer l'expression de $f'(x)$ la fonction dérivée de $f(x)$.
> 2. En déduire les valeurs de $f'(-1)$, $f'(2)$ et $f'(4)$
> 3. Vérifier les résultats de la question précédente en utilisant géogébra. Vous expliquerez la méthode utilisée.

> [!definition] Définition — Fonction dérivée
> Fonction qui associe à chaque réel $x$ d'une fonction $f$ le coefficient directeur de la tangente en un point de la courbe représentative de $f$. Elle est notée $f'(x)$.

> [!propriete] Propriété
> Le sens de variation dépend du signe de la dérivée :
> - Si $f'(x) = 0$ alors la fonction $f$ est constante.
> - Si $f'(x) > 0$ alors la fonction $f$ est croissante.
> - Si $f'(x) < 0$ alors la fonction $f$ est décroissante.
>
> Si pour une valeur $x_0$, $f'(x_0) = 0$ avec changement de signe, alors la fonction $f$ passe par un extremum $x_0$.

![[tabvar.png]]

> [!rituel] Rituel
> 1. Résoudre $6(x+4) = 12$
> 2. On lance un dé à six faces. Soit A : "Le nombre obtenu est un multiple de 3" et B : "Le nombre obtenu est un multiple de 2".
>    1. Déterminer $p(A\cup B)$
>    2. Déterminer $p(A\cap B)$

> [!correction] Correction
> 1. $6(x+4) = 12 \Rightarrow 6x + 24 = 12 \Rightarrow 6x = -12 \Rightarrow x = -2$.
> 2. $p(A\cup B) = \dfrac{4}{6}$ ; $p(A\cap B) = \dfrac{1}{6}$.

> [!exercice] Exercice 3
> Soit $f:x \mapsto 4x^2-2x+10$.
> 1. Déterminer l'expression de $f'(x)$ la fonction dérivée de $f(x)$.
> 2. Étudier le signe de la fonction $f'(x)$
> 3. En déduire le tableau de variation de $f$

> [!travail] Travail
> En utilisant le tableau de compétences, effectuer le TP suivant. L'utilisation de géogébra est exclusive à la partie valider dans laquelle un graphique vous permettra de valider les résultats obtenus.
>
> Un gérant d'hôtel pense que son entreprise génère le plus de bénéfice quand son taux d'occupation est de 90%. On considère la fonction $f:x\mapsto -x^2+140x-2400$, où $x$ correspond au taux d'occupation de l'hôtel et $f(x)$ le bénéfice réalisé.
>
> **Problématique :** Le gérant de l'hôtel a-t-il raison ?
>
>> [!aide] Aide
>> Dans ce TP, il est important de comprendre le rôle de la fonction.
>> 1. Que permet de faire cette fonction ?
>> 2. Que pourrait-on avoir comme information en obtenant le tableau de variations de cette fonction ?

> [!travail] Travail
> En utilisant le tableau de compétences, effectuer le TP suivant. L'utilisation de géogébra est exclusive à la partie valider dans laquelle un graphique vous permettra de valider les résultats obtenus.
>
> L'entreprise C.S.I.I. produit des articles du domaine informatique pour l'Europe. Le coût de production $C(x)$ exprimé en milliers d'euros pour x articles est donné par la fonction $C$ avec : $C(x) = 0,02 x^2 - 2 x + 98$ pour $x$ appartenant à l'intervalle $[50 ; 150]$.
>
> Le montant des ventes $V(x)$ exprimé en milliers d'euros est pour sa part donné par la fonction $V$ avec $V(x) = 1,5 x$ pour $x$ appartenant à l'intervalle $[50 ; 150]$.
>
> **Problématique :** Le dirigeant de l'entreprise souhaite déterminer pour quel nombre d'articles produits le bénéfice de son entreprise est maximal.
>
>> [!aide] Aide
>> Dans ce TP, il est important de comprendre le rôle de la fonction.
>> 1. Que permet de faire cette fonction ?
>> 2. Que pourrait-on avoir comme information en obtenant le tableau de variations de cette fonction ?
