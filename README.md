# Pokemon_design-patterns

 ## Exercice 1

1) Quel sont les problèmes engendrés par l’implémentation du code de chaque attaque dans la classe ?
Si plusieurs classes ont la même attaque, nous allons avoir une duplication inutile du même code/méthode dans chaque classe.

2) Quel sont les problèmes engendrés par cette solution ?
Il faut faire une classe pour chaque association possible, ce qui est long, lourd, difficilement maintenable, …

3) L’agrégation entre les classes Pokémon et Énergie a-t-elle une incidence ?
Oui, car si un pokémon est K.O., l'énergie n’est pas détruite, elle est conservé.


## Exercice 2

