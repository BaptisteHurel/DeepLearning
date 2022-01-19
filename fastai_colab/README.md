# TP Fast AI - Deep Learning
![History_of_artificial_intelligence_timeline](https://user-images.githubusercontent.com/58144828/150096770-ee4623ba-056f-41e9-b026-4acfc51368c2.jpg)

## 1) Resources 
- Course => https://course.fast.ai/
- Videos => https://course.fast.ai/videos/
- Colab notebooks => https://course.fast.ai/start_colab

## 2) Reminder
### 2.1) Types of machine learning
![image](https://user-images.githubusercontent.com/58144828/149974222-0bb940ce-24ed-44cd-a7a6-d393d683a724.png)

### 2.2) Noize Problem
Training your algo with noise
![1_zlxO7NuxK6ZijZtXnRl46Q](https://user-images.githubusercontent.com/58144828/150101230-b85184d5-705b-477c-bf71-803b1bf6a2f8.png)

### 2.3) Overfitting problem

### 2.4) Bias Variance tradeoff
![image](https://user-images.githubusercontent.com/58144828/150097848-3fa2558f-2041-4bd9-b94e-61a15c3f82d8.png)

### 2.5) Spliting for solution
Separate test data and training data (train / test / validation)
![training-validation-test-data-set-1024x552](https://user-images.githubusercontent.com/58144828/150102268-c3c5bf24-1404-451b-a739-5b0d127edf61.png)
- Train Data
- Test Data

### Find the balance
![Illustration-du-dilemme-biais-variance-Lorsque-la-complexite-du-modele-augmente](https://user-images.githubusercontent.com/58144828/150098729-06efe242-28cd-4b30-ac33-88a847da0c36.png)

### MLP - Multilayer perceptron
![2018-04-13_1330](https://user-images.githubusercontent.com/58144828/150099463-2085ca12-0037-4539-802d-d457a739d3da.png)

### Choix du poids
- Readjust the weights of our network (bias)
- Search for the minimum error rate / maximum success rate

## 1) 01_intro
Link : https://github.com/BaptisteHurel/Python/blob/master/TP%20Fast%20AI/01_intro.ipynb

## 2) 02_production
Link : https://github.com/BaptisteHurel/Python/blob/master/TP%20Fast%20AI/02_production.ipynb

## 3) Atelier-keras-CatsVSDogs
Link : https://github.com/BaptisteHurel/Python/blob/master/TP%20Fast%20AI/Atelier-keras-CatsVSDogs.ipynb

- La stratégie de ce transfert d'apprentissage consiste à exploiter la connaissance acquise sur un problème de classification général pour l’appliquer à un problème particulier.
- L'objectif de ce tutoriel est de montrer les capacités du transfert d'apprentissage permettant de résoudre des problèmes complexes avec des moyens de calcul modestes.
  
- **Keras** est une bibliothèque agissant au niveau du modèle : elle met à disposition des modules permettant de développer des modèles de deep learning (apprentissage profond) complexes
- **TensorFlow** est un outil open source d'apprentissage automatique développé par Google.

### Classification d'image à l'aide du Deep Learning
- Génération des données
- Définition du modèle
- Apprentissage
- Prédiction
- Extraction de nouvelle caractéristiques (features)
- Prédiction sur le jeu test de Kaggle