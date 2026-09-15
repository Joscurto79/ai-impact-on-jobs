# 📊 Observatoire RH — Compétences & Risque IA (2024–2030)

> Cockpit décisionnel exécutif d'aide à la reconversion professionnelle (reskilling) face à l'impact de l'intelligence artificielle sur l'emploi.

🔗 **[Accéder au Dashboard en direct (GitHub Pages)](https://TON-PSEUDO.github.io/NOM-DU-DEPOT/)**

---

## 🎯 Problématique Métier & Objectifs
L'automatisation croissante redéfinit les besoins en compétences. Ce projet fournit aux directions RH et décideurs un outil analytique à double détente :
1. **Identifier les métiers en zone critique (Quadrant Q1) :** Profils combinant une forte vulnérabilité à l'automatisation ($\ge 50\%$) et une contraction nette des recrutements d'ici 2030 ($< 0\%$).
2. **Actionner les plans de formation ciblés :** Relier chaque métier sous tension aux compétences logicielles transversales pour piloter la montée en compétences (*up-skilling* et *reskilling*).

---

## 📐 Méthodologie & Métriques

* **Vivier d'Emplois (2024) :** Volume d'opportunités de recrutement initiales (`SUM([Job Openings (2024)])`).
* **Évolution Nette Projetée (2024–2030) :**  
  $$\text{Croissance} = \frac{\text{Emplois Projetés 2030} - \text{Emplois 2024}}{\text{Emplois 2024}}$$
* **Indicateur de tension (KPI Q1) :** Décompte distinct des intitulés de postes (`COUNTD([Job Title])`) basculant sous le seuil critique pour la région et le secteur sélectionnés.
* **Transversalité des Compétences :** Identification des outils clés par volume d'emplois dédoublonné et fréquence métier.

---

## 🛠️ Stack Technique
* **Business Intelligence :** Tableau Cloud (Modélisation LOD FIXED, filtres de contexte, actions de filtrage interactives).
* **Front-End & Intégration :** Tableau Embedding API v3 (Composant `<tableau-viz>`), HTML5 / CSS3 moderne (*Card UI*).
* **Hébergement & Déploiement :** GitHub Pages.

---

## 💡 Guide d'Interaction
1. **Filtres globaux :** Sélectionner une région géographique ou une industrie pour adapter le calcul des quadrants aux réalités locales.
2. **Scatter Plot interactif :** Cliquer sur une bulle métier (ex. dans le quadrant rouge Q1) pour filtrer instantanément la liste des technologies associées.
3. **Plan d'action :** Identifier les compétences prioritaires à financer dans le catalogue de formation.
