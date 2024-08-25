titre : optimisez la gestion du stock d'une boutique en nettoyant ses données 
    Rapprochement des Données :
        Fichiers à fusionner :
            erp.xlsx : Export de l’ERP avec les références produit, prix de vente, et état des stocks.
            web.xlsx : Export de la boutique en ligne avec les informations sur les produits et le nombre de ventes.
            Table de liaison : liaison.xlsx, associant les références de l’ERP aux références de la boutique en ligne (SKU).
        Analyse : Effectuer le rapprochement des données et fusionner les fichiers pour obtenir un dataset consolidé.

    Analyse Financière :
        Calculer le chiffre d'affaires par produit ainsi que le total du chiffre d’affaires réalisé en ligne.

    Détection des Erreurs :
        Analyser les prix des produits pour identifier les valeurs aberrantes, les lister, et créer des graphiques pour visualiser ces anomalies.
        Utiliser Python avec Pandas pour le nettoyage des données et Plotly pour la visualisation graphique.

Livrables

    Jupyter Notebook : Documenter le processus de nettoyage et d'analyse des données.
    Fichier de Données Final : Dataset consolidé au format Excel ou équivalent.
    Présentation : Présenter les analyses exploratoires, le nettoyage des données, les analyses univariées, et les compétences acquises.
