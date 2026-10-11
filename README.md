# Analyse des remises et du profit (Power BI)

Tableau de bord interactif qui cherche à savoir si les remises accordées font perdre de l'argent, réalisé avec Power BI Desktop.







## Données
Jeu de données « Superstore orders » (Kaggle), couvrant les années 2011 à 2014 sur 7 marchés : Africa, APAC, Canada, EMEA, EU, LATAM et US.

## Nettoyage (Power Query)
- Colonnes discount, profit et shipping_cost lues comme du texte : converties en nombres avec les paramètres régionaux anglais (point décimal)
- Vérification des types de données pour les dates et les quantités

## Indicateurs
- Profit total : 1,47 M
- Remise moyenne : 14,29 %
- Marge : 18,74 % (mesure DAX : profit / ventes)

## Visuels
- Profit par sous-catégorie (barres)
- Remise moyenne et profit par sous-catégorie (nuage de points)
- Filtres interactifs : marché et année

## Conclusion
- Tables est la seule sous-catégorie déficitaire (profit : -64 083) et c'est celle qui a la remise moyenne la plus élevée (29,07 %).
- Copiers est la plus rentable (profit : 258 568) avec une remise moyenne de 11,71 %.
- Les autres sous-catégories restent entre 10 % et 20 % de remise moyenne et sont rentables.
- Limite : un seul point déficitaire ne prouve pas que les remises causent la perte. Les coûts et les volumes peuvent aussi jouer.
- Piste : analyser le prix de vente et les frais de livraison de Tables.

## Outils
Power BI Desktop, Power Query, DAX

## Auteur
Aboubakar Koné, étudiant en Licence 3 Réseaux et Sécurité Informatique (UVCI, Abidjan)<img width="638" height="317" alt="Capture d’écran 2026-10-11 013531" src="https://github.com/user-attachments/assets/3950171d-5edf-4160-adaa-59b1528088fd" />
