
``` markdown
# Intégration Monte-Carlo en Python
   RANDRIANJAFY Voahanginiaina Roberte 
Ce projet implémente une méthode
 d'intégration numérique utilisant
 la technique de Monte-Carlo
pour calculer une approximation de
l'intégrale d'une fonction donnée.

## Fonctionnalités

- Calcul d'intégrales définies par
la méthode Monte-Carlo
- Comparaison avec la valeur exacte
de l'intégrale
- Calcul de l'erreur d'approximation
- Configuration flexible des
paramètres d'intégration

## Utilisation

Le code est contenu dans le fichier
 `code.py`. Pour l'exécuter :

```bash
python code.py
```

## Paramètres configurables
a et b : bornes de l'intégrale

num_samples : nombre d'échantillons 
pour la simulation Monte-Carlo 
(défaut: 100000)

f(x) : fonction à intégrer 
(défaut: x²)
## Exemple de sortie
```
la valeur de l'integrale approché
 est : 0.333456789123
la Valeur exacte de l'integrale
 est : 0.333333333333
l'erreur à la valeur exacte est :
 0.00012345579
En augmentant num_samples 
(le nombre d'echantillons),
l'approximation de l'intégrale
devrait devenir de plus en plus
précise
```
## Personnalisation
Pour intégrer une autre fonction :

Modifiez la fonction f(x) dans 
le code

Ajustez la variable exact_value 
si vous connaissez la valeur exacte 
de la nouvelle intégrale
## Auteur
RANDRIANJAFY Voahanginiaina Roberte 
```
