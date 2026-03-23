# 🎼 Outils Musicaux Interactifs

Une suite d'outils web haute performance, sans dépendances, conçue pour accompagner les musiciens dans l'étude de la théorie, la pratique rythmique et l'entretien de leur instrument.

🚀 **Accès rapide aux outils :**
* [🎡 Cycle des Quintes](https://fiorens.github.io/Cycle_Quinte/index.html)
* [⏱️ Métronome](https://fiorens.github.io/Cycle_Quinte/Metronome.html)
* [🎸 Accordeur Chromatique](https://fiorens.github.io/Cycle_Quinte/Accordeur.html)

---

## 🎸 Accordeur Chromatique
Un analyseur de fréquences en temps réel optimisé pour une utilisation mobile et desktop.

### 🌟 Fonctionnalités
* **Moteur de Détection Avancé :** Utilise l'autocorrélation combinée à une **interpolation parabolique** pour une précision sous le hertz.
* **Stabilité Mobile :** Algorithme de lissage adaptatif (Low-pass filter) pour ignorer les parasites et stabiliser l'aiguille sur les cordes graves.
* **Mode Anti-Veille (Wake Lock) :** Utilise l'API Screen Wake Lock pour empêcher l'écran du smartphone de s'éteindre pendant l'accordage.
* **Affichage Scientifique :** Note en notation française, octave réelle (Standard Scientifique) et fréquence exacte.
* **Indicateur de Justesse :** Jauge dynamique de +/- 50 cents avec retour visuel colorimétrique (Vert = Accordé à moins de 5 cents).

---

## ⏱️ Métronome
Un métronome précis au millier de seconde près, capable de gérer des structures rythmiques complexes.

### 🌟 Fonctionnalités
* **Signatures Rythmiques Totales :** Contrôle indépendant du numérateur (1 à 16) et du dénominateur (1 à 64).
* **Gestion Binaire & Ternaire :** Adaptation automatique du ressenti visuel et sonore.
* **Pulsations Contrastées :** Accentuation sonore et visuelle pour différencier les temps forts des temps faibles.
* **Large Plage de Tempo :** De 30 à 250 BPM.

---

## 🎡 Cycle des Quintes
Un outil de visualisation harmonique pour explorer les relations entre les tonalités et les accords.

### 🌟 Fonctionnalités
* **Roue Interactive :** Navigation fluide entre les 12 tonalités majeures et mineures.
* **Analyse Harmonique :** Affichage instantané des 7 degrés d'une gamme (I, ii, iii, IV, V, vi, vii°).
* **Dual-Notation :** Bascule instantanée entre la notation Anglaise (C, D, E...) et Française (Do, Ré, Mi...).
* **Visualisation des Armures :** Compteur dynamique de dièses et bémols.

---

## 🛠️ Détails Techniques
L'intégralité de la suite est développée en **Vanilla JavaScript**, garantissant une exécution instantanée sur n'importe quel navigateur moderne (testé sur Ubuntu 24.04 et navigateurs mobiles iOS/Android).

* **Web Audio API :** * *Synthèse :* Génération de clics via oscillateurs (latence zéro).
    * *Analyse :* Capture brute via `AnalyserNode` avec désactivation des filtres système (AGC, Echo cancellation) pour une analyse de fréquence pure.
* **Optimisation Mobile :** Implémentation de buffers circulaires pour le lissage des données et gestion de l'économie d'énergie.
* **Zéro Dépendance :** Aucun framework, aucune bibliothèque externe, aucune image ou fichier audio externe.

---

## 🤝 Contribution
Le projet est en constante évolution. N'hésitez pas à ouvrir une Issue pour suggérer une amélioration ou à proposer une Pull Request.

Développé avec passion pour les musiciens. 🎹
