---
chapitre: 4
tags:
  - maths/premiere-bac-pro
---

# Probabilités

## S'approprier

Dans cette partie, nous allons nous approprier le langage probabiliste.

> [!activite] Activité
> Un voleur vole une carte bleue. Ne connaissant pas le code, il décide tout de même de retirer de l'argent avec cette dernière.
> 1. Sachant qu'un code de carte bleue est composé de quatre chiffres. Déterminer quel est le nombre de codes possibles.
> 2. En déduire la probabilité de réussite de ce voleur.
>
> Si vous êtes le genre de personne à cacher d'une main le clavier des distributeurs de banque pour éviter qu'on ne voit votre code secret grâce à une petite caméra planquée dans un coin : bravo !
> Mais cela ne suffit plus vraiment car des chercheurs ont mis au point une technique assez simple qui utilise une caméra thermique, qui permet simplement en filmant le clavier du distributeur, de deviner le code utilisé par la personne qui vient juste de passer.
>
> ![[thermique.jpg]]
>
> 1. Expliquer pourquoi certaines touches du clavier ressortent à la caméra thermique.
> 2. En utilisant cette technique, déterminer quel est le nombre de codes possibles.
> 3. En déduire la probabilité de réussite de ce voleur high-tech.

> [!definition] Définition — Univers
> On appelle univers l'ensemble des issues possibles d'une expérience aléatoire. On appelle aussi cardinal de l'univers le nombre de ces issues.

> [!definition] Définition — Événement
> Un événement est une partie de l'univers, formée d'une ou de plusieurs issues possibles. On appelle cardinal d'un évènement le nombre de ses issues.

> [!rituel] Rituel
> 1. Si on augmente un prix de 10%, on le multiplie par :
> 2. Si on baisse un prix de 15%, on le multiplie par :
> 3. Un article a été soldé à -30%, son prix soldé est 47 €. Quel était son prix avant les soldes ?

> [!correction] Correction
> 1. Coefficient multiplicateur : $1.1$.
> 2. Coefficient multiplicateur : $0.85$.
> 3. $\dfrac{47}{0.7} = 67.14$ €.

> [!exercice] Exercice 1
> En reprenant ces définitions et l'activité précédente (carte de crédit et caméra thermique) répondre aux questions suivantes :
> 1. Dans le cas où le voleur n'utilise pas de caméra thermique, exprimer sous la forme d'une phrase l'univers de cette expérience. Déterminer le cardinal de cet univers.
> 2. Même question dans le cas du voleur utilisant une caméra ?

> [!activite] Activité
> À la rentrée scolaire, on fait une enquête dans les classes de terminale baccalauréat professionnel. 30% des élèves ont 17 ans, 45% ont 18 ans et les autres 19 ans et plus. De plus on a déterminé que 3/4 des élèves de 17 ans souhaitaient poursuivre en BTS ainsi que les 2/3 des élèves de 18 ans et la moitié des élèves de 19 ans et plus.
> 1. Compléter l'arbre des issues possibles.
>
> ![[arbre.png]]
>
> 2. On choisit un étudiant au hasard.
>    1. Quelle est la probabilité de choisir un étudiant de 18 ans ayant envie de poursuivre en BTS ?
>    2. Quelle est la probabilité de choisir un étudiant de 17 ans n'ayant pas envie de poursuivre en BTS ?
>    3. Quelle est la probabilité de choisir un étudiant qui souhaite poursuivre en BTS ?
>    4. Quelle est la probabilité de choisir un étudiant de 17 ou 18 ans choisissant de poursuivre en BTS ?

> [!definition] Définition — Intersection
> Soit deux évènements $A$ et $B$. On appelle intersection de l'évènement $A$ et $B$, l'évènement $C$ où $A$ **et** $B$ se réalise. On note :
> $$ C = A \cap B $$

> [!definition] Définition — Union
> Soit deux évènements $A$ et $B$. On appelle union de l'évènement $A$ et $B$, l'évènement $C$ où $A$ **ou** $B$ se réalise. On note :
> $$ C = A \cup B $$

> [!definition] Définition — Incompatible
> Soit deux évènements $A$ et $B$. $A$ et $B$ sont dit incompatible si :
> $$ A \cap B = \varnothing$$

