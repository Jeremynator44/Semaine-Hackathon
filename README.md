# 🚴‍♂️ Parking Angers - "Tous au Sport !" 🏋️‍♀️

## 📋 Description

Ce projet s'inscrit dans l'initiative **"Tous au Sport !"** portée par la ville d'Angers, qui vise à combiner **transport durable (vélo)** et **accès aux équipements sportifs**. L'application permet :

1. De localiser les **parkings vélos** ou **parkings voitures** les plus proches d'un équipement sportif.
2. De lister les **activités sportives disponibles** à Angers et de permettre à l'utilisateur de choisir un équipement sportif correspondant.
3. D'afficher les distances entre les parkings et les équipements sportifs sélectionnés.

Le projet utilise **Leaflet.js** pour afficher les données sur une carte interactive et récupère les informations depuis des fichiers JSON locaux ou des APIs ouvertes.

---

## 🌟 Fonctionnalités

- **Affichage sur carte :**
    - Les **parkings vélos**, **parkings voitures** et **installations sportives** sont affichés dynamiquement sur une carte interactive.
    - Les points d'intérêt sont triés et filtrés en fonction des sélections de l'utilisateur.

- **Liste des activités sportives :**
    - Les activités sportives disponibles à Angers sont listées dynamiquement à partir des données des installations sportives.
    - L'utilisateur peut sélectionner une activité pour filtrer les équipements correspondants.

- **Mise à jour automatique :**
    - Lorsqu'un type de point d'intérêt est sélectionné (vélo, voiture ou installations sportives), les données affichées sur la carte se mettent à jour automatiquement.

- **Adaptation à l'utilisateur :**
    - L'utilisateur peut indiquer sa **position géographique** pour trouver l'équipement sportif le plus proche et les parkings à proximité.

---

## 📁 Structure des données

### Fichiers JSON utilisés :
1. **Parkings vélos :**
     - URL : [API Parkings Vélos](https://angersloiremetropole.opendatasoft.com/explore/dataset/parking-velo-angers/information/)
     - Contient les coordonnées des parkings vélos à Angers.

2. **Parkings voitures :**
     - URL : [API Parkings Voitures](https://angersloiremetropole.opendatasoft.com/explore/dataset/parking-angers/table/)
     - Inclut les coordonnées et la disponibilité des places.

3. **Installations sportives :**
     - URL : [API Installations Sportives](https://angersloiremetropole.opendatasoft.com/explore/dataset/equipements-sportifs-angers/information/)
     - Comprend les coordonnées et le champ `ACTIVITE` listant les sports disponibles.

---

## 📌 Utilisation

1. Sélectionner un type de point d'intérêt :
     - Parkings vélos, parkings voitures ou installations sportives.
     - Les données correspondantes s'affichent automatiquement sur la carte.

2. Consulter les activités sportives disponibles :
     - Les activités sont affichées dans une liste sous la carte.
     - Sélectionnez une activité pour filtrer les équipements sportifs correspondants.

3. Consulter les distances :
     - Les distances entre les parkings et les équipements sportifs sont calculées (fonctionnalité à améliorer dans la version suivante).

---

## 📦 Technologies utilisées

- **HTML/CSS/JavaScript**
- **Leaflet.js** : Bibliothèque pour les cartes interactives.
- **Fetch API** : Pour charger les données depuis des fichiers JSON locaux.
- **Node.js / Python** : Serveur local pour gérer les appels aux fichiers JSON.

---

## 🚀 Améliorations futures

- Calculer les distances exactes entre les parkings et les équipements sportifs en utilisant des formules géographiques (par exemple, Haversine).
- Permettre à l'utilisateur d'indiquer sa position pour afficher les équipements et parkings les plus proches.
- Ajouter des informations détaillées sur les équipements sportifs (horaires, disponibilité, etc.).
- Optimiser le code pour une meilleure performance et lisibilité.

---

## ⚙️ Installation

### Prérequis :
- **Node.js** ou **Python** pour démarrer un serveur local.
- Un navigateur moderne compatible avec JavaScript.

### Étapes :
1. Clonez ce dépôt :
     ```bash
     git clone https://github.com/Jeremynator44/Semaine-Hackathon.git
     cd parking-angers
     ```

2. Installez les dépendances et démarrez le serveur :
     ```bash
     npm install
     npm start
     ```

---

## 👤 Contributeur

Ce projet a été développé dans le cadre du Hackathon Angers - Tous au Sport.

---

## 📄 Charte d'utilisation

Ce projet a été développé avec l'aide d'outils de productivité comme ChatGPT. Les suggestions générées ont été adaptées manuellement pour répondre aux besoins spécifiques du projet.

---

## 📹 Vidéo de présentation

Lien à ajouter ici : Vidéo de présentation
https://www.youtube.com/watch?v=hjoI2F-c1Wo

---

## 📧 Contact

Pour toute question ou suggestion, veuillez contacter votre-email@exemple.com.