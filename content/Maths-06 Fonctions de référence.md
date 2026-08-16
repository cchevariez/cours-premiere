---
chapitre: 6
tags:
  - maths/premiere-bac-pro
---

# Fonctions de référence

## Fonctions de référence

### Fonctions carré

> [!definition] Définition — Fonction carré
> La fonction carré est définie par $f : x \longmapsto x^2$. Son domaine de définition est $D_{f} = [ -\infty ; +\infty ]$.

> [!exercice] Exercice 1
> Compléter le tableau de valeurs de la fonction $f(x)=x^2$.
>
> | $x$ | -5 | -4 | -3 | -2 | -1 | 0 | 1 | 2 | 3 | 4 | 5 |
> |---|---|---|---|---|---|---|---|---|---|---|---|
> | $f(x)$ | | | | | | | | | | | |
>
> Placer les points sur le repère ci-dessous puis tracer la courbe de la fonction carré.
>
> ![[repcarre.png]]

On peut donc en déduire le tableau de variation suivant :

| $x$ | $-\infty$ | | $0$ | | $+\infty$ |
|---|:---:|:---:|:---:|:---:|:---:|
| Variations de $f$ | $+\infty$ | ↘ | $0$ | ↗ | $+\infty$ |

### Fonctions cube

> [!definition] Définition — Fonction cube
> La fonction cube est définie par $f : x \longmapsto x^3$. Son domaine de définition est $D_{f} = [ -\infty ; +\infty ]$.

> [!exercice] Exercice 2
> Compléter le tableau de valeurs de la fonction $f(x)=x^3$.
>
> | $x$ | -1,5 | -1,25 | -1 | -0,75 | -0,5 | 0 | 0,5 | 0,75 | 1 | 1,25 | 1,5 |
> |---|---|---|---|---|---|---|---|---|---|---|---|
> | $f(x)$ | | | | | | | | | | | |
>
> Placer les points sur le repère ci-dessous puis tracer la courbe de la fonction cube.
>
> ![[repcube.png]]

On peut donc en déduire le tableau de variation suivant :

| $x$ | $-\infty$ | | $+\infty$ |
|---|:---:|:---:|:---:|
| Variations de $f$ | $-\infty$ | ↗ | $+\infty$ |

### Fonctions inverse

> [!definition] Définition — Fonction inverse
> La fonction inverse est définie par $f : x \longmapsto \dfrac{1}{x}$. Son domaine de définition est $D_{f} = [ -\infty ;0[ \cup ] 0; +\infty ]$.

> [!exercice] Exercice 3
> Compléter le tableau de valeurs de la fonction $f(x)=\dfrac{1}{x}$.
>
> | $x$ | -2 | -1 | -0,75 | -0,5 | -0,25 | 0,25 | 0,5 | 0,75 | 1 | 2 |
> |---|---|---|---|---|---|---|---|---|---|---|
> | $f(x)$ | | | | | | | | | | |
>
> Placer les points sur le repère ci-dessous puis tracer la courbe de la fonction inverse.
>
> ![[repcube.png]]

On peut donc en déduire le tableau de variation suivant :

| $x$ | $-\infty$ | | $0$ | | $+\infty$ |
|---|:---:|:---:|:---:|:---:|:---:|
| Variations de $f$ | $0$ | ↘ | $-\infty$ ‖ $+\infty$ | ↘ | $0$ |

### Fonctions racine carrée

> [!definition] Définition — Fonction racine carrée
> La fonction racine carrée est définie par $f : x \longmapsto \sqrt{x}$. Son domaine de définition est $D_{f} = [ 0; +\infty ]$.

> [!exercice] Exercice 4
> Compléter le tableau de valeurs de la fonction $f(x)=\sqrt{x}$.
>
> | $x$ | 0 | 0,25 | -0,5 | 1 | 2 | 3 | 4 | 5 | 6 | 7 |
> |---|---|---|---|---|---|---|---|---|---|---|
> | $f(x)$ | | | | | | | | | | |
>
> Placer les points sur le repère ci-dessous puis tracer la courbe de la fonction racine carrée.
>
> ![[repracine.png]]

On peut donc en déduire le tableau de variation suivant :

| $x$ | $0$ | | $+\infty$ |
|---|:---:|:---:|:---:|
| Variations de $f$ | $0$ | ↗ | $\infty$ |

## Fonctions de la forme $kf$

> [!propriete] Propriété
> On considère une fonction $f$. La fonction $kf$ dont le sens de variation est :
> - identique à celui de $f$ si $k>0$
> - contraire à celui de $f$ si $k<0$

> [!exercice] Exercice 5
> Donner les tableaux de variations des fonctions suivantes :
> $$
> \begin{align*}
> f(x) &= -2x^2 \\
> g(x) &= \dfrac{7}{x}\\
> h(x) &= -8 \sqrt{x}\\
> i(x) &= 9x^{3}
> \end{align*}
> $$

