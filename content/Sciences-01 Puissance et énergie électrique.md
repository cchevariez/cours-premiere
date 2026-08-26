---
chapitre: 1
tags:
  - sciences/premiere-bac-pro
---

# Puissance et énergie électrique

> [!rituel] Rituel
> Identifier les différentes grandeurs de cette plaque signalétique et donner de leur unité.
>
> ![[signaletique.png|200]]

> [!correction] Correction
> - $220\,\text{V}$ : Tension en Volt.
> - $7\,\text{A}$ : Intensité en Ampère.
> - $1,54\,\text{kW}$ : Puissance en kilowatt.
> - $50\,\text{Hz}$ : Fréquence en Hertz.

## Grandeurs et mesures

## Grandeurs

> [!definition] Définition — Tension électrique (vulgarisation)
> La tension, de symbole $U$, constitue la "pression" provenant d'une source d'alimentation d'un circuit électrique qui pousse les électrons chargés (le courant) le long d'une boucle conductrice, leur permettant d'accomplir un travail, tel qu'éclairer une ampoule. La tension est mesurée en volts (V).

> [!definition] Définition — Intensité électrique (vulgarisation)
> L'intensité électrique, de symbole $I$, mesure combien d'électrons passent à un endroit donné dans un circuit en une seconde. Elle se mesure en ampères (ou simplement "ampères", symbolisés par $A$).

> [!exercice] Exercice 1
> Faisons une analogie entre le courant électrique et un courant d'eau. Pour chaque montage, qualifier de forte ou faible son intensité et sa tension.
>
> ![[tension-intensite.png]]
>
> Si on insérait un robinet sur chaque tube reliant les deux béchers, comment nommerait-on ce robinet dans un circuit électrique ?

> [!exercice] Exercice 2 — Application - Conversions d'unités électriques
> Effectuer les conversions d'unités suivantes :
> 1. Convertir 250 mV en V
> 2. Convertir 1,5 kW en W
> 3. Convertir 0,045 A en mA
> 4. Convertir 2500 Hz en kHz
> 5. Convertir 750 W en kW

> [!correction] Correction
> 1. $250\,\text{mV} = 0,25\,\text{V}$
> 2. $1,5\,\text{kW} = 1500\,\text{W}$
> 3. $0,045\,\text{A} = 45\,\text{mA}$
> 4. $2500\,\text{Hz} = 2,5\,\text{kHz}$
> 5. $750\,\text{W} = 0,75\,\text{kW}$

## Mesures

Pour mesurer la tension et l'intensité, on utilise un multimètre. Comme son nom l'indique un multimètre possède de multiples fonctions.

![[multi.png|200]]

Pour mesurer une tension, on se branche en dérivation du dipôle dont on veut mesurer la tension. Voici une image d'illustration :

![[mesure-tension.png|500]]

Voici le schéma électrique correspondant à cette situation :

![[tension-circuit.png|200]]

Pour mesurer une intensité, on branche le multimètre en série. Voici une image d'illustration :

![[mesure-intensite.png|500]]

Voici le schéma électrique correspondant à cette situation :

![[intensite-circuit.png|300]]

> [!travail] Travail
> On souhaite mesurer la tension aux bornes d'une résistance.
>
> 1. Compléter le schéma suivant avec les symboles des appareils de mesure appropriés.
>
> ![[elec-tp1.png|400]]
>
> 2. À l'aide du matériel fourni, réaliser le montage ci-dessous. **Appeler votre professeur avant de mettre le circuit sous tension**.
> 3. On appelle puissance, notée $P$, le produit de la tension $U$ (en Volt) et de l'intensité $I$ (en ampères). $$P = U \times I$$ L'unité de la puissance est le Watt ($W$). Déterminer la puissance de la résistance.

> [!exercice] Exercice 3 — Application directe de $P = U \times I$
> Pour chacun des circuits ci-dessous, calculer la grandeur manquante à l'aide de la formule $P = U \times I$.
>
> ```
>  a)                          b)
>   ┌─────[A]─────┐             ┌─────[A]─────┐
>   │    2 A      │             │    5 A      │
>  (—) 12 V        R           (—) U = ?      Moteur
>   │              │             │            P = 60 W
>   └──────────────┘             └─────────────┘
> ```
>
> 1. Circuit a) : $U = 12\,\text{V}$, $I = 2\,\text{A}$. Calculer $P$.
> 2. Circuit b) : $P = 60\,\text{W}$, $I = 5\,\text{A}$. Calculer $U$.
> 3. Une lampe de $100\,\text{W}$ est branchée sous une tension de $230\,\text{V}$. Calculer l'intensité $I$ qui la traverse.
> 4. Un radiateur électrique est parcouru par un courant de $8\,\text{A}$ sous une tension de $230\,\text{V}$. Calculer sa puissance.

