---
tags:
  - maths/premiere-bac-pro
  - fiche-methode
---

# Python : La boucle While

## Les opérateurs `+=` et `-=`

Dans un code, vous verrez souvent les opérateurs `+=` ou `-=`. Ces deux opérateurs permettent d'incrémenter (augmenter une variable d'une valeur) ou de décrémenter (diminuer une variable d'une valeur).

> [!exercice] Exercice 1
> Que fait chacun des codes suivants :
> ```python
> i = 9
> print(i)
> i += 12
> print(i)
> ```
>
> ```python
> i = 2
> print(i)
> i -= 10
> print(i)
> ```

## Définition et syntaxe de la boucle While

En anglais, « while » signifie « tant que ». Cette boucle permet donc de répéter une suite d'instructions **tant que** une condition n'est pas vérifiée. Si la condition est vérifiée, la boucle s'arrête et le code se poursuit.

La boucle `While` suit le schéma suivant :

![[while.png]]

> [!exercice] Exercice 2
> Que fait le code suivant :
> ```python
> i = 14
>
> while i < 20:
>   print(i)
>   i+=1.5
>
> print("On est sorti de la boucle",i)
> ```

> [!exercice] Exercice 3
> Que fait le code suivant :
> ```python
> i = 23
>
> while i < 22:
>   print(i)
>   i+=2
>
> print("On est sorti de la boucle",i)
> ```

> [!exercice] Exercice 4
> Que fait le code suivant :
> ```python
> i = 23
>
> while i > 10:
>   print(i)
>   i+=3
>
> print("On est sorti de la boucle",i)
> ```

**Bilan :**

## Boucle While avec compteurs

> [!exercice] Exercice 5
> Voici une boucle While
> ```python
> a = 10
> i = 0
>
> while a < 180:
>   print(a)
>   a += 12
>   i += 1
>
> print(i)
> ```
> 1. Quelle est la valeur de $i$ affichée par la dernière ligne ?
> 2. À quoi correspond cette valeur ?

> [!exercice] Exercice 6
> Voici une autre variante
>
> ```python
> a = 10
> i = 1
>
> while 1 < 6:
>   print(a)
>   a += 12
>   i += 1
>
> print(a)
> ```
> 1. Quelle est la valeur de $a$ affichée par la dernière ligne ?
> 2. Expliquer en quelques mots ce que fait ce programme
