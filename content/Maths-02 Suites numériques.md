---
chapitre: 2
tags:
  - maths/premiere-bac-pro
---

# Suites numériques

| Compétences | Capacités |
|---|---|
| **S'approprier** | Comprendre la problématique liée au problème |
| **Analyser / Raisonner** | À partir de l'énoncé, identifier la nature d'une suite et ses propriétés.<br>Émettre une hypothèse raisonnable. |
| **Réaliser** | Calculer un terme d'une suite arithmétique.<br>Réaliser la somme d'une suite arithmétique.<br>Utiliser les propriétés de suites pour connaître son sens de variation. |
| **Valider** | Utiliser un programme Python afin de valider un résultat.<br>Utiliser une représentation graphique pour valider un résultat. |
| **Communiquer** | Communiquer les résultats trouvés en utilisant le vocabulaire et les notations adéquats. |

> [!rituel] Rituel
> 1. Résoudre $-3x-4=14$
> 2. Que fait le programme suivant ?
>
> ```python
> i = 2
> while i < 50:
>     print(i)
>     i = i + 2
> ```

> [!correction] Correction
> 1. $-3x-4=14 \Rightarrow -3x = 18 \Rightarrow x = -6$.
> 2. Ce programme affiche tous les nombres pairs strictement inférieurs à 50.

## S'approprier

