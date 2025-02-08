# Facial Emotion Recognition

Ce projet permet de reconnaître les émotions faciales à partir d'images en utilisant un modèle de réseau de neurones convolutif (CNN). Le modèle est entraîné sur un dataset public de Kaggle contenant des images faciales avec des annotations d'émotions. L'objectif est de prédire les émotions des individus à partir d'une image de leur visage.

---

## Table des matières

1. [Introduction](#introduction)
2. [Prérequis](#prérequis)
3. [Obtention du Dataset](#obtention-du-dataset)
4. [Entraînement du Modèle](#entrainement-du-modèle)
5. [Évaluation du Modèle](#evaluation-du-modèle)
6. [Utilisation du Modèle](#utilisation-du-modèle)
7. [Conclusion](#conclusion)

---

## Introduction

Le projet se base sur l'utilisation de réseaux de neurones convolutifs (CNN) pour identifier des émotions faciales à partir d'images. Le modèle prédit une des sept émotions principales : colère, dégout, peur, joie, tristesse, surprise ou neutre.

---

## Prérequis

- Python 3.x
- Bibliothèques Python : TensorFlow, Keras, OpenCV, Matplotlib, Pandas, NumPy

---

## Obtention du Dataset

Le dataset utilisé provient de la compétition **Facial Expression Recognition** sur **Kaggle**. Il contient des images d'expressions faciales annotées avec 7 émotions. Vous pouvez télécharger le dataset [ici](https://www.kaggle.com/datasets/msambare/fer2013).

---

## Entraînement du Modèle

Le modèle a été construit avec un réseau de neurones convolutif (CNN) pour extraire les caractéristiques des images et les classifier en fonction des émotions. Les images ont été prétraitées pour être normalisées et les étiquettes d'émotions ont été converties en format one-hot encoding.

---

## Évaluation du Modèle

Le modèle a été évalué sur un ensemble de test séparé. La performance du modèle a été mesurée par la précision (accuracy) de la classification des émotions.

---

## Utilisation du Modèle

Une fois le modèle entraîné, il peut être utilisé pour prédire les émotions sur de nouvelles images. Le modèle fournit une prédiction des émotions faciales en temps réel en fonction des données d'entrée.

---

## Conclusion

Ce projet permet de classifier des émotions faciales à l'aide d'un réseau de neurones convolutif, et montre l'application du deep learning dans l'analyse des images faciales. Le modèle peut être amélioré avec davantage de données et d'expérimentations sur différentes architectures.

---

### Contribuer

Les contributions sont les bienvenues ! Si vous souhaitez contribuer à ce projet, vous pouvez soumettre une **pull request**.

---

### Licence

Ce projet est sous licence [MIT](LICENSE).