> [!correction] Correction
> 1. $P = 12\times2 = 24\,\text{W}$.
> 2. $U = \dfrac{P}{I} = \dfrac{60}{5} = 12\,\text{V}$.
> 3. $I = \dfrac{P}{U} = \dfrac{100}{230} \approx 0,43\,\text{A}$.
> 4. $P = 230\times8 = 1840\,\text{W}$.

> [!exercice] Exercice 4
> Voici l'installation électrique d'un salon de coiffure. Le Consuel (COmité National pour la Sécurité des Usagers de l'ELectricité) doit passer afin de vérifier l'installation. Vous disposez du tableau de la norme NFC, que toutes les installations doivent respecter, ainsi qu'un schéma du tableau divisionnaire du salon. À l'aide de ces documents, indiquer les changements nécessaires à effectuer afin que le Consuel valide l'installation. Chaque modification à effectuer doit être soigneusement justifiée.
>
> ![[norme.png|400]]
>
> ![[tableaudiv.png|400]]

## Énergie

> [!definition] Définition — Énergie
> L'énergie électrique est la capacité d'un système électrique à effectuer un travail, comme allumer une lampe ou faire fonctionner un appareil. Elle est calculée en fonction de la puissance consommée et du temps pendant lequel cette puissance est utilisée.
>
> L'unité SI de l'énergie électrique est le joule (J), mais dans le contexte domestique, on utilise plus couramment le kilowattheure (kWh). Un joule correspond à une consommation de un Watt pendant une seconde. Un kilowattheure correspond à l'énergie consommée par un appareil de 1000 watts fonctionnant pendant une heure. On a donc la formule :
> $$E = P \times t$$

> [!exercice] Exercice 5 — Application directe de $E = P \times t$
> À l'aide de la formule $E = P \times t$, répondre aux questions suivantes (attention aux unités : pour obtenir $E$ en Joule, $t$ doit être en secondes).
> 1. Un four de $2000\,\text{W}$ fonctionne pendant $15\,\text{min}$. Calculer l'énergie consommée en Joule.
> 2. Une ampoule de $9\,\text{W}$ reste allumée pendant $4\,\text{h}$. Calculer l'énergie consommée en Wh puis en kWh.
> 3. Un chargeur de téléphone consomme $18\,\text{Wh}$ pour une charge complète de $2\,\text{h}$. Calculer sa puissance.
> 4. Un radiateur de $1500\,\text{W}$ doit fournir une énergie de $3\,\text{kWh}$. Pendant combien de temps doit-il fonctionner ?

> [!correction] Correction
> 1. $t=15\,\text{min}=900\,\text{s}$, donc $E=2000\times900=1\,800\,000\,\text{J}=1,8\,\text{MJ}$.
> 2. $E = 9\times4=36\,\text{Wh}=0,036\,\text{kWh}$.
> 3. $P=\dfrac{E}{t}=\dfrac{18}{2}=9\,\text{W}$.
> 4. $t=\dfrac{E}{P}=\dfrac{3000}{1500}=2\,\text{h}$.

> [!travail] Travail
> Voici les informations concernant un vélo électrique :
>
> ![[velo5.png|400]]
>
> - Batterie $36V/760Wh$
> - Puissance du moteur : $250W$
> - Chargeur : $40V/3A$
>
> 1. Calculer, en Joule, l'énergie consommée pendant une balade de 1h30min.
> 2. Le Joule est-il l'unité la plus adaptée à cette situation ? Proposer une alternative si besoin.
> 3. On décide de faire une balade de 3h. L'assistance du vélo sera-t-elle disponible pendant toute la balade ? (justifier par le calcul)
> 4. La batterie du vélo est totalement déchargée. Pendant combien de temps faut-il la charger afin qu'elle soit à nouveau totalement pleine.
> 5. Sachant que le prix de l'électricité est
>    - 0.1711 € en heures pleines
>    - 0.1321 € en heures creuses
>
>    Déterminer le coût de cette recharge en heures pleines et en heures creuses.

## Problèmes de synthèse

> [!exercice] Problème de synthèse 1 — Installation électrique d'un atelier de menuiserie
> Un atelier de menuiserie est alimenté sous une tension de $230\,\text{V}$, protégé par un disjoncteur de calibre $16\,\text{A}$. Quatre appareils peuvent fonctionner simultanément :
>
> ```
>                         Disjoncteur 16 A
>                                │
>       ┌─────────────┬─────────┴─────────┬─────────────┐
>       │             │                   │             │
>    [Scie]      [Perceuse]         [Aspirateur]   [Éclairage]
>   I = 6 A       P = 690 W           I = 4 A        P = 460 W
>       │             │                   │             │
>      230 V         230 V               230 V         230 V
> ```
>
> 1. Calculer la puissance de la scie circulaire et de l'aspirateur d'atelier.
> 2. Calculer l'intensité appelée par la perceuse à colonne et par l'éclairage.
> 3. En déduire la puissance totale, puis l'intensité totale appelée lorsque les quatre appareils fonctionnent en même temps.
> 4. Le disjoncteur de calibre 16 A va-t-il déclencher ? Justifier.
> 5. Un menuisier branche en plus un chauffage d'appoint de $460\,\text{W}$. Le disjoncteur déclenche-t-il maintenant ? Justifier par le calcul.
> 6. L'atelier fonctionne 6h par jour, 5 jours par semaine (sans le chauffage d'appoint). Calculer l'énergie consommée en une semaine, en kWh.
> 7. Sachant que le prix du kWh est de $0,1711\,\text{€}$, calculer le coût hebdomadaire de fonctionnement de l'atelier.

