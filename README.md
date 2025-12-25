# Mini-projet Data Mining - Prédiction Prix Immobiliers Paris

**Étudiants** : Nader NOUIRA & Nesrine BEN YAHIA  
**Classe** : 3 DNI - 2025

## Description du projet
Application web interactive qui prédit le prix d'un bien immobilier à Paris en intégrant :
- Sentiments simulés sur les quartiers
- Clustering K-Means pour grouper les quartiers par vibe
- Régression Random Forest pour prédire le prix
- Indice d'attractivité personnalisé (combinaison sentiment + prix moyen)

## Installation
1. Clone le dépôt  
   `git clone https://github.com/Nessrinebenyahia1/mini-projet-immo-sentiments-2025`
2. Installe les dépendances  
   `pip install -r requirements.txt`
3. Lance l'application  
   `python -m streamlit run src/app.py`

## Démonstration (captures d'écran)
<img width="1366" height="768" alt="Capture d’écran (137)" src="https://github.com/user-attachments/assets/b264929e-6ad6-4669-b61f-04c375376536" />
<img width="1366" height="768" alt="Capture d’écran (138)" src="https://github.com/user-attachments/assets/57b80c3f-ab29-49b1-b6a1-bdc1f9f2154a" />
<img width="1366" height="768" alt="Capture d’écran (140)" src="https://github.com/user-attachments/assets/17112e13-4ac4-42f2-ad7a-8a5ed6354ef9" />
<img width="1361" height="557" alt="image" src="https://github.com/user-attachments/assets/30b8e942-bc1b-4081-841c-edfbd68dee54" />
<img width="863" height="484" alt="image" src="https://github.com/user-attachments/assets/b3b86184-6c37-4358-82f0-6d5d871746e7" />



## Algorithmes Data Mining utilisés
- Clustering non supervisé : **K-Means**
- Régression supervisée : **Random Forest Regressor**
- Feature engineering : indice d'attractivité original

Projet 100% original – Réalisé avec Python, scikit-learn et Streamlit.
