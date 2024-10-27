# Agent de Résolution du Puzzle 8

Ce dépôt contient un agent intelligent conçu pour résoudre le problème classique du puzzle 8 en utilisant l'algorithme A*.
Cet agent est capable d'évaluer l'état du puzzle et de prendre des décisions basées sur la distance de Manhattan, une heuristique qui mesure la distance minimale pour atteindre l'état cible.

## Fonctionnalités

- **Résolution du puzzle 8 :** Utilisation de l'algorithme A* pour trouver la solution optimale.
- **Heuristique de Manhattan :** Évaluation des états en fonction de la distance de Manhattan pour guider la recherche.

## Installation

Pour utiliser cet agent, vous devez d'abord créer un environnement Python et installer les dépendances nécessaires.

### Étapes d'installation
 
1. **Créer un environnement virtuel :**
2. ```bash
   python -m venv en
   ```
3. **Activer l'environnement virtuel :**
   sur windows:
   ```bash
   .\env\Scripts\activate
   ```
   sur linux/macOs :
   ```bash
    source env/bin/activate
   ```
5. **Installer les bibliothèques nécessaires :**
   ```bash
   pip install -r requirements.txt
   ```

## États Initiaux

Dans la cellule des états initiaux, vous trouverez des exemples d'états initiaux du puzzle 8. Ces états sont commentés et peuvent être utilisés directement dans le code. 
Vous pouvez également fournir votre propre état initial en l'affectant à la variable `initial_puzzle`.

### Exemple d'États Initiaux

Voici quelques exemples d'états initiaux commentés que vous pouvez utiliser :

```python
# État initial 1
initial_puzzle = [
    [1, 2, 3],
    [4, 5, 0],
    [7, 8, 6]
]

# État initial 2
# initial_puzzle = [
#     [1, 0, 3],
#     [4, 2, 5],
#     [7, 8, 6]
# ]

# État initial 3
# initial_puzzle = [
#     [2, 8, 3],
#     [1, 6, 4],
#     [7, 0, 5]
# ]
```

### Points à Adapter
- Vous pouvez ajouter ou modifier les états initiaux selon votre code.
- Assurez-vous que le format des états est cohérent avec celui attendu par votre agent.

## Remerciements
Merci à tous ceux qui ont pris le temps de visiter et de tester cet agent de résolution du puzzle 8. Vos retours et suggestions sont précieux et contribuent à l'amélioration de ce projet.
N'hésitez pas à explorer, expérimenter et partager vos expériences !

