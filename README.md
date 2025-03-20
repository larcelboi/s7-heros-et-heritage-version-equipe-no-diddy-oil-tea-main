# Objectifs
- Utiliser tous les concepts de programmation orientée-objet vus jusqu'à présent
- Retour sur lecture/écriture de fichiers
- Développer la pensée orientée-objet, la logique applicative et l'autonomie en vue de l'examen et de la réalisation d'un projet dans les prochaines semaines

# Énoncé et exigences
Vous devez développer, en équipe de préférence, une application qui permet d'entraîner les héros face au crime grandissant en faisant des simulations d'intervention de vos héros.

- Il y a trois types de super-héros : les super-héros "normaux", les super-héros qui peuvent voler et les super-héros qui peuvent changer de dimension
  - Tous les super-héros ont un nom ainsi qu'au moins un pouvoir parmi une liste prédéfinie.
  - Tous les super-héros ont une position qu'on peut représenter sur un plan cartésien où les unités sont en km.
  - Tous les super-héros peuvent utiliser leurs pouvoirs et se déplacer à 10 km/h; ils ont peu de chances de se perdre en chemin (10%)
  - Les super-héros qui peuvent voler se déplacent plus rapidement à 100 km/h et ont peu de chances de se perdre en chemin (10%)
  - Les super-héros qui peuvent changer de dimension se déplacent plus rapidement encore (300 km/h) mais peuvent facilement se perdre entre les différentes dimensions (70%)
  - Un super-héros qui se perd en chemin ne se rend pas à temps au criminel et ne parvient pas à arrêter le crime
- Les criminels ont un nom, une position, une vitesse de déplacement et un type de crime préféré parmi une liste prédéfinie. Les crimes sont stockés dans un fichier.
- Un super-héros qui arrive en moins de 5 min au criminel a 70% de chances d'arrêter le crime; sinon ses chances sont de 50%
- Chaque héros doit garder trace du nombre de crimes qu'il a arrêtés
- On doit aussi garder trace du nombre de crimes arrêtés par tous les super-héros, tous types confondus

Vous devriez utiliser dans votre solution
- les propriétés et méthodes de classe
- l'héritage
- les énumérations
- au moins une exception personnalisée
- les accesseurs et les mutateurs

Documenter avec docstring toutes les méthodes.

# Ressources
- https://www.alloprof.qc.ca/fr/eleves/bv/mathematiques/le-plan-cartesien-m1309
- https://www.alloprof.qc.ca/fr/eleves/bv/mathematiques/math-la-distance-entre-deux-points-m1311
- https://docs.python.org/3/library/math.html - il existe une méthode pour faciliter le calcul de distance
- https://docs.python.org/3/library/datetime.html

# Conseils
- Il est fortement suggéré de faire un diagramme UML avant d'écrire votre code en Python avec les bonnes pratiques POO.
- Il est suggéré de faire un peu de pseudo-code avant de faire les calculs ou toute autre méthode qui ne serait pas "facile" à implémenter
- Il est fortement suggéré d'écrire quelques tests, particulièrement pour les calculs
- La durée prévue de l'exercice est d'environ 5 heures, en équipe. Il est suggéré de faire valider votre avancement par la personne enseignante à chaque période de cours consacrée à l'exercice.

# Remise et rétroaction
- Vous devez faire essayer votre application à au moins une autre équipe de la classe
- Vous devez donner de la rétroaction à au moins une autre équipe sur la facilité d'utilisation et sur leur validation des données entrées