> [!activite] Activité
> L'architecture de la salle 3000 à Lyon est inspirée des amphithéâtres gallo-romains.
>
> ![[salle3000.jpg|400]]
> ![[3000.jpg|400]]
>
> La salle 3000 comporte 46 places au premier rang et 52 places au deuxième rang. Chaque rang suivant comporte 6 places de plus que le rang précédent.
>
> **Problématique :** Le service de billetterie souhaiterait savoir rapidement le nombre de places pour un rang donné.
>
> 1. Déterminer le nombre de places au troisième et au quatrième rang.
> 2. Déterminer le nombre de places au 23ᵉ rang. Décrire la méthode de calcul que vous avez utilisée.
> - [Vidéo — aide méthode](https://youtu.be/_gLvvida2ZE)
>
> 3. À votre avis, quelle critique peut émettre le service de billetterie à propos de votre méthode ?
> 4. Pourrait-on mettre en place une formule, nous permettant de trouver directement le nombre de places au 23ᵉ rang ?
> - [Vidéo — aide méthode (suite)](https://youtu.be/uqCZsALbdbM)
>
> 5. Déterminer le nombre de places au 12ᵉ et au 19ᵉ rang.
> 6. Déterminer le nombre de places au $n$ᵉ rang. En quoi la formule obtenue peut-elle répondre à la problématique ?

> [!rituel] Rituel
> 1. Calculer $12-19$.
> 2. Calculer $-8-15$.
> 3. Dans la liste 5, 9, 13, 17, quelle est la différence entre deux termes consécutifs ?
> 4. Continuer la liste : 100, 94, 88, 82, … donner les deux termes suivants.

> [!correction] Correction
> 1. $12-19=-7$.
> 2. $-8-15=-23$.
> 3. La différence commune est $4$.
> 4. $76$ puis $70$.

## Analyser

> [!definition] Définition — Suite numérique
> Une suite numérique est une succession de nombres. Ces nombres sont les termes de la suite. Une suite est ordonnée, chaque élément possède un rang. Une suite est désignée par une lettre (usuellement $u$). En mathématiques, la suite $u$ est notée $(u_n)$.

> [!exemple] Exemple
> Voici les cinq premiers termes de la suite $(v_n)$ :
>
> ![[notationsuite.png|400]]

> [!exercice] Exercice 1
> Voici les cinq premiers termes de la suite nommée $u$.
>
> ![[suite2.png|350]]
>
> 1. Donner la notation de la suite $u$
> 2. Quelle est la valeur de $u_3$ ?
> 3. Quel est le rang du terme de valeur 5 ?
> 4. Donner la notation du terme de valeur 20 ?

> [!definition] Définition — Suite arithmétique
> Dans une suite arithmétique, on passe d'un terme au suivant en additionnant toujours le même nombre $r$ que l'on appelle raison.
>
> ![[schemaarithm.png|400]]
>
> On a donc :
>
> ![[rec.png]]

> [!rituel] Rituel
> Déterminer les coordonnées du point d'intersection des droites suivantes :
> 1. $D$ : $y=3x-5$ et $D'$ : $y=-2x+10$
> 2. $D$ : $y=-x+8$ et $D'$ : $y=4x-2$

> [!correction] Correction
> 1. $3x-5=-2x+10 \Rightarrow 5x=15 \Rightarrow x=3$, donc $y=3\times3-5=4$. Point d'intersection : $(3;4)$.
> 2. $-x+8=4x-2 \Rightarrow 10=5x \Rightarrow x=2$, donc $y=-2+8=6$. Point d'intersection : $(2;6)$.

> [!exercice] Exercice 2
> En reprenant le contexte de l'activité sur la salle 3000. On note $(u_n)$, la suite formée par le nombre de places à chaque rang.
> 1. Que représentent les termes $u_1$ et $u_2$ ?
> 2. Donner la valeur de $u_1$ et de $u_2$.
> 3. Expliquer pourquoi la suite $(u_n)$ est une suite arithmétique.
> 4. Utiliser les notations des suites afin de réécrire la formule obtenue à la dernière question.
>
> $$\textrm{"Nombre de places au rang n"} = 46 + (n-1) \times 6$$

> [!propriete] Propriété
> Pour une suite arithmétique $(u_n)$ de premier terme $u_1$ et de raison $r$ on a :
> $$u_n = u_1 + (n-1)\times r$$

> [!exercice] Exercice 3
> Soit $(v_n)$ la suite arithmétique de premier terme $v_1=200$ et de raison $r=-7$.
> 1. Déterminer $v_2$ et $v_3$
> 2. Déterminer $v_{60}$

> [!definition] Définition — Somme des termes d'une suite arithmétique
> Pour une suite arithmétique $(u_n)$, on note $S_n$ la somme de ses $n$ premiers termes :
> $$S_n = u_1+u_2+\cdots+u_n$$

> [!propriete] Propriété
> Pour une suite arithmétique $(u_n)$ de premier terme $u_1$, la somme de ses $n$ premiers termes est :
> $$S_n = n \times \dfrac{u_1+u_n}{2}$$
> (nombre de termes $\times$ la moyenne du premier et du dernier terme.)

> [!exemple] Exemple
> Soit la suite arithmétique de premier terme $u_1=3$ et de raison $r=4$. Calculons la somme $S_{10}$ de ses 10 premiers termes.
>
> On calcule d'abord $u_{10}$ :
> $$u_{10} = 3+(10-1)\times4 = 39$$
> Puis la somme :
> $$S_{10} = 10\times\dfrac{3+39}{2} = 210$$

> [!exercice] Exercice 4
> On reprend la suite $(v_n)$ de l'Exercice 3 ($v_1=200$, $r=-7$).
> 1. Calculer $v_{20}$.
> 2. En déduire la somme $S_{20}$ des 20 premiers termes de cette suite.

> [!rituel] Rituel
> 1. Que fait l'instruction `i = i + 3` dans une boucle ?
> 2. Quelle est la première valeur affichée par ce programme ?
>
> ```python
> i = 5
> while i < 20:
>     print(i)
>     i = i + 5
> ```
>
> 3. Combien de fois la boucle s'exécute-t-elle ?
> 4. Quelle est la dernière valeur affichée ?

> [!correction] Correction
> 1. Elle augmente `i` de 3 à chaque tour de boucle.
> 2. $5$.
> 3. 3 fois.
> 4. $15$.

## Applications

> [!exercice] Exercice 5
> Compléter les commentaires du code Python ci-dessous :
>
> ```python
> # Ce programme permet de ...............................
>
> # ......................................................
> # ......................................................
> raison = 5
> premier_terme = 12
> limite = 300
> n = 1
>
> terme_courant = premier_terme
>
>
> # ......................................................
> # ......................................................
> while terme_courant < limite:
>     print("limite non atteinte", terme_courant, n)
>     #.....................................................
>     #.....................................................
>     terme_courant += raison
>     n += 1
>
> print("limite atteinte", terme_courant, n)
> ```

> [!aide] Aide
> Faire un tableau à 2 colonnes. Dans la première colonne, noter les valeurs prises par `n`. Dans la seconde, noter les valeurs prises par `terme_courant`.
>
> Le programme doit afficher :
> ```
> limite non atteinte 12 1
> limite non atteinte 17 2
> limite non atteinte 22 3
> ...
> limite non atteinte 297 58
> limite atteinte 302 59
> ```

> [!activite] Activité
> Afin de gérer les règlements de nos abonnements (Netflix, téléphone, ...), on place, au mois de janvier, 3000 € sur un compte. Aucune autre opération n'est effectuée sur ce compte. Le montant de l'ensemble de nos abonnements s'élève à 67,30 € par mois. Les prélèvements commencent à partir du mois de février.
>
> **Problématique :** Nous souhaitons savoir à quelle date il ne nous restera que 250 € sur le compte afin d'avoir le temps de prévenir tout découvert.
>
> 1. De quelle somme dispose-t-on sur le compte en janvier, février et mars de la première année.
> 2. Déterminer la nature de la suite formée par le solde du compte de chaque mois.
> 3. Afin de répondre à la problématique, nous allons utiliser le programme de l'exercice précédent. Votre travail consiste à adapter en deux temps :
>    - Premier temps : Souligner/Surligner les lignes nécessitant une modification.
>    - Deuxième temps : Proposer une modification des lignes mises en évidence.
>
> ```python
> raison = 5
> premier_terme = 12
> limite = 300
>
>
> terme_courant = premier_terme
> n = 1
>
> while terme_courant < limite:
>     print("limite non atteinte", terme_courant, n)
>     terme_courant += raison
>     n += 1
>
> print("limite atteinte", terme_courant, n)
> ```

> [!exercice] Exercice 6
> L'entreprise « Condial » spécialisée dans le conditionnement des produits alimentaires envisage de développer sa production. Au mois de décembre 2013, cette entreprise fabrique 45 000 unités pour le conditionnement de boissons. Elle prévoit une augmentation mensuelle de 5 000 unités les mois suivants. On souhaite savoir au bout de combien de mois la production initiale doublera.
> 1. Calculer les productions des quatre premiers mois de l'année 2014.
> 2. Montrer que ces quatre nombres forment une suite arithmétique. Préciser la raison.
> 3. Déterminer pour quel mois de l'année 2014 la production du mois de décembre aura doublé.

> [!exercice] Exercice 7
> Le gérant d'un magasin de vélo compare le chiffre d'affaires réalisé au cours du mois de juillet des trois années 2012, 2013 et 2014.
>
> ![[tabsuite.png]]
>
> 1. Les nombres $C_1$, $C_2$, $C_3$ sont les trois premiers termes d'une suite arithmétique. Préciser la raison de cette suite.
> 2. Le gérant estime que l'évolution de son chiffre d'affaires va suivre cette suite numérique.
>    1. Calculer le terme $C_4$ de cette suite. En déduire le montant du chiffre d'affaires attendu pour juillet 2015.
>    2. Donner le rang « n » du terme $C_n$ tel que $C_n$ = 11 250. Indiquer l'année au cours de laquelle le chiffre d'affaires du mois de juillet aura atteint 11 250 €.

> [!exercice] Exercice 8
> Un client d'un établissement bancaire a souscrit un contrat permettant le versement automatique de 200 €, chaque premier jour d'un mois d'une année, sur un livret d'épargne. Le premier janvier le client possède 1 500 € sur le livret et le versement automatique augmente ce capital de 200 € qui sera donc de 1 700 €. On désigne par $u_1$ ce capital. Les capitaux placés sur le livret après les versements automatiques de février et de mars sont notés $u_2$ et $u_3$.
> 1. Calculer $u_2$ et $u_3$.
> 2. Donner la nature de la suite dont les 3 premiers termes sont $u_1$, $u_2$ et $u_3$. Justifier la réponse et préciser la valeur de la raison.
> 3. Donner la valeur du terme de la suite qui représente le capital placé, immédiatement après le versement du mois de septembre.

> [!rituel] Rituel
> 1. Un capital de 500€ augmente de 4% par an. Quel est le coefficient multiplicateur associé ?
> 2. Calculer le nouveau montant après cette augmentation.
> 3. Une population de 2000 habitants diminue de 10% par an. Quel est le coefficient multiplicateur associé ?
> 4. Calculer la population après cette diminution.

> [!correction] Correction
> 1. $1,04$.
> 2. $500\times1,04=520$€.
> 3. $0,90$.
> 4. $2000\times0,90=1800$ habitants.

> [!exercice] Exercice 9
> On considère la suite numérique $u_1$ = 8 000 ; $u_2$ = 9 200 ; $u_3$ = 10 580.
> 1. Préciser, en justifiant la réponse, s'il s'agit d'une suite arithmétique ou d'une suite géométrique.
> 2. Indiquer la raison de cette suite.
> 3. On considère la suite géométrique. Calculer $u_{10}$ et $u_{20}$.

> [!exercice] Exercice 10
> Une société du secteur des nouvelles technologies prévoit une augmentation de son chiffre d'affaires de 15 % chaque année pendant 6 ans. On note $u_1, u_2, u_3, u_4, u_5, u_6$ la suite formée par les 6 chiffres d'affaires consécutifs.
> 1. Donner le coefficient multiplicateur qui permet de calculer $u_2$ à partir de $u_1$ ; $u_3$ à partir de $u_2$ ; $u_4$ à partir de $u_3$ ; $u_5$ à partir de $u_4$ ; $u_6$ à partir de $u_5$.
> 2. En déduire la nature de la suite (arithmétique ou géométrique) de la suite formée par les 6 chiffres d'affaires consécutifs et donner la valeur de la raison.
> 3. Le chiffre d'affaires, noté $u_1$, de l'année 2014 s'élève à 3 200 000 €. Calculer le chiffre d'affaires prévisionnel, $u_2$, de 2015.
> 4. Calculer le terme $u_6$ de la suite. Donner l'année où le chiffre d'affaires est égal à la valeur du terme $u_6$.
> 5. Confirmer si un doublement du chiffre d'affaires sera réalisé dès 2018 comme l'affirme le PDG de la société. Justifier la réponse.

> [!exercice] Exercice 11
> La population d'un village de montagne diminue tous les ans de 20 %.
> 1. Sachant qu'en 1996 elle était de 1 875 habitants, compléter le tableau suivant :
>
> ![[tabsuite2.png]]
>
> 2. Montrer que les nombres d'habitants sont des termes d'une suite dont on déterminera la nature et la raison.
> 3. Déterminer la population de ce village en 2010.
> 4. Donner l'année d'extinction de ce village si on suppose la diminution de la population constante.

> [!exercice] Exercice 12
> On reprend le contexte de l'activité sur la salle 3000 : 46 places au premier rang, et 6 places de plus à chaque rang suivant.
> 1. Calculer le nombre de places au 30ᵉ rang.
> 2. En déduire la capacité totale de la salle si elle compte 30 rangs.
> 3. La direction hésite à porter la salle à 35 rangs. Calculer la nouvelle capacité totale et indiquer le nombre de places supplémentaires gagnées par rapport à 30 rangs.
