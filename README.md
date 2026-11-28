# HelpMyEmperor — Codex & Guide Tactique *Age of Empires IV*

**HelpMyEmperor** est une application web monopage (SPA) conçue pour aider les joueurs d'*Age of Empires IV* à préparer leurs parties, comprendre les mécaniques complexes et prendre les bonnes décisions stratégiques en quelques secondes.

---

## Fonctionnalités principales

* **Couverture des 25 civilisations :** Analyse détaillée des forces, faiblesses, mécaniques uniques, cartes favorables et compositions d'unités pour l'ensemble des civilisations du jeu de base et des extensions.
* **Mode Écran de Chargement (`Ma Civ vs Adversaire`) :** Sélectionnez votre civilisation et celle de votre adversaire pour obtenir un briefing rapide :
  * Verdict du duel (*Favorable*, *Équilibré*, *Difficile* ou *Miroir*).
  * Menace principale de l'adversaire, repère de scouting et timing critique.
  * Réponse recommandée (transition d'Âge, unités clés, priorité à la forge) et condition de victoire.
* **Frise des Timings Critiques & Power Spikes (`0:00 → 20:00+`) :** Visualisation des pics de puissance, fenêtres de vulnérabilité et points de contrôle clés au fil de la partie.
* **Passages d'Âge & Planificateur de Synergie :** Fiches comparatives des choix d'Âge (monuments, commanderies de l'Ordre du Temple, ailes modulaires, dynasties chinoises / Zhu Xi, etc.) avec composition d'un plan de partie exportable en un clic.
* **Build Orders & Chronologie :** Repères d'ouverture et séquences clés pour structurer le début de partie.

---

## Architecture & Stack technique

Le projet repose sur une architecture légère et autonome, sans dépendance serveur complexe :

* **Interface & Mise en page :** HTML5, Tailwind CSS, esthétique sobre et technique pensée pour une lecture rapide.
* **Logique & Données :** JavaScript natif (données structurées des civilisations, rendus dynamiques des onglets, du comparateur d'Âges et du mode duel).
* **Déploiement :** Hébergement statique compatible **GitHub Pages**.

---

## Utilisation & Déploiement

### En local
1. Clonez le dépôt :
   ```bash
   git clone git@github.com:gaetan-laplace/Sector2401.git
   cd Sector2401