> [!correction] Correction
> 1. Scie : $P=230\times6=1380\,\text{W}$. Aspirateur : $P=230\times4=920\,\text{W}$.
> 2. Perceuse : $I=\dfrac{690}{230}=3\,\text{A}$. Éclairage : $I=\dfrac{460}{230}=2\,\text{A}$.
> 3. $P_{totale}=1380+690+920+460=3450\,\text{W}$. $I_{totale}=6+3+4+2=15\,\text{A}$.
> 4. $15\,\text{A} < 16\,\text{A}$ : le disjoncteur ne déclenche pas (marge faible, seulement $1\,\text{A}$).
> 5. Chauffage : $I=\dfrac{460}{230}=2\,\text{A}$. Nouvelle intensité totale : $15+2=17\,\text{A} > 16\,\text{A}$ : le disjoncteur déclenche.
> 6. $P_{totale}=3,45\,\text{kW}$. Temps hebdomadaire : $6\times5=30\,\text{h}$. $E=3,45\times30=103,5\,\text{kWh}$.
> 7. Coût $=103,5\times0,1711\approx17,71\,\text{€}$.

> [!exercice] Problème de synthèse 2 — Ampoule incandescente ou LED ?
> On souhaite remplacer une ampoule incandescente par une ampoule LED équivalente. L'ampoule est utilisée en moyenne $4\,\text{h}$ par jour, $365$ jours par an. Le prix du kWh est de $0,1711\,\text{€}$.
>
> | | Ampoule incandescente | Ampoule LED |
> |---|---|---|
> | Puissance | 60 W | 9 W |
> | Prix d'achat | 1 € | 6 € |
> | Durée de vie | 1000 h | 15 000 h |
>
> 1. Calculer l'énergie consommée par chaque ampoule sur $15\,000\,\text{h}$ d'utilisation, en kWh.
> 2. En déduire le coût de l'électricité consommée par chaque ampoule sur ces $15\,000\,\text{h}$.
> 3. Combien d'ampoules incandescentes faut-il acheter pour couvrir $15\,000\,\text{h}$ d'utilisation (durée de vie d'une seule LED) ? En déduire le coût d'achat total des ampoules incandescentes.
> 4. En tenant compte du prix d'achat et du coût de l'électricité, comparer le coût total sur $15\,000\,\text{h}$ des deux solutions. Laquelle est la plus économique ? Justifier.

> [!correction] Correction
> 1. Incandescente : $E=60\times15\,000=900\,000\,\text{Wh}=900\,\text{kWh}$. LED : $E=9\times15\,000=135\,000\,\text{Wh}=135\,\text{kWh}$.
> 2. Incandescente : $900\times0,1711\approx153,99\,\text{€}$. LED : $135\times0,1711\approx23,10\,\text{€}$.
> 3. $\dfrac{15\,000}{1000}=15$ ampoules. Coût d'achat : $15\times1=15\,\text{€}$.
> 4. Incandescente : $153,99+15=168,99\,\text{€}$. LED : $23,10+6=29,10\,\text{€}$. La LED est nettement plus économique (environ $140\,\text{€}$ d'économie sur la durée).

**Tester vos connaissances :** [Quiz en ligne (Quiziniere)](https://www.quiziniere.com/diffusions/6K5PEM)