> [!definition] Définition — Contraire
> Soit un évènement $A$. On note $\overline{A}$ l'évènement contraire de $A$. On a :
> $$ p(\overline{A}) = 1 - p(A)$$

> [!exercice] Exercice 2
> En reprenant les définitions et l'activité précédente on note :
> - $A$ : On choisit un étudiant de 17 ans.
> - $B$ : On choisit un étudiant de 18 ans.
> - $C$ : On choisit un étudiant de 19 ans et plus.
> - $D$ : On choisit un étudiant qui désire poursuivre en BTS.
> - $E$ : On choisit un étudiant qui ne désire pas poursuivre en BTS.
>
> 1. Exprimer sous la forme d'une phrase $A \cup B$, puis calculer $p(A \cup B)$.
> 2. Exprimer sous la forme d'une phrase $A \cap E$, puis calculer $p(A \cap E)$.
> 3. Exprimer sous la forme d'une phrase $A \cap C$, puis calculer $p(A \cap C)$.
> 4. Exprimer sous la forme d'une phrase $A \cup B \cup C$, puis calculer $p(A \cup B \cup C)$.
> 5. Exprimer sous la forme d'une phrase $\overline{A}$, puis calculer $p(\overline{A})$.
> 6. Exprimer sous la forme d'une phrase $\overline{A \cup B}$, puis calculer $p(\overline{A \cup B})$.

> [!exercice] Exercice 3
> À la sortie d'une rencontre de football opposant Paris à Marseille, des supporters attendent les joueurs pour des autographes. Une première personne sort des vestiaires.
> On considère l'évènement A "la personne qui sort est un arbitre" et B "la personne qui sort est un joueur de Marseille".
> 1. Les évènements A et B sont-ils compatibles ?
> 2. Si on considère que seuls des arbitres ou des joueurs peuvent sortir du vestiaire. Quel est l'évènement contraire de B ?

> [!propriete] Propriété
> Soit $A$ et $B$ deux événements indépendants alors :
> $$p(A \cap B) = p(A) \times p(B)$$

> [!propriete] Propriété
> Soit $A$ et $B$ deux évènements du même univers alors :
> $$p(A \cup B) = p(A) + p(B) - p(A \cap B)$$

> [!activite] Activité
> Une étude statistique, menée auprès d'un échantillon représentatif de familles, concernant l'équipement de cuisine, a donné les résultats suivants :
> - 80% ont un four à micro-ondes
> - 30% ont un lave-vaisselle
> - 15% n'ont ni four à micro-ondes ni lave-vaisselle.
>
> On choisit une famille de l'échantillon au hasard.
> 1. On note :
>    - $M$ l'évènement "la famille possède un micro-ondes."
>    - $L$ l'évènement "la famille possède un lave-vaisselle"
>    1. Que représente l'évènement $\overline{M}$ ?
>    2. Que représente l'évènement $M \cup L$ ?
> 2. Calculer $p(M \cup L)$

> [!rituel] Rituel
> On considère la droite de régression $y = 1500x + 6000$. Où $x$ représente le numéro de l'année et $y$ le CA d'une entreprise.
> 1. Déterminer le CA de l'entreprise l'année 12.
> 2. Déterminer en quelle année le CA de l'entreprise dépassera 30000 euros.

> [!correction] Correction
> 1. $y = 1500\times12+6000 = 18600$ €.
> 2. $30000 = 1500x + 6000 \Rightarrow 1500x = 24000 \Rightarrow x = \dfrac{24000}{1500} = 16$.

> [!exercice] Exercice 4
> Une gare SNCF possède deux guichets A et B dont l'un au moins des deux est ouvert. On considère les évènements A et B suivants :
> - $A$ : "le guichet A est ouvert"
> - $B$ : "le guichet B est ouvert"
>
> Une étude statistique a permis d'établir les probabilités suivantes :
> - $p(A) = 0,75$
> - $p(B) = 0,5$
>
> 1. Donner la signification de $A\cup B$ et déterminer $p(A\cup B)$.
> 2. Calculer la probabilité que les deux guichets soient ouverts. On utilisera la formule $p(A \cup B) = p(A) + p(B) - p(A \cap B)$.

