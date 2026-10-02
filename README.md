# TP2:

Salut, je suis Marouane Chafiqi, étudiant en master TEE.

Ce projet est mon deuxième TP de NLP (Natural Language Processing). J'y ai appris comment transformer du texte en chiffres pour qu'une machine puisse le traiter.

## Ce que j'ai fait

1. **Bag of Words** : j'ai transformé 3 phrases en matrice avec `CountVectorizer`, où chaque colonne est un mot et chaque valeur son nombre d'apparitions
2. **TF-IDF** : j'ai refait la même chose avec `TfidfVectorizer` pour donner plus de poids aux mots importants et moins aux mots très courants
3. **Comparaison** : j'ai observé les différences de poids entre les deux méthodes (par exemple, un mot présent dans toutes les phrases comme "le" pèse peu, alors que "football" ou "cinema" pèsent plus)

## Outils utilisés

Python, Jupyter Notebook, scikit-learn, pandas

## Fichier principal

`TP2_NLP.ipynb` : le notebook avec le code, les résultats et mes réponses aux questions.

## Pour le lancer

```
pip install scikit-learn pandas
jupyter notebook
```
