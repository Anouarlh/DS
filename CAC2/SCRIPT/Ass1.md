<img src="image 1 (1).jpg" style="height:450px;margin-right:450px"/>
Anouar LAHLOU
🎯 Objectif de l’étude

L’étude vise à prédire la performance scolaire des élèves du secondaire portugais (notamment en Mathématiques et Langue Portugaise) à l’aide de techniques de data mining (fouille de données).
Elle cherche aussi à identifier les facteurs les plus influents sur la réussite ou l’échec scolaire.

🧠 Contexte

Malgré une amélioration du niveau d’éducation au Portugal, les taux d’échec et d’abandon scolaire restent très élevés.

Les matières de base (Maths et Portugais) sont déterminantes pour la réussite générale.

Les méthodes de Business Intelligence (BI) et Data Mining (DM) offrent des outils puissants pour analyser les données éducatives et améliorer la prise de décision.

🧩 Méthodologie

Données collectées :

Issues de rapports scolaires et de questionnaires remplis par 788 élèves (deux écoles portugaises, 2005-2006).

Après nettoyage, deux bases :

395 élèves (Maths)

649 élèves (Portugais)

Variables : âge, sexe, profession et niveau d’éducation des parents, temps d’étude, absences, consommation d’alcool, etc.

Tâches de modélisation :

Classification binaire : réussite/échec (note ≥ 10).

Classification à 5 niveaux : d’“excellent” à “insuffisant”.

Régression : prédiction de la note finale (0 à 20).

Techniques utilisées :

Decision Trees (DT)

Random Forests (RF)

Neural Networks (NN)

Support Vector Machines (SVM)

Comparaison avec un modèle naïf basé sur les notes précédentes.

📊 Résultats principaux

Les meilleures prédictions sont obtenues lorsque les notes des 1er et 2e trimestres sont incluses.

Les Random Forests donnent les meilleures performances globales, suivies des arbres de décision.

Les NN et SVM sont moins performants, car plus sensibles aux variables inutiles.

Facteurs clés identifiés :

Notes précédentes (G1, G2)

Nombre d’absences

Nombre d’échecs antérieurs

Soutien scolaire (familial ou extra)

Travail et éducation de la mère

Consommation d’alcool

Fréquence des sorties avec les amis

🧾 Conclusions

Les performances scolaires peuvent être prédites avec une bonne précision grâce aux données disponibles.

Les résultats passés sont le meilleur indicateur de la réussite future.

D’autres variables sociales, familiales et comportementales ont également un impact non négligeable.

L’étude ouvre la voie à des systèmes prédictifs intégrés dans la gestion scolaire pour :

Détecter précocement les élèves à risque.

Améliorer l’orientation et le soutien pédagogique.

Optimiser la gestion des ressources éducatives.

💡 Perspectives futures

Étendre l’étude à plus d’écoles et d’années scolaires.

Intégrer un apprentissage en ligne et en temps réel (on-line learning).

Appliquer des techniques de sélection automatique de variables.

Approfondir la compréhension sociologique des facteurs d’échec.
