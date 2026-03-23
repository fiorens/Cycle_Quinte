# 🎼 Outils Musicaux Interactifs

Une suite d'outils web haute performance, sans dépendances, conçue pour accompagner les musiciens dans l'étude de la théorie, la pratique rythmique et l'entretien de leur instrument.

🚀 **Accès rapide aux outils :**
* [🎡 Cycle des Quintes](https://fiorens.github.io/Cycle_Quinte/index.html)
* [⏱️ Métronome Pro](https://fiorens.github.io/Cycle_Quinte/metronome.html)
* [🎸 Accordeur Chromatique](https://fiorens.github.io/Cycle_Quinte/Accordeur.html)

---

## 🎸 Accordeur Chromatique Pro
Un analyseur de fréquences en temps réel ultra-précis pour accorder n'importe quel instrument (Guitare, Basse, Violon, Piano).

### 🌟 Fonctionnalités
* **Détection de Pitch Haute Précision :** Utilise un algorithme d'autocorrélation pour isoler la fréquence fondamentale.
* **Affichage Scientifique :** Affiche la note (Notation Française), l'octave précise (ex: Do 3) et la fréquence exacte en Hz.
* **Jauge de Précision (Cents) :** Système d'aiguille visuelle pour un réglage fin à +/- 50 cents.
* **Code Couleur Intelligent :** L'interface passe au **Vert** dès que la note est parfaitement juste (< 5 cents d'écart).
* **Optimisation Audio :** Désactivation automatique des filtres système (écho/bruit) pour une capture pure de l'instrument.

---

## ⏱️ Métronome Universel Pro
Un métronome capable de gérer des structures rythmiques allant de la simple marche aux mesures complexes de la musique contemporaine.

### 🌟 Fonctionnalités
* **Signatures Rythmiques Totales :** Contrôle indépendant du numérateur (1 à 16) et du dénominateur (1 à 64).
* **Gestion Binaire & Ternaire :** Adaptation automatique du ressenti visuel et sonore.
* **Pulsations Contrastées :** Accentuation sonore et visuelle (Vert/Bleu) pour différencier les temps forts des temps faibles.
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
L'intégralité de la suite est développée en **Vanilla JavaScript**, garantissant une exécution instantanée sur n'importe quel navigateur moderne (testé sur Ubuntu 24.04).

* **Web Audio API :** * *Synthèse :* Génération de clics via oscillateurs pour le métronome (latence zéro).
    * *Analyse :* Capture et traitement du flux micro via `AnalyserNode` pour l'accordeur.
* **Algorithmique :** Implémentation de la transformée de Fourier et de l'autocorrélation pour la détection de pitch.
* **Zéro Dépendance :** Pas de frameworks, pas de bibliothèques externes, pas de fichiers audio lourds.

---

## 🤝 Contribution
Le projet est en constante évolution. N'hésitez pas à ouvrir une Issue pour suggérer une amélioration ou à proposer une Pull Request.

Développé avec passion pour les musiciens. 🎹
