# Test technique INRIA

- Toute la partie nettoyage des données se trouve dans 1_cleaning
- La partie recherche et implémentation de la déduplication est faite dans 2_duplicates
- Enfin, 3_eda comprend la visualisation des résultats et les conclusions tirées

Les autres fichiers contiennent des données:

- db_clean.csv et clean_pcr.csv contiennent les données patient et pcr après cleaning
- australia_covid_no_dup.csv contient df_patient après déduplication par la méthode LSH
- deduped.pkl contient le pickle.dump des résultats de process.dedupe sur la totalité des données (2h46 de traitement)


**Installation des librairies nécessaires**

``pip3 install -r requirements.txt``
