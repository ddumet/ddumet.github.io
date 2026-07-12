---
title: IA & Agro-Écologie — Prédire la santé des plantes par spectrométrie
date: 2020-08-01 12:00:00 +0200
categories: [Projets Pro Senseen]
tags: [machine-learning, python, agro-tech, web-services]
description: Développement et déploiement de modèles prédictifs basés sur des données multi-modales (spectrométrie NIR, sols, météo) pour le suivi de la santé des plantes.
---

Dans le cadre de mes fonctions en tant qu'Ingénieur Machine Learning chez **Senseen**, j'ai orchestré la conception et le déploiement opérationnel de modèles d'intelligence artificielle destinés à l'agriculture. L'objectif principal était de fournir aux viticulteurs et agriculteurs un outil d'aide à la décision fiable, pour monitorer la santé des végétaux.

## Le Défi Technologique

Prédire l'état de santé et le stress hydrique ou nutritionnel des plantes à partir de capteurs de terrain, avant même que les symptômes ne soient visibles. Le projet reposait sur la fusion de sources de données hétérogènes et multi-modales :

* **Spectrométrie infrarouge (NIR) :** Scans directs des feuilles et des tissus végétaux.
* **Données pédologiques :** Analyses et compositions physico-chimiques des sols.
* **Données environnementales :** Historiques et prévisions météorologiques locales.

---

## Stack Technique & Approche ML

Pour mener à bien ce projet, j'ai mis en place un pipeline de données complet, de la collecte au déploiement :

* **Exploration & Préparation :** Traitement des signaux spectraux et feature engineering avancé sous **Python** (**NumPy**, **Pandas**, **Scikit-learn**).
* **Modélisation :** Entraînement et optimisation d'algorithmes de classification et de régression pour identifier les marqueurs de stress des plantes.
* **Industrialisation :** Encapsulation des modèles sous forme de micro-services via des APIs (**FastAPI** / **Flask**), permettant une intégration fluide avec les applications métiers des utilisateurs.

---

## Impact et Management

En plus de la dimension purement Data Science, ce projet a inclus une forte composante de gestion de projet et de terrain :

* **Lead Data :** Organisation et supervision des campagnes de collecte de données directement dans les vignobles et exploitations.
* **Mentorat :** Management et encadrement opérationnel de deux apprentis Data Scientists, favorisant la montée en compétences de l'équipe sur la stack d'IA de l'entreprise.

Ce projet démontre comment l'IA et les modèles prédictifs peuvent s'ancrer dans la transition agro-écologique en optimisant les ressources et en anticipant les risques sanitaires des cultures.
