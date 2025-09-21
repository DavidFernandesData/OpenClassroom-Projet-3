# OpenClassroom-Projet-3
Projet 3 — Étude de santé publique (FAO) avec R ou Python




Contexte — Vous rejoignez une équipe FAO (ONU) pour contribuer à une étude sur l’alimentation et la sous‑nutrition. Julien (ancien DA) a couvert 2018→aujourd’hui. Votre périmètre : historique 2013→2017. Livrables présentés lors d’une soutenance.

🧭 Résumé exécutif

Objectif : explorer, analyser et communiquer les tendances de sous‑nutrition mondiale (2013–2017) à partir des données FAO.

Méthode : Notebook Python (pandas, numpy, matplotlib/plotly, statsmodels) ou R (tidyverse, ggplot2, broom).

Sorties : Notebook reproductible, slides de synthèse, figures prêtes à l’impression, notes d’interprétation.

Collaboration : intégrer (ou comparer à) l’ébauche/notes de Julien (2018+), conserver un lexique commun.

🎯 Compétences visées

Manipulation & nettoyage de données (import, typage, valeurs manquantes, normalisation).

Analyse exploratoire (EDA) & dataviz interprétables pour non‑spécialistes.

Raisonnement analytique (hypothèses, métriques, limites) & storytelling.

Reproductibilité (environnements, seed, scripts, structure de dépôt).

📦 Livrables attendus

notebooks/etude_fao_2013_2017.ipynb ou notebooks/etude_fao_2013_2017.Rmd (exécutable de bout en bout).

slides/presentation_etude_fao.pptx (≤ 10 slides, ≤ 7 éléments/slide).

data/processed/ : jeux nettoyés + dictionnaire/lexique mis à jour.

figures/ : graphiques en .png/.svg (300 dpi) référencés dans le notebook.

reports/executive_summary.md : résumé des conclusions & recommandations.

Optionnel : requirements.txt / environment.yml (Python) ou renv.lock (R), Makefile/run.sh.
🔍 Données

Provenance : FAO — fichiers livrés en PJ (Données FAO.zip).

Périmètre d’analyse : 2013–2017 (historique). Pour mise en perspective, comparer aux points clés 2018+ (notes Julien).

Lexique : PJ3 (mettre à jour si renaming de variables).

Considérations : unités, périodicité, couverture géographique, changements méthodologiques.

📊 Questions d’analyse (guide)

Tendance globale de la sous-nutrition (prévalence/absolu) 2013–2017.

Découpage régional (ex. Afrique subsaharienne, Asie du Sud, Amérique latine…).

Distribution (quartiles, outliers) par pays/année.

Co‑évolution avec variables contextuelles disponibles (ex. approvisionnement kcal/hab, population).

Écarts vs 2018+ (pont méthodologique avec le travail de Julien, si pertinent).

Sensibilités & limites : qualité des données, ruptures de séries, imputations.

Ajoutez toute analyse complémentaire pertinente (saisonnalité, comparaison par revenu, clusterisation simple, etc.).

🧪 Méthodologie (notebook)

Préparation : description des fichiers, chargement, dictionnaire, contrôles de cohérence.

Nettoyage : renommage clair, formats de dates, gestion NA/outliers, clés (pays/année).

EDA : stats descriptives, tableaux/bornes de confiance simples.

Viz : séries temporelles, barres empilées par région, cartes choroplèthes (optionnel), distributions.

Synthèse : messages clés & implications politiques.

🗣️ Storyline recommandée (pour la soutenance)

Contexte & données (1 slide).

Tendances clés 2013–2017 (2–3 slides).

Focus régions/pays (2 slides).

Facteurs associés & limites (1–2 slides).

Conclusion & pistes (1 slide) + pont vers 2018+.

🔐 Éthique & conformité

Données publiques FAO : respecter les conditions d’utilisation.

Respecter la RGPD et l’éthique de publication (pas de ré‑identification).

📚 Ressources

Cours OpenClassrooms : Python | R (recommandés par Julien).

PJ1 : Ébauche de trame (avec commentaires) — point de départ.

PJ4 : Notebooks (Python & R) — libre d’adapter.
