# Parcours S03
- Ton repo : [https://github.com/O-clock-Atlantis/S03-parcours-Olivier-Go](https://github.com/O-clock-Atlantis/S03-parcours-Olivier-Go)
- Correcteur : jc

# Feedback du prof

## Test 1

### Enoncé

- Demander à l'utilisateur de rentrer un premier nombre dans une boite de dialogue
- Demander à l'utilisateur de rentrer un 2e nombre dans une boite de dialogue
- Additionner les deux nombres
- Afficher le résultat dans #result

### Attendus

- [x] Syntaxe JS
- [x] Récupération des valeurs via `prompt`
- [x] Conversion des valeurs en nombre
- [x] Calcul de la somme
- [x] Ciblage d'un élement du DOM
- [x] Modification du contenu de l'élément

### Commentaires

- Nickel :thumbsup:
- Bien la fioriture CSS avec `style` ;)

## Test 2

### Enoncé

- L'utilisateur tape un nombre dans chaque input, puis clique sur OK
- A la soumission du formulaire, on additionne les deux nombres
- On affiche le résultat dans #result

### Attendus

- [x] Syntaxe JS
- [x] Écoute de l'évènement `submit`
- [x] Bloquer le comportement par défaut avec `preventDefault`
- [x] Ciblage d'un élement du DOM
- [x] Utilisation de la propiété `value`
- [x] Conversion des valeurs en nombre
- [x] Calcul de la somme
- [x] Modification du contenu de l'élément

### Commentaires

- C'est top de l'avoir fait sous forme de module
- Nickel :thumbsup:

## Test 3

### Enoncé

- L'utilisateur tape un nombre dans chaque input
- Chaque fois que l'on tape au clavier dans l'un des deux input et si les deux inputs sont remplis, on additionne les deux nombres et on affiche le résultat dans #result

### Attendus

- [x] Syntaxe JS
- [ ] Écoute de l'évènement `keyup` ou `input`
- [x] Ciblage d'un élement du DOM
- [x] Utilisation de la propiété `value`
- [x] Conversion des valeurs en nombre
- [x] Calcul de la somme
- [x] Modification du contenu de l'élément

### Commentaires

- C'est pas mal d'avoir utilisé un évènement du clavier, on préfère `keyup` qui correspond précisement à l'instant suivant l'appuie d'une touche, ainsi on a bien la dernière valeur à jour
- C'est top de l'avoir fait sous forme de module
- Sinon nickel :thumbsup:
- Très bien le contrôle de l'affichage que si on a un nombre.

## Test 4

### Enoncé

- Dans #container, affiche l'heure à la seconde près.
Sous le format : 11h 12m 06s
- Chaque seconde, l'heure doit être actualisée

### Attendus

- [x] Syntaxe JS
- [x] Utilisation de `setInterval` pour répéter une action périodiquement
- [x] Récupération de la date avec `new Date()`
- [x] Utilisation des méthodes de l'objet Date pour récupérer les heures, minutes et secondes
- [ ] Ajout des 0 devant les chiffres
- [x] Concaténation pour former l'heure complète
- [x] Modification du contenu de l'élément

### Commentaires

- Tu as bien généré la date, dans l'exemple donné les nombres inférieurs à 10 ont un 0 devant. Pour se faire on pouvait concaténer un 0 et s'assurer de la longueur de la chaîne.
- C'est top de l'avoir fait sous forme de module
- Sinon nickel :thumbsup:
- Tu peux nommer la fonction de rappel comme pour les événements : `setInterval(clockApp.getTime, 1000);` au lieu de `setInterval("clockApp.getTime()", 1000);`

## Test 5

### Enoncé

- int est un entier
- Le doubler, et le retourner

### Attendus

- [x] Syntaxe JS
- [x] Multiplication de la valeur du paramètre par 2
- [x] Retour d'une valeur

### Commentaires

- Nickel :thumbsup:

## Test 6

### Enoncé

- int est un entier
- Retourner `true` si c'est pair, `false` si c'est impair

### Attendus

- [x] Syntaxe JS
- [x] Test pour déterminer si le paramètre est paire ou non
- [x] Retour d'une valeur

### Commentaires

- Nickel :thumbsup:

## Test 7

### Enoncé

- str est une string
- Retourner l'extension de fichier.

### Attendus

- [x] Utilisation de méthodes et de propriété des chaînes de caractères et/ou des tableaux pour manipuler et tester le paramètre d'entrée
- [x] Test pour retourner `false` en cas d'erreur
- [x] Extraction de l'extension
- [x] Retour d'une valeur

### Commentaires

- Nickel :thumbsup:

## Test 8

### Enoncé

- arr est un array
- Retourner la chaîne la plus longue de l'array

### Attendus

- [x] Syntaxe JS
- [x] Utilisation d'une boucle pour répéter des instructions
- [ ] Test pour déterminer le type de la variable grâce à `typeof`
- [ ] Test de la longueur de la chaîne
- [x] Test pour retourner `false` en cas d'erreur
- [x] Retour d'une valeur

### Commentaires

- Nickel :thumbsup:
- Bien joué pour l'usage `reduce`, on en attendait pas tant :)

## Test 9

### Enoncé

- arr est un array
- Retourner la somme des nombres contenus dans cet array

### Attendus

- [x] Syntaxe JS
- [ ] Utilisation d'une boucle pour répéter des instructions
- [ ] Test pour déterminer le type de la variable grâce à `typeof`
- [ ] Incrémentation d'une variable
- [x] Prise en compte des sous-tableaux
- [x] Retour d'une valeur

### Commentaires

- Nickel :thumbsup:
- Récursivité, reduce + filter = :muscle: :boom:
- Niveau socle, on attendait une fonction récursive, des if et l'usage de `typeof` :)

## Test 10

### Enoncé

- Dans la session, à la clé dirty_strings, récupérer chaque chaîne de caractères
- Les emails valides doivent être stockés dans un tableau en session à la clé clean_emails
- Les urls valides doivent être stockées dans un tableau en session à la clé clean_urls

### Attendus

- [x] Syntaxe PHP
- [x] Session rendue disponible grâce à `session_start()`
- [x] Déclaration de tableaux pour stocker nos valeurs
- [x] Utilisation du tableau associatif `$_SESSION` pour accéder aux valeurs stockées dans la session
- [ ] Parcours du tableau grâce à une boucle
- [x] Utilisation de la fonction PHP `filter_var`
- [x] Ajout d'éléments à la fin d'un tableau
- [x] Ajout d'élements à une clé précise du tableau associatif `$_SESSION`

### Commentaires

- Nickel :thumbsup:
- Pas de boucles ni de push, mais `array_filter`, impec' :)

## Général

- [x] Présence de commentaires dans le code
- [x] Indentation et lisibilité du code
- [x] Noms de variables précis
- [x] Variables et fonctions en "camelCase"

### Pistes de révisions


### Commentaires

- Excellent parcours, bravo :clap:
Aurais-tu quelques connaissances préalables en programmation :smirk: ?
En tout cas, parcours au top, bien joué. N'hésite pas à essayer de les faire en utilisant que ce qui est connu dans le socle, éventuellement, la prochaine fois (ou pas ^^ mais ça permet de revenir aux origines !).