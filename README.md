# Description du Projet

Le projet réalisé durant mon stage technique chez BEEVORA avait pour objectif de prédire les cotations proposées par un bookmaker pour différents événements sportifs. L'idée principale était de déterminer si les cotations proposées étaient sous-évaluées ou sur-évaluées par rapport aux "vraies" cotations basées sur des données historiques et des facteurs externes influençant le résultat d'un événement.

# Etapes du projet

1. **Prétraitement des données**  
   - Extraction des scores finaux à partir des chaînes de caractères.
   - Calcul de la variable cible `cote_passe` (True/False) indiquant si la cote était gagnante.
   - Ajout de caractéristiques temporelles (mois, jour de la semaine, jour du mois, heure).

2. **Modèles testés**  
   - Régression logistique.
   - Arbre de décision.
   - Forêt aléatoire.
   - Réseaux de neurones
   - regression linéaire
    
3. **Évaluation des performances**  
   - Métriques : Précision, rappel, et validation croisée.
     
# Conclusion

Ce projet de prédiction des cotations a permis de démontrer l’intérêt de l’analyse de données dans l’univers des paris sportifs. Cependant, il reste encore beaucoup de travail à faire pour améliorer la précision des modèles et les rendre exploitables dans un contexte de production. Néanmoins, il offre une base solide pour des améliorations futures et pourrait devenir une technologie intéressante pour les acteurs du marché des paris sportifs.