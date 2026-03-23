# 🎼 Outils Musicaux Interactifs

Une suite d'outils web légers et performants conçus pour aider les musiciens dans leur pratique quotidienne et l'étude de la théorie.

🚀 **Démos en ligne :**
* [Accéder au Cycle des Quintes](https://fiorens.github.io/Cycle_Quinte/)
* [Accéder au Métronome Pro](https://fiorens.github.io/Cycle_Quinte/metronome.html)

---

## 🎡 Cycle des Quintes
Un outil de visualisation harmonique pour explorer les relations entre les tonalités, les armures et les degrés.

### 🌟 Fonctionnalités
* **Roue de navigation interactive :** Exploration visuelle des 12 tonalités majeures et mineures.
* **Analyse Harmonique Automatique :** Affiche instantanément les 7 degrés d'une gamme (I, ii, iii, IV, V, vi, vii°).
* **Dual-Notation :** Switch entre la notation Anglaise (C, D, E...) et Française (Do, Ré, Mi...).
* **Visualisation des Armures :** Indique précisément le nombre de dièses ou de bémols.
* **Gestion des Enharmonies :** Support complet des tonalités complexes (ex: Fa♯/Sol♭).

---

## ⏱️ Métronome Universel Pro
Un métronome de haute précision capable de gérer des structures rythmiques simples ou extrêmement complexes.

### 🌟 Fonctionnalités
* **Signatures Rythmiques Totales :** Contrôle indépendant du numérateur (1 à 16) et du dénominateur (1, 2, 4, 8, 16, 32, 64).
* **Gestion Binaire & Ternaire :** Adaptation visuelle et sonore selon l'unité de temps choisie (Noire, Croche, Triolet, etc.).
* **Pulsations Contrastées :** Différenciation visuelle et sonore entre le **Temps Fort** (Vert/Aigu) et les **Temps Faibles** (Bleu/Grave).
* **Large Plage de Tempo :** Réglage précis de 30 à 250 BPM.
* **Indicateurs Dynamiques :** Système de "dots" réactifs pour un suivi visuel parfait de la mesure.

---

## 🛠️ Détails Techniques
L'ensemble du projet est développé en **Vanilla JavaScript, HTML5 et CSS3**, garantissant une légèreté et une rapidité d'exécution optimales sans aucune dépendance externe.

* **Web Audio API :** Utilisation d'oscillateurs temps réel pour le métronome, garantissant une précision rythmique absolue et une absence de latence (pas de fichiers .mp3 externes).
* **Trigonométrie CSS :** Utilisation de `cos()` et `sin()` pour le placement dynamique des notes sur le cercle des quintes.
* **Interface Responsive :** Design adaptatif via CSS Flexbox et Grid pour une utilisation fluide sur ordinateur, tablette et smartphone (Ubuntu 24.04 friendly).

---

## 📖 Comment les utiliser ?

### Cycle des Quintes :
1.  **Sélectionnez une note** sur le cercle extérieur (Majeur) ou intérieur (mineur).
2.  **Observez les relations** : L'outil met en évidence la tonique, ses dominantes, ses sous-dominantes et ses relatifs.
3.  **Consultez le tableau** : Les accords correspondants s'affichent en bas pour faciliter la composition.

### Métronome :
1.  **Réglez votre signature** : Cliquez sur les chiffres de la fraction pour changer le nombre de temps ou l'unité.
2.  **Ajustez le tempo** : Utilisez le curseur pour définir votre vitesse de travail.
3.  **Lancez le rythme** : Appuyez sur DÉMARRER et suivez les indicateurs visuels colorés.

---

## 🤝 Contribution
Les suggestions et les rapports de bugs sont les bienvenus ! N'hésitez pas à ouvrir une Issue ou à proposer une Pull Request.

Développé avec passion pour les musiciens. 🎹
