# Frittage par micro-ondes : démonstrations interactives

Trois pages web construites à partir d’un modèle simplifié du chauffage d’une pastille céramique par micro-ondes.

## Contenu

- `index.html` : page d’accueil.
- `simulateur_frittage.html` : simulateur et défi (puissance et épaisseur d’isolant : temps de chauffe, écart cœur–bord, contrainte indicative).
- `carte_animee.html` : carte de température animée de la pastille en coupe.
- `labo_ml.html` : petit réseau de neurones entraîné sur les simulations, validé sur des cas jamais vus.

## Le modèle

Équation de la chaleur 2D axisymétrique : pastille d’alumine de 20 mm de diamètre et 10 mm de hauteur dans un isolant de 20 mm, avec une source de chaleur uniforme et des pertes par convection et rayonnement.

## Limites

Modèle simplifié, non validé par des mesures : source uniforme (le champ électromagnétique n’est pas calculé), pas de retrait de frittage, propriétés des matériaux typiques. Il montre des tendances, pas des valeurs exactes.

## Sources

- Kiley E.M., *Reduced-Dimensional Coupled Electromagnetic, Thermal, and Mechanical Models of Microwave Sintering*, thèse de doctorat, Worcester Polytechnic Institute, 2016 : équations de base.

## Auteurs

Projet universitaire réalisé à deux. Le code et les pages ont été développés avec l’aide de Claude (Anthropic).