> [!exercice] Exercice 5
> Les organismes de Sécurité sociale peuvent effectuer des contrôles aléatoires auprès des salariés lorsqu'ils sont en arrêt de travail pour raison médicale. Un médecin, assermenté par la Sécurité sociale, se rend au domicile du malade pour vérifier les raisons de son arrêt.
> Dans un département, il existe 3 médecins pour 50 000 salariés.
> 1. Le pourcentage de salariés en arrêt de travail est en moyenne de 6%. Combien de salariés sont potentiellement arrêtés pour raison médicale ?
> 2. Si le contrôle par les médecins se fait de façon aléatoire, quelle est la probabilité pour un salarié en arrêt de travail d'être contrôlé si un médecin peut voir 10 salariés par jour ?
> 3. Dans 90% des cas les médecins de la Sécurité sociale confirment l'arrêt de travail prescrit par le médecin traitant. Quelle est la probabilité pour que l'on demande à un salarié de reprendre le travail suite à un contrôle ?

> [!exercice] Exercice 6
> On tire au hasard une carte dans un jeu de 52 cartes.
> 1. Quelle est la probabilité d'obtenir un cœur ?
> 2. Quelle est la probabilité d'obtenir une figure ?
> 3. Quelle est la probabilité d'obtenir une figure qui soit un cœur ?
> 4. En utilisant la formule $p(A \cup B) = p(A) + p(B) - p(A \cap B)$, déterminer quelle est la probabilité d'obtenir un cœur ou une figure ?

> [!travail] Travail
> L'objectif de cet exercice est de calculer des probabilités concernant la confiance qu'accordent les Français aux médicaments homéopathiques.
> Voici les résultats d'un sondage téléphonique réalisé auprès de 1 000 personnes entre le 5 et le 11 janvier de l'an dernier :
> - 770 personnes font confiance aux médicaments homéopathiques ;
> - 350 personnes ont utilisé au moins une fois des médicaments homéopathiques ;
> - 80% des personnes ayant utilisé au moins une fois des médicaments homéopathiques leur font confiance.
>
> 1. Compléter ci-dessous le tableau récapitulant les résultats de ce sondage.
>
> ![[tabproba.png]]
>
> On choisit une personne au hasard parmi les personnes interrogées et on considère les deux événements suivants :
> - Événement A : « la personne choisie fait confiance aux médicaments homéopathiques » ;
> - Événement B : « la personne choisie n'a jamais utilisé de médicaments homéopathiques ».
>
> **Problématique :** Déterminer la probabilité de l'évènement : « la personne choisie ne fait pas confiance aux médicaments homéopathiques ou n'en a jamais utilisé »

> [!rituel] Rituel
> Répondre aux questions suivantes :
> 1. Calculer 60% de 4500 euros :
> 2. Calculer 20% de 80% de 3000 euros :
> 3. Votre salaire est de 1450 euros, quel sera votre nouveau salaire si on vous augmente de 8% :

> [!exercice] Exercice 7
> Une entreprise fabrique 20 000 sièges pour voitures par an dans deux usines. La production de l'usine A est 12 000 sièges par an et celle de l'usine B, 8 000 sièges par an.
> Des contrôles qualité ont montré que 2% des sièges fabriqués dans l'usine A et 1% des sièges fabriqués dans l'usine B sont défectueux.
> L'objectif de cet exercice est de calculer la probabilité p qu'un siège prélevé au hasard dans la production soit défectueux.
> On considère les événements suivants :
> - évènement A : « le siège prélevé provient de l'usine A »
> - évènement B : « le siège prélevé provient de l'usine B »
> - évènement D : « le siège prélevé est défectueux ».
>
> 1. Calculer la probabilité $p(A)$.
> 2. Définir en une phrase l'évènement $\overline{D}$
> 3. Donner la probabilité $p_1$ pour que le siège prélevé soit défectueux s'il provient de l'usine A.
> 4. Compléter l'arbre des probabilités ci-dessous.
>
> ![[arbreproba.png]]
>
> 5. Calculer la probabilité $p$ qu'un siège prélevé au hasard soit défectueux.
