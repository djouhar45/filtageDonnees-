# 📊 Analyse des Prêts Bancaires

Ce projet présente une série d'analyses réalisées à partir d’un jeu de données contenant des informations sur les prêts bancaires accordés par différentes agences.

## 🔎 Objectif
Répondre aux questions formulées par le responsable du service prêt, afin de mieux comprendre les profils à risque et les performances des agences.

---

## 📁 Fichier utilisé
- `prets.csv` (ou un fichier pandas chargé au préalable)

---

## ✅ Analyses réalisées

1. **Nombre de personnes ayant dépassé le taux d’endettement autorisé (35%)**
   - Filtrage des clients avec un taux d’endettement strictement supérieur à 35%
   - Calcul du nombre total

2. **Nombre de personnes à risque dans l’agence Parisienne**
   - Même traitement, filtré uniquement sur l’agence située à Paris

3. **Ajout d’une colonne `risque`**
   - Une nouvelle variable (`risque`) a été ajoutée au DataFrame :
     - `"Oui"` si le client dépasse le seuil d’endettement
     - `"Non"` sinon

4. **Analyse des prêts automobiles**
   - Nombre total de prêts automobiles accordés
   - Coût total moyen de ces prêts

5. **Bénéfice mensuel total de l’agence Toulousaine**
   - Filtrage sur l’agence de Toulouse
   - Somme des bénéfices mensuels associés à ses prêts

---

## 🧠 Technologies utilisées

- Python
- pandas
- NumPy
- Jupyter Notebook (optionnel)
- GitHub

