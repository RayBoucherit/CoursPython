# Programmation

La programmation consiste à résoudre des problèmes de différents domaines (mathématique, biologie, finance, santé etc.) Cela implique de savoir **programmer** des ordinateurs.  
Ce qui veut dire leur donner une suite d'instructions à exécuter pour résoudre le problème rencontré.
Cette suite d'instructions s'appelle un **algorithme**.

## Algorithme

>Ensemble de règles opératoires dont l'application permet de résoudre un problème énoncé au moyen d'un nombre fini d'opérations.  
>Un algorithme peut être traduit, grâce à un langage de programmation, en un programme exécutable par un ordinateur.  
(Définition du Larousse)  

Un algorithme peut donc être traduit en un programme informatique. Voyons les spécifités des programmes Python.

## Le programme "Hello World"
  
Traditionnellement, le premier **programme** que l'on écrit quand on apprend un nouveau langage est appelé le programme **"Hello World"** (Bonjour Monde en français).  
Il se contente d'afficher le texte `Hello, World!` à l'écran.  
En Python cela donne:  
```python
    //ce code affiche: Hello, world!
    print("Hello, world!")
```

**Exercice**: Exécuter le code précédent, essayer de faire afficher votre nom au programme.

**Question**: Supprimer les caractères `//` de l'exemple de code. Que se passe-t-il? Chercher ce qu'est un commentaire.

# Variables en Python

## Introduction

Dans un langage de programmation on peut définir des **variables**.  
Une **variable** est un emplacement mémoire avec un nom qui stocke une **valeur**.  
Une **valeur** peut être un nombre, du texte, un booléen (?), une image, du son etc.  
C'est son **type** qui détermine ce qu'elle contient.

## Déclarer des variables/assigner une valeur

Pour **déclarer** une **variable** et lui **assigner** une valeur, la syntaxe est la suivante:
```python
    var1 = "valeur 1"
    var2 = 2
    var3 = False
``` 
Le nom de la variable doit être écrit avant le symbole `=` et sa valeur après.

**Exercice**: Déclarer une variable dans l'interpreteur que contient le nom de votre couleur préférée.
Afficher ce qu'elle contient avec `print(var)` où var est le nom de la variable déclarer

### Nommer des variables

Le fait de nommer une variable en Python doit respecter certaines rêgles.
Tout d'abord les seuls caractère autorisés sont [a-z], [A-Z], `_` et [0-9].
Il ne faut pas que le nom de la variable commence par un chiffre.
Il ne faut pas non plus utiliser des **mots réservés** du langage.
Intuitivement, les **mots réservés** sont les mots qui ont un sens pour python.
Ces mots peuvent être `print, input, if, while` etc.
Nous verrons d'autres **mots réservés** et leure signification plus tard dans le cours

### Le symbole d'assignation

Le symbole utilisé pour assigner une valeur à une variable en python est `=`.
Il n'a pas la même signification qu'en mathématique.
L'assignation ne vérifie pas l'égalité entre une variable et une valeur mais il donne à la variable la valeur indiqué.
On peut le schématiser par `var <- val`
**Exemple**:
```python
    x = 10
    y = 7
    x = y
```
**Question**: Quelle est la valeur de x à la fin de l'exécution de ce programme ?

### Les différents types de valeur