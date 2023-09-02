# README

Ce repository contient le code d'un projet lié à la détection de fraude dans les transactions par carte de crédit. L'objectif de ce projet est de développer un modèle d'apprentissage  capable d'identifier avec précision les transactions frauduleuses et de les distinguer des transactions légitimes.

## Base de données

Le projet utilise un ensemble de données qui comprend des informations sur les transactions par carte de crédit, telles que la durée de la transaction, le montant de la transaction et diverses fonctionnalités anonymisées. L'ensemble de données est fourni au format CSV et se compose d'un ensemble d'entrainement et d'un ensemble de test.

## L'analyse des données

La première étape du projet consiste à effectuer une analyse de l’ensemble de données. Cela inclut l'exploration des données, la visualisation des distributions et l'identification de toutes les corrélations entre les caractéristiques. L'analyse est effectuée à l'aide de diverses bibliothèques Python, notamment pandas, numpy, seaborn et matplotlib.

## Prétraitement des données

Avant de former les modèles d'apprentissage, certaines étapes de prétraitement sont appliquées à l'ensemble de données. Ces étapes impliquent la mise à l'échelle des fonctionnalités de temps et de quantité à l'aide d'un RobustScaler pour garantir que toutes les fonctionnalités sont à une échelle similaire. De plus, l'ensemble de données est divisé en ensembles d'entrainement et de test à l'aide de la fonction train_test_split de sklearn.model_selection.

## Formation et évaluation des modèles

Plusieurs modèles d'apprentissage sont entraînés et évalués sur l'ensemble de données prétraité. Les modèles incluent la régression logistique, les K-voisins les plus proches, le classificateur de vecteurs de support et le classificateur d'arbre de décision. Une validation croisée est effectuée pour évaluer les performances de chaque modèle.

Le modèle de régression logistique s'avère le plus efficace, avec un score de précision de 70 %. Ce modèle est sélectionné comme modèle final pour prédire la fraude dans les transactions par carte de crédit.

## Prédictions

Le modèle final formé est utilisé pour prédire la fraude dans l'ensemble de données de test. Les prédictions sont faites à l'aide de la méthode de prévision du modèle de régression logistique. Les résultats prédits sont ensuite enregistrés dans un fichier de soumission au format CSV.

## Conclusion

Ce projet démontre l'utilité d'algorithmes d'apprentissage  pour la détection des fraudes dans les transactions par carte de crédit. En analysant et en prétraitant les données, en entraînant et en évaluant différents modèles et en effectuant des prédictions sur l'ensemble de données de test, nous pouvons créer un système de détection des fraudes efficace.

Veuillez vous référer au code fourni dans ce repository pour plus de détails sur l'implémentation.

Si vous avez des questions ou avez besoin d'aide supplémentaire, n'hésitez pas à me contacter.
