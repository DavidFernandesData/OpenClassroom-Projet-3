#Projet 3 — Réalisez une étude de santé publique (FAO) avec R ou Python




Contexte — Vous intégrez une équipe de la FAO (ONU) pour contribuer à une étude sur l’alimentation et la sous‑nutrition. L’ancien analyste a couvert 2018→présent ; votre périmètre est l’historique 2013→2017. Les livrables seront présentés en soutenance.

🎯 Objectifs & compétences

Manipuler, nettoyer et documenter des données publiques FAO.

Réaliser une analyse exploratoire (EDA) et des visualisations interprétables.

Structurer une narration claire et reproductible via Notebook (R ou Python).

Synthétiser les enseignements dans un executive summary et des slides.

📦 Livrables

notebooks/etude_fao_2013_2017.ipynb ou notebooks/etude_fao_2013_2017.Rmd (reproductible de A→Z).

figures/ : graphiques exportés (.png/.svg, 300 dpi).

data/processed/ : données nettoyées + dictionnaire (lexique).

slides/presentation_etude_fao.pptx : ≤ 10 slides, ≤ 7 éléments/slide.

reports/executive_summary.md : conclusions, limites, recommandations.

env/requirements.txt (Python) ou env/renv.lock (R) ; env/environment.yml optionnel.

🔍 Données & périmètre

Période analysée : 2013–2017 (historique). Comparaison possible avec 2018+ (travail existant).

Sources : fichiers FAO (PJ), + lexique (définitions, unités, codes pays).

Points d’attention : cohérence d’unités, ruptures de séries, données manquantes, population (dénominateur), agrégations régionales.

📊 Questions d’analyse (guide)

Tendances globales de la sous‑nutrition (prévalence & effectifs) 2013–2017.

Écarts régionaux (ex. Afrique subsaharienne, Asie du Sud, Amérique latine…).

Distribution par pays (quartiles, outliers) et trajectoires notables.

Co‑évolution avec variables contextuelles disponibles (ex. disponibilités kcal/hab, population).

Limites & sensibilités : qualité/complétude, changements méthodo, effets d’agrégation.

🧪 Méthodologie (notebook)

Import & contrôle : lecture, typage, checks (dédoublonnage, NA, bornes).

Nettoyage : renommage clair, harmonisation des codes pays, normalisation des dates.

EDA : statistiques descriptives, corrélations simples, tableaux récap.

Viz : séries temporelles, barres empilées régionales, boxplots pays, carte choroplèthe (optionnel).

Synthèse : messages clés, incertitudes, implications politiques.

🗣️ Storyline pour la soutenance

Contexte & objectifs (1 slide)

Données & méthode (1–2)

Résultats clés 2013–2017 (3–4)

Focales régionales/pays (2)

Limites & implications (1)

Conclusion & pistes (1) + pont 2018+

🔐 Éthique & conformité

Données publiques FAO : respecter les conditions d’utilisation.

RGPD/éthique : pas de ré‑identification ; prudence sur les comparaisons sensibles.

📚 Ressources

Cours recommandés : Python & R (OpenClassrooms).

Supports : Ébauche de présentation (PJ), Notebooks (R/Python), Lexique.

🔎 Extraits des fichiers fournis

Présentation (PDF) : titres et sections clés — Kilocalories par habitant ; Liste des céréales (ex. avoine, millet, sorgho, « Céréales, autres ») ; Top 10 pays ayant le plus bénéficié de l’aide alimentaire (2013–2016) ; Évolution de l’aide alimentaire pour les 5 pays principaux (Syrie, Yémen, Soudan, Soudan du Sud, …).

Notebook PDF : plan structuré — 2.1 Population, 2.2 Disponibilité alimentaire, 2.3 Aide alimentaire, 2.3 Sous‑nutrition ; modules méthodo 3.3 Nombre théorique de personnes nourries (végétaux), 3.4 Utilisation de la disponibilité intérieure ; sorties avec tableaux et impressions de dimensions des datasets.

Notebook .ipynb : cellules d’import & d’EDA, commentaires pédagogiques, import pandas as pd.

📈 Faits saillants (issus des notebooks/PDF)

Capacité théorique d’alimentation (2017) :

Avec la disponibilité totale: ~139 % de la population mondiale pourrait être nourrie (calcul basé sur ~2 000 kcal/j/hab).

Avec la seule origine végétale: ~92 % (hypothèse ~2 500 kcal/j/hab pour les végétaux).

Aide alimentaire (2013–2016) : concentration sur un petit nombre de pays avec en tête Syrie, Yémen, Soudan, Soudan du Sud (liste Top 10 et séries temporelles dans la présentation).

Données thématiques : suivis par pays/année, disponibilité en kcal/hab/j, ventilations par origine (végétale/animale) et usage (nourriture, pertes, semences, aliments pour animaux, variation de stock).

Ces éléments sont intégrés pour contextualiser le README et guider la soutenance. Remplacez/complétez selon vos résultats finaux.

👤 Auteur & licence

Auteur : David Fernandes — David.Fernandes.data@gmail.com

Licence : CC BY‑NC‑SA 4.0