## Fonction de la forme $f+g$

> [!definition] Définition — Fonction de la forme $f+g$
> La somme $f+g$ des fonctions $f$ et $g$ est la fonction définie par :
> $$ f+g : x \longmapsto f(x) + g(x)$$

La représentation graphique $C_{f+g}$ de la fonction $f+g$ est obtenue point par point à partir des courbes $C_f$ et $C_g$ représentatives des fonctions $f$ et $g$ : pour une abscisse $x_1$ donnée, l'ordonnée du point de la courbe $C_{f+g}$ s'obtient en additionnant les ordonnées $f(x_1)$ et $g(x_1)$ des points des courbes $C_f$ et $C_g$.

![[cfg.png]]

> [!propriete] Propriété
> Sens de variation de la fonction $f+g$ :
> - Si $f$ et $g$ sont deux fonctions croissantes sur un intervalle $I$, la fonction $f+g$ est croissante sur cet intervalle.
> - Si $f$ et $g$ sont deux fonctions décroissantes sur un intervalle $I$, la fonction $f+g$ est décroissante sur cet intervalle.

> [!exercice] Exercice 6
> Donner le tableau de variation de la fonction $f(x)= x^2 + \sqrt{x}$

## Inéquations de la forme $f(x) \geq 0$ et $f(x) \geq g(x)$

Les solutions de l'inéquation $f(x) \geq 0$ sont les valeurs des abscisses des points de la courbe représentative de $f$ au-dessus de l'axe des abscisses.

> [!exercice] Exercice 7
> À l'aide de la courbe représentative de la fonction $f$ résoudre graphiquement $f(x) \geq 0$.
>
> ![[courbef.png]]

Les solutions de l'inéquation $f(x) \geq g(x)$ sont les valeurs des abscisses des points de la courbe représentative de $f$ se situant au-dessus ou sur la courbe représentative de $g$.

> [!exercice] Exercice 8
> À l'aide des courbes représentatives des fonctions $f$ et $g$ résoudre graphiquement $f(x) \geq g(x)$.
>
> ![[courbefg.png]]

> [!exercice] Exercice 9
> Pour chacune des fonctions donner :
> - L'impact de chacun des nombres sur la courbe de la fonction carré.
> - Le tableau de variation de la fonction.
>
> 1. $f(x) = x^2 + 5$
>
>   5 décale la courbe de 5 unités vers le haut.
>
>   | $x$ | $-\infty$ | | $0$ | | $+\infty$ |
>   |---|:---:|:---:|:---:|:---:|:---:|
>   | Variations de $f$ | $+\infty$ | ↘ | $5$ | ↗ | $+\infty$ |
>
> 2. $g(x) = -2x^3$
>
>   -2 inverse le sens de variation de la fonction $x^2$.
>
>   | $x$ | $-\infty$ | | $+\infty$ |
>   |---|:---:|:---:|:---:|
>   | Variations de $g$ | $+\infty$ | ↘ | $-\infty$ |
>
> 3. $h(x) = \sqrt{x-6}$
>
>   -6 décale la courbe de 6 unités vers la droite.
>
>   | $x$ | $6$ | | $+\infty$ |
>   |---|:---:|:---:|:---:|
>   | Variations de $h$ | $0$ | ↗ | $\infty$ |
>
> 4. $i(x) = (x+2)^2-6$
>   - 2 décale la courbe de 2 unités vers la gauche
>   - -6 décale la courbe de 6 unités vers le bas
>
>   | $x$ | $-\infty$ | | $-2$ | | $+\infty$ |
>   |---|:---:|:---:|:---:|:---:|:---:|
>   | Variations de $i$ | $+\infty$ | ↘ | $-6$ | ↗ | $+\infty$ |
>
> 5. $h(x) = \dfrac{1}{x-6}$
>
>   -6 décale la courbe de 6 unités vers la droite.
>
>   | $x$ | $-\infty$ | | $6$ | | $+\infty$ |
>   |---|:---:|:---:|:---:|:---:|:---:|
>   | Variations de $h$ | $0$ | ↘ | $-\infty$ ‖ $+\infty$ | ↘ | $0$ |
>
> 6. $h(x) = -2(x-4)^2+5$
>   - -2 inverse le sens de variation de la fonction
>   - -4 décale la courbe de 4 unités vers la droite
>   - 5 décale la courbe de 5 unités vers le haut
>
>   | $x$ | $-\infty$ | | $4$ | | $+\infty$ |
>   |---|:---:|:---:|:---:|:---:|:---:|
>   | Variations de $h$ | $+\infty$ | ↗ | $5$ | ↘ | $+\infty$ |
