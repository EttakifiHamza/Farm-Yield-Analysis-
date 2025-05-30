# Jeu de données
Ce jeu de données fournit des informations sur divers aspects de l'agriculture 🌱, en mettant spécifiquement l'accent sur les détails au niveau des exploitations agricoles, les types de cultures, les méthodes d'irrigation, les propriétés du sol et les mesures associées telles que le rendement, l'utilisation de l'eau, l'utilisation d'engrais et l'utilisation de pesticides. L'objectif est d'analyser et de prédire les rendements des cultures et d'identifier les facteurs influençant la productivité.

🔑 Caractéristiques clés :

🏷️ Farm_ID : Identifiant unique pour chaque exploitation.

🌽 Crop_Type : Type de culture cultivée (par exemple, Coton, Carotte, Blé).

🚿 Irrigation_Type : Méthode d'irrigation utilisée (par exemple, Goutte-à-goutte, Manuelle, Inondation).

🌍 Soil_Type : Type de sol présent sur l'exploitation (par exemple, Argileux, Sableux, Silteux).

🗓️ Season : Saison pendant laquelle la culture est cultivée (par exemple, Kharif, Rabi, Zaid).

🏞️ Farm_Area (acres) : Superficie totale de l'exploitation en acres.

🧪 Fertilizer_Used (tonnes) : Quantité d'engrais appliquée.

🐞 Pesticide_Used (kg) : Quantité de pesticide utilisée.

💧 Water_Usage (mètres cubes) : Consommation totale d'eau pour la culture.

📈 Yield (tonnes) : Rendement total de la culture en tonnes.

🎯 Objectif :
L'objectif principal est d'analyser les relations entre ces variables, d'identifier les facteurs influençant les rendements des cultures et de construire des modèles prédictifs pour estimer les rendements en fonction des caractéristiques d'entrée.

📊 Caractéristiques des données :

📝 Type de données : Le jeu de données contient des caractéristiques numériques et catégorielles.

🎯 Variable cible : Rendement (tonnes)

🔢 Caractéristiques codées : Les variables catégorielles telles que le type de culture, le type d'irrigation et le type de sol sont codées pour les besoins du modèle.

🤖 Approche de modélisation :

Modèles de régression utilisés :

🧮 Régression linéaire

🌲 Régression par forêt aléatoire

⚡ Régression XGBoost

💡 Régression LGBM

🐈 Régression CatBoost
