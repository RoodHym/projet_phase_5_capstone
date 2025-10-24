# projet_phase_5_capstone
# Apercu du projet
Ce projet vise à analyser la production mondiale de plastique, son traitement (recyclage, incinération, enfouissement, mauvaise gestion) et à modéliser la relation entre ces variables à l’aide d’algorithmes de machine learning (Random Forest, Gradient Boosting, Régression Linéaire).Nous allons prédire la part de plastique mal gérée et de comprendre les dynamiques globales de la pollution plastique. 
Et Proposer à la fin des recommandations politiques basées sur les données.

# Jeux de données
Nous avons utiliser trois jeux de donnees: 
1. global-plastics-production.csv : production annuelle mondiale de plastique (1950–2019)
2. share-plastic-fate.csv : répartition du traitement des déchets plastiques (recyclé, incinéré, enfoui, mal géré)
3. mismanaged-plastic-waste-per-capita.csv : déchets plastiques mal gérés par habitant (kg/an)
   La source de ces jeux de données est les site de kaggle.

# Analyse exploratoire des données
Nous allons analyser l’évolution de la production mondiale de plastique, évaluer l'efficacité de gestion des déchets par région, identifier les zones critiques de mauvaise gestion des déchets.

## Graphique : Courbe d'Évolution Temporelle de la Production Mondiale de plastiques

Caractéristiques :

•	Axe Y : Millions de tonnes (échelle 0-500)
•	Axe X : Période 1950-2019
•	Courbe exponentielle marquée
<img width="944" height="514" alt="image" src="https://github.com/user-attachments/assets/0e3f88be-d5e7-4054-b6db-5ca3e341c30c" />

## Histogramme : Répartition par Pays des déchets mal gérés/habitant/an
Structure du Graphique :

•	Axe X : kg de déchets mal gérés/habitant/an
•	Axe Y : Nombre de pays dans chaque intervalle
<img width="1041" height="571" alt="image" src="https://github.com/user-attachments/assets/cb5943e9-e7f7-4992-932d-ac5ed04dab39" />



# Modelisation predictive
Nous allons testes trois modèles de machine learning:
- Régression Linéaire
- Random Forest Regressor
- Gradient Boosting Regressor

# Recommandations Strategiques
Actions Prioritaires :
Cartographier les points chauds de pollution plastique:
	Utiliser les résultats du modèle pour identifier les pays/régions ayant les plus fortes valeurs de «Déchets 	Mal Gérés par habitant».	L’objectif est de concentrer les efforts de collecte et de 	sensibilisation.
   
Lancer des programmes de tri à la source dans les zones urbaines:
	 Former les ménages et les entreprises à trier le 	plastique selon sa nature. 
	 Le modèle montre que la part de déchets recyclés est 	un facteur déterminant de la réduction du plastique mal géré.
    
Investir dans la recherche et l’innovation:
	Financer des projets d’IA et de data science pour la 	prédiction de la pollution plastique et l’optimisation 	du tri automatique (computer vision, capteurs).
	Utiliser des modèles prédictifs plus performants (Random Forest, Gradient Boosting) pour anticiper les pics de déchets mal gérés.





