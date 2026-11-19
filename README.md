# Projet CI12 — Prévision des exportations agroalimentaires marocaines

- **Étudiante :** Basma Fadili
- **Sujet :** CI12 — Prévision de la valeur annuelle des exportations agroalimentaires du Maroc (Tomates fraîches et Agrumes, 2000–2024)
- **Source des données :** FAOSTAT (Cultures et produits animaux — Commerce)
- **Modèle principal :** Régression linéaire régularisée Ridge ($L_2$) avec validation croisée temporelle (`TimeSeriesSplit`) et découpage chronologique strict sans fuite (Train : 2001–2019 | Test : 2020–2024)

## Structure du dépôt
- `Basma FADILI 26005993 Exam CC partie B.ipynb` : Notebook complet exécuté de bout en bout (10 sections)
- `rapport/rapport.pdf` : Export PDF du compte rendu complet
- `requirements.txt` : Dépendances Python nécessaires à la reproduction
