---
tags:
  - maths/premiere-bac-pro
  - fiche-methode
---

# Python : Exercices supplémentaires

### Type 1 : Analyser le code

> [!exercice] Exercice 1
> Que fait le code suivant :
> ```python
> i = 0
>
> while i < 10:
>   print(i)
>   i += 3
>
> print("Boucle terminee")
> ```

> [!exercice] Exercice 2
> Que fait le code suivant :
> ```python
> i = 10
>
> while i < 5:
>   print(i)
>   i += 1
>
> print("Fin du programme")
> ```

> [!exercice] Exercice 3
> Que fait le code suivant :
> ```python
> i = 0
>
> while i >= 0:
>   print(i)
>   i += 2
>
> print("Boucle terminee")
> ```

> [!exercice] Exercice 4
> Que fait le code suivant :
> ```python
> i = 10
> compteur = 0
>
> while i > 0:
>   print("Tour numero", compteur)
>   print("Valeur de i :", i)
>   i -= 1
>   compteur += 1
>
> print("Boucle terminee")
> ```

> [!exercice] Exercice 5
> Que fait le code suivant :
> ```python
> i = 1
> j = 10
>
> while i < j:
>   print("i =", i, ", j =", j)
>   i += 2
>   j -= 1
>
> print("Boucle terminee")
> ```

### Type 2 : Écrire le code

> [!exercice] Exercice 6
> On souhaite afficher les nombres de 1 à 5 avec un message personnalisé pour chaque nombre. Voici le résultat attendu :
>
> ```
> 4
> 8
> 12
> 16
> 20
>
> C'est fini !
> ```
>
> Écrivez un programme Python utilisant une boucle `while` pour obtenir ce résultat.

> [!exercice] Exercice 7
> Un programme affiche les valeurs suivantes lors de son exécution :
>
> ```
> 5
> 4
> 3
> 2
> 1
> Fini!
> ```
>
> Écrivez un programme Python utilisant une boucle `while` avec un compteur pour reproduire cet affichage.

> [!exercice] Exercice 8
> En 2024, on dispose d'un compte dont le solde est 2500 €. On ajoute, par versements automatiques, 800 € par an sur ce compte. Écrire un programme Python permettant d'afficher les éléments suivants :
>
> ```
> 2024  solde :  2500
> 2025  solde :  3300
> 2026  solde :  4100
> 2027  solde :  4900
> 2028  solde :  5700
> On dépasse un solde de 6000 euros l'année 2029
> ```
