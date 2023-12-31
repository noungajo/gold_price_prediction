# gold_price_prediction
Le projet "Gold Price Prediction" est un projet qui implémente les réseaux de neurones artificiels avec TensorFlow pour prédire le prix de l'or
## Dataset

Ce fichier de données est au format CSV (Comma Separated Values) avec 2290 lignes et 7 colonnes. 
Il contient 5 colonnes de type numérique et une colonne au format date. Les données montrent clairement les valeurs des variables SPX, GLD, USO, SLV, EUR/USD en fonction des dates figurant dans la colonne de dates.
Les variables SPX, GLD, USO, SLV, EUR/USD sont généralement utilisées pour suivre et analyser des aspects différents du marché financier et de l'économie.

1. **SPX** : Il s'agit du symbole du S&P 500, un indice boursier américain largement utilisé qui représente la performance des 500 plus grandes entreprises cotées en bourse aux États-Unis. Le S&P 500 est un indicateur clé de la santé du marché boursier américain et de l'économie en général.

2. **GLD** : Il s'agit du symbole de SPDR Gold Trust, un ETF (Exchange-Traded Fund) qui vise à suivre le prix de l'or. GLD est utilisé pour investir dans l'or, ce qui en fait une variable importante pour suivre le prix de l'or et les tendances dans le secteur de l'or.

3. **USO** : Il s'agit du symbole de l'United States Oil Fund, un ETF qui vise à suivre le prix du pétrole brut. USO est utilisé pour investir dans le pétrole brut et est donc un indicateur clé des tendances du marché pétrolier.

4. **SLV** : Il s'agit du symbole du iShares Silver Trust, un ETF qui suit le prix de l'argent. SLV est utilisé pour investir dans l'argent et est donc un indicateur important pour suivre le prix de l'argent.

5. **EUR/USD** : Il s'agit du taux de change entre l'euro (EUR) et le dollar américain (USD). Cet indicateur montre la valeur relative de l'euro par rapport au dollar américain sur le marché des changes. Il est souvent utilisé pour évaluer les tendances des devises.



## Prérequis

Avant de commencer, assurez-vous d'avoir installé les bibliothèques Python nécessaires en utilisant la commande suivante :

```bash
pip install pandas scikit-learn jupyter
```

## Structure du Projet

Le projet est organisé de la manière suivante :

```
diabetes_detection_project/
    ├── gold_price_prediction.ipynb
    ├── gld_price_prediction.csv
    └── README.md
```

- `gold_price_prediction.ipynb` : Le notebook Jupyter principal contenant le code pour la préparation des données, l'entraînement du modèle lineaire, et l'évaluation de la performance du modèle.
- `gld_price_prediction.csv` : Le jeu de données au format CSV.
- `README.md` (ce fichier) : La documentation du projet.

## Utilisation

1. Clonez ce dépôt sur votre ordinateur :

   ```bash
   git clone https://github.com/noungajo/gold_price_prediction.git
   cd gold_price_prediction
   ```

2. Exécutez le notebook Jupyter `gold_price_prediction.ipynb` pour travailler sur le projet. Vous pouvez utiliser Jupyter Notebook ou JupyterLab pour cela.

3. Suivez les étapes dans le notebook pour charger les données, préparer les caractéristiques, entraîner le modèle lineaire, et évaluer ses performances.

4. Une fois le modèle formé, vous pouvez l'utiliser pour prédire le prix de l'or en fonction des caracteristiques fournies.

## Contribution

Les contributions à ce projet sont les bienvenues. Si vous souhaitez contribuer, veuillez ouvrir une "issue" pour discuter de votre proposition ou soumettre une "pull request" pour ajouter des fonctionnalités ou résoudre des problèmes.

## Licence

Ce projet est sous licence MIT. Vous êtes libre de l'utiliser et de le modifier comme bon vous semble.

---

