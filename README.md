# Prévision de la consommation d'électricité à Mayotte

Projet personnel sous R : analyse et prévision de la consommation d'électricité à Mayotte, avec des scénarios de croissance à l'horizon 2030.

## Données
Données publiques de l'IEDOM (source EDM), 16 trimestres de 2020T3 à 2024T2. Ce ne sont pas des données internes à EDM.

## Méthode
- Décomposition de la série (tendance, saisonnalité)
- Comparaison d'une tendance linéaire et d'un lissage de Holt sur un échantillon de test
- Prévision à 12 trimestres et scénarios de croissance (3 %, 5 %, 8 % par an)

## Fichiers
- `Rapport_EDM.Rmd` : rapport complet (R Markdown)
- `Rapport_EDM.html` : rapport généré
- `EDM.R` : script d'analyse
- `conso_electricite_mayotte_trimestriel.csv` : données

## Limites
Série courte (16 points), arrêtée en 2024T2, donc avant le cyclone Chido. Unité publiée à confirmer.

Outils : R (tidyverse, forecast)
