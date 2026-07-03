<div align="center">

# 🛫 Guirlande

### Système Intelligent de Balisage de Piste d'Atterrissage

_Travaux Pratiques - Objets Connectés et Capteurs_

![Statut](https://img.shields.io/badge/Statut-En%20cours-yellow?style=for-the-badge)
![Arduino](https://img.shields.io/badge/Arduino-UNO-00979D?style=for-the-badge&logo=arduino&logoColor=white)
![Bluetooth](https://img.shields.io/badge/Bluetooth-Contrôle%20à%20distance-0082FC?style=for-the-badge&logo=bluetooth&logoColor=white)
![IoT](https://img.shields.io/badge/IoT-Objets%20Connectés-6A5ACD?style=for-the-badge)
![Année](https://img.shields.io/badge/Année%20Académique-2025--2026-informational?style=for-the-badge)

**Institut Africain d'Informatique (IAI) - Gabon**
Objects Connectés

</div>

---

## 📑 Sommaire

- [Contexte](#-contexte)
- [Le projet en bref](#-le-projet-en-bref)
- [Équipements](#-équipements-utilisés)
- [Phases de réalisation](#️-phases-de-réalisation)
- [Contenu du dépôt](#-contenu-du-dépôt)
- [Équipe](#-équipe-1)
- [Conclusion](#-conclusion)

---

## 🌍 Contexte

Dans le cadre des travaux pratiques en objets connectés et capteurs, l'équipe a conçu un objet intelligent baptisé **« Guirlande »**, illustrant les principes fondamentaux de l'**Internet des Objets (IoT)** : capter une information de l'environnement, la traiter, puis agir en conséquence de manière automatisée.

> 🎯 **Problématique - Phoenix Airline**
> L'éclairage actuel de la piste d'atterrissage et de décollage est inadapté, statique et réagit mal aux conditions environnementales. Cela compromet la sécurité des manœuvres aéroportuaires, réduit la visibilité des pilotes et engendre un gaspillage énergétique.

**🚀 Objectif du projet :** passer d'un éclairage inefficace à un **balisage de piste intelligent**, garantissant à la fois une sécurité optimale et une maîtrise de la consommation énergétique, grâce à la détection de présence et à la commande dynamique de sorties lumineuses.

---

## 🎯 Le projet en bref

| 🔍 Question    | 💡 Réponse                                                                                                                                  |
| :------------- | :------------------------------------------------------------------------------------------------------------------------------------------ |
| **Quoi ?**     | Un dispositif capable de détecter automatiquement la présence d'un avion et de déclencher l'éclairage de la piste sans intervention humaine |
| **Pourquoi ?** | ⚡ Optimisation énergétique · 🤖 Réduction de l'intervention humaine · 🛡️ Amélioration de la sécurité au sol                                |
| **Comment ?**  | Un **Arduino UNO** + capteur de mouvement **HC-SR04** pour la détection, et un **module Bluetooth** pour le contrôle à distance             |
| **Où ?**       | Une piste de décollage/atterrissage d'avions, où le système fonctionne de manière fiable et autonome                                        |

---

## 🧰 Équipements utilisés

<div align="center">

| Composant          | Quantité | Rôle                                                   |
| :----------------- | :------: | :----------------------------------------------------- |
| 🔌 BreadBoard      |    1     | Plaque d'essai sans soudure pour relier les composants |
| 🧠 Arduino UNO     |    1     | Microcontrôleur pilotant l'ensemble du système         |
| 📶 Carte Bluetooth |    1     | Communication sans fil avec l'application mobile       |
| ⚡ Résistances     |    8     | Protection des Leds contre une intensité excessive     |
| 💡 Leds            |    8     | Points d'éclairage simulant le balisage de piste       |
| 🔗 Câble USB       |    1     | Alimentation et programmation de l'Arduino             |
| 🧵 Jumpers         |    14    | Connexions entre Arduino, BreadBoard et composants     |
| 📡 Capteur HC-SR04 |    1     | Détection de la présence/approche d'un avion           |

</div>

---

## 🛠️ Phases de réalisation

```
Phase 1 ──▶ Phase 2 ──▶ Phase 3 ──▶ Phase 4 ──▶ Phase 5 ──▶ Phase 6 ──▶ Phase 7
Alimen-      Résis-       Leds         Capteur      Bluetooth    Program-     Tests &
tation       tances       câblées      câblé        connecté     mation       validation
```

| Phase  | Description                                                                       |
| :----: | :-------------------------------------------------------------------------------- |
| **1️⃣** | Connexion des broches d'alimentation (5V et GND) entre l'Arduino et la BreadBoard |
| **2️⃣** | Câblage des résistances en série avec chaque future Led                           |
| **3️⃣** | Câblage des Leds à la suite de leur résistance respective                         |
| **4️⃣** | Câblage du capteur de mouvement via les Jumpers                                   |
| **5️⃣** | Connexion de la carte Bluetooth sur la BreadBoard                                 |
| **6️⃣** | Programmation du système sur l'IDE Arduino (lecture capteur + pilotage des Leds)  |
| **7️⃣** | Tests et validation (détection, réponse des Leds, contrôle Bluetooth)             |

---

## 📁 Contenu du dépôt

| 📂 Fichier / Dossier                                                             | 📝 Description                                                                         |
| :------------------------------------------------------------------------------- | :------------------------------------------------------------------------------------- |
| [`Code_Arduino_IDE.txt`](./Code_Arduino_IDE.txt)                                 | 💻 Code Arduino (`.ino`) - lecture du capteur HC-SR04 et pilotage automatique des Leds |
| [`Piste_Intelligente.pptx`](./Piste_Intelligente.pptx)                           | 📊 Support PowerPoint de présentation du projet                                        |
| TP1_Guirlandes connectées.mp4                                                    | 🎬 Vidéo de présentation et de démonstration du système                                |
| [`rapport_complet_projet_Guirlande.pdf`](./rapport_complet_projet_Guirlande.pdf) | 📄 Rapport complet du TP (contexte, équipements, phases, apports, conclusion)          |

---

## 👥 Équipe 1

<div align="center">

| 👤 Membre                                                                                            | 🛠️ Contribution                                                  |
| :--------------------------------------------------------------------------------------------------- | :--------------------------------------------------------------- |
| **<a href="https://github.com/Lebonheur2370/">BAMBO Le Bonheur </a>**                                                                | Programmation Arduino pour la gestion automatique de l'éclairage |
| **<a href="https://github.com/JamyBee/">BARESSY Samuelle Jamila </a>** | Résistances et Leds - câblage et rôle dans le circuit            |
| **<a href="https://github.com/Thrylos77">DANSOU KOFFI Junior </a>**                                                             | Fonctionnement de l'Arduino UNO et montage de la BreadBoard      |
| **<a href="https://github.com/Thierno-dtd/">DOUTHE Thierno David </a>**            | Application de contrôle Bluetooth et interface                   |
| **<a href="https://github.com/thethal/">EKOME EKOME Elie Thales </a>**                                                         | Essais de connexion Arduino / BreadBoard / Jumpers               |
| **<a href="https://github.com/epsilon10763/">EYA'A BILOGHE Norwen </a>**                              | Capteur de mouvement et son intégration                          |
| **<a href="https://github.com/IRJ-Prime/">ILOUMBOU Roland Junior</a>**                               | Documentation des phases et préparation du rapport               |
| **<a href="https://github.com/Sam-10-Ph">ISSAMBOU Jean Samuel </a>**                                 | Module Bluetooth et modalités de contrôle à distance             |

</div>

**🖋️ Correcteur :** Mr. TAKOUMBO Yvan
**🏫 Supervision académique :** IAI Gabon - Objects Connectés

---

## ✅ Conclusion

Ce projet a permis de poser les bases théoriques et pratiques sur les objets connectés, en alignant le travail sur un contexte pertinent : l'**automatisation de l'éclairage d'une piste d'atterrissage**. La définition du matériel, la planification des sept phases de montage et la répartition des recherches au sein du groupe constituent une fondation solide.

**🔜 Prochaines étapes :**

- [ ] Câblage effectif du circuit sur la BreadBoard
- [ ] Programmation complète de l'Arduino
- [ ] Réalisation de la maquette physique
- [ ] Tests finaux de détection et de contrôle à distance via Bluetooth

---

<div align="center">

</div>
