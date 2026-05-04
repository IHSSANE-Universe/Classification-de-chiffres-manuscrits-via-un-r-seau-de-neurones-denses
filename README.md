# Classification de chiffres manuscrits (MNIST)

## Objectif
Développer et entraîner un modèle de réseau de neurones profond capable d'identifier des chiffres manuscrits avec une précision élevée.

## Architecture du Modèle
* **Entrée** : Aplatissement (Flatten) des images 28x28 en vecteurs de 784 pixels.
* **Couche cachée** : 128 neurones avec activation 'ReLU' pour capter les relations non-linéaires.
* **Régularisation** : Utilisation d'un 'Dropout' de 20% pour éviter le surapprentissage (overfitting).
* **Sortie** : 10 neurones avec activation 'Softmax' pour prédire la probabilité de chaque chiffre (0 à 9).

## Configuration technique
* **Optimiseur** : Adam.
* **Fonction de perte** : Sparse Categorical Crossentropy.
* **Métrique** : Précision (Accuracy)[cite: 1].

## Résultats attendus
* Entraînement sur 10 époques[cite: 1].
* Visualisation de l'évolution de la précision et de la perte via des graphiques Matplotlib[cite: 1].