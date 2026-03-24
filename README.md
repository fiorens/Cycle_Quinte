# 🎼 Outils Musicaux Interactifs

Une suite d'outils web haute performance, **0 dépendance**, conçue pour accompagner les musiciens dans l'exploration harmonique, la pratique rythmique et l'entretien de leur instrument.

🚀 **Accès rapide aux outils :**
* [🧭 **Le Compas Harmonique**](https://fiorens.github.io/Cycle_Quinte/Compas.html) — *Nouveau : Navigation & Modulation*
* [🎡 Cycle des Quintes](https://fiorens.github.io/Cycle_Quinte/Cycle.html)
* [⏱️ Métronome](https://fiorens.github.io/Cycle_Quinte/Metronome.html)
* [🎸 Accordeur Chromatique](https://fiorens.github.io/Cycle_Quinte/Accordeur.html)

---

## 🧭 Le Compas Harmonique
Un véritable **GPS pour compositeurs** conçu pour briser les blocages créatifs et explorer les transitions d'accords fluides.

### 🌟 Fonctionnalités
* **Station de Modulation :** Configurez votre tonalité de départ et basculez instantanément entre les modes **Majeur** et **Mineur**.
* **Système de Pivot Intelligent :** En cliquant sur un accord, l'outil ouvre trois axes de réflexion :
    * **🏠 Rester :** Suggestions basées sur les cadences classiques et la **Cadence Rompue** (V → vi) pour prolonger le mouvement.
    * **🚀 Voyager :** Interface de modulation pour transformer dynamiquement l'accord sélectionné en nouvelle Tonique.
    * **🎸 Styles & Astuces :** Accords "Hors-piste" incluant le **$\flat$VII (Son Rock)**, les **Dominantes Secondaires** (Tapis rouge) et les **Liens Diminués** (Glisse chromatique).
* **Code Couleur Harmonique :** Repérage visuel immédiat des fonctions (Repos, Mouvement, Tension).

---

## 🎸 Accordeur Chromatique
Un analyseur de fréquences en temps réel optimisé pour une utilisation mobile et desktop avec une précision chirurgicale.

### 🌟 Fonctionnalités
* **Moteur de Détection Avancé :** Utilise l'autocorrélation combinée à une **interpolation parabolique** pour une précision sous le hertz.
* **Stabilité Mobile :** Algorithme de lissage adaptatif (Low-pass filter) pour ignorer les parasites et stabiliser l'aiguille sur les cordes graves.
* **Mode Anti-Veille (Wake Lock) :** Utilise l'API Screen Wake Lock pour empêcher l'écran du smartphone de s'éteindre pendant l'accordage.
* **Indicateur de Justesse :** Jauge dynamique de +/- 50 cents avec retour visuel colorimétrique (Vert = Accordé à moins de 5 cents).

---

## ⏱️ Métronome
Un métronome précis au millier de seconde près, capable de gérer des structures rythmiques complexes.

### 🌟 Fonctionnalités
* **Signatures Rythmiques Totales :** Contrôle indépendant du numérateur (1 à 16) et du dénominateur (1 à 64).
* **Gestion Binaire & Ternaire :** Adaptation automatique du ressenti visuel et sonore.
* **Pulsations Contrastées :** Accentuation sonore via oscillateurs pour différencier les temps forts des temps faibles.

---

## 🎡 Cycle des Quintes
Un outil de visualisation harmonique pour explorer les relations entre les tonalités et les accords.

### 🌟 Fonctionnalités
* **Roue Interactive :** Navigation fluide entre les 12 tonalités majeures et mineures.
* **Analyse Harmonique :** Affichage instantané des 7 degrés d'une gamme (I, ii, iii, IV, V, vi, vii°).
* **Dual-Notation :** Bascule instantanée entre la notation Anglaise (C, D, E...) et Française (Do, Ré, Mi...).

---

## 🛠️ Détails Techniques
L'intégralité de la suite est développée en **Vanilla JavaScript**, garantissant une exécution instantanée sur n'importe quel navigateur moderne (testé sur Ubuntu 24.04 et navigateurs mobiles).

* **Web Audio API :** Synthèse via oscillateurs (latence zéro) et capture brute via `AnalyserNode` pour une analyse de fréquence pure.
* **Mathématiques Harmoniques :** Calculs dynamiques des intervalles et des degrés sans bases de données pré-enregistrées.
* **Optimisation Mobile :** Implémentation de buffers circulaires pour le lissage des données et gestion de l'économie d'énergie.
* **Zéro Dépendance :** Aucun framework, aucune bibliothèque externe, iconographie en **SVG pur** pour un poids plume.

---

## 🤝 Contribution
Le projet est en constante évolution. N'hésitez pas à ouvrir une Issue pour suggérer une amélioration ou à proposer une Pull Request.

Développé avec passion pour les musiciens. 🎹
