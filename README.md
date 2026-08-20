### Zobir Zeghoud — Data / MLOps Engineer

17 ans en Data & BI, spécialisé en Machine Learning et l'industrialisation de modèles en
production. Les projets ci-dessous sont tous des plateformes MLOps complètes — pas des notebooks
isolés : API, conteneurisation, tracking d'expériences, monitoring, et pour deux d'entre eux, une
démo en ligne.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-zzeghoud-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/zzeghoud)
[![Email](https://img.shields.io/badge/Email-z.zeghoud%40yahoo.com-EA4335?logo=gmail&logoColor=white)](mailto:z.zeghoud@yahoo.com)

---

#### Projets phares

**[rakuten_z](https://github.com/zz75da/rakuten_z)** — Classification multimodale de produits e-commerce
FastAPI (14 services) · Airflow · MLflow/DVC · Prometheus/Grafana · Kubernetes (HPA testé)
85 000 produits, 27 catégories, fusion tardive texte+image — 84,9% de précision (CLIP ViT-B/32)

**[income-inequality-mlops](https://github.com/zz75da/income-inequality-mlops)** — Prédiction des inégalités de revenus par pays
Airflow · DVC/DagsHub · MLflow avec gates de promotion en registre · Prometheus/Grafana · SHAP
Gini R² 0,614 · mobilité intergénérationnelle R² 0,358 · classe de revenu 99,1% — 3 modèles en Production
**[Démo en ligne](https://income-inequality-mlops-zz75da.streamlit.app/)**

**[MedSentry — confidentiality_level_pred](https://github.com/zz75da/confidentiality_level_pred)** — Classificateur de risque pour projets health-tech
9 classificateurs gradient-boosted (scikit-learn) sur 3 dimensions de risque (réglementaire/vie privée, sécurité patient, PI/financier) · suite de tests complète · CI · desktop (Tkinter) + web (Streamlit)
Précision moyenne 72,2 % vs 43,5 % (baseline classe majoritaire) sur données synthétiques, limites documentées dans le model card
**[Démo en ligne](https://confidentialitylevelpred-zz75da.streamlit.app/)**

**[elec_prediction](https://github.com/zz75da/elec_prediction)** — Prévision de consommation électrique multi-pays
FastAPI (train-api/predict-api) · DVC · MLflow · Prometheus/Grafana
7 pays (France, USA, Allemagne, Autriche, Luxembourg, UK, Finlande) — LightGBM poolé, MAPE 1,93%

**[car_procurement](https://github.com/zz75da/car_procurement)** — Analytics achats & détection d'anomalies (Renault)
Isolation Forest (anomalies de coût) + CatBoost (conformité fournisseurs, class-imbalance corrigée)
J'ai débusqué un piège de classifieur nul (rappel de 0 % masqué par une accuracy de 89 %), puis appliqué la méthodologie d'évaluation correcte (pondération de classes équilibrée, F1-macro, ROC-AUC, validation croisée à 5 plis) pour révéler que le signal n'était en réalité pas présent.

**[sales-analysis](https://github.com/zz75da/sales-analysis)** — Analytics client e-commerce
RFM, CLV (BG/NBD + XGBoost), prédiction de churn, A/B testing corrigé

<img src="https://raw.githubusercontent.com/zz75da/sales-analysis/main/rfm_visualisations.png" width="49%"> <img src="https://raw.githubusercontent.com/zz75da/sales-analysis/main/clv_tiers.png" width="49%">

---

#### Stack technique

![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/-FastAPI-009688?logo=fastapi&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?logo=docker&logoColor=white)
![Airflow](https://img.shields.io/badge/-Airflow-017CEE?logo=apacheairflow&logoColor=white)
![MLflow](https://img.shields.io/badge/-MLflow-0194E2?logo=mlflow&logoColor=white)
![DVC](https://img.shields.io/badge/-DVC-13ADC7?logo=dvc&logoColor=white)
![Kubernetes](https://img.shields.io/badge/-Kubernetes-326CE5?logo=kubernetes&logoColor=white)
![Prometheus](https://img.shields.io/badge/-Prometheus-E6522C?logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/-Grafana-F46800?logo=grafana&logoColor=white)
![GCP](https://img.shields.io/badge/-GCP-4285F4?logo=googlecloud&logoColor=white)
![Looker](https://img.shields.io/badge/-Looker-4285F4?logo=looker&logoColor=white)
![scikit--learn](https://img.shields.io/badge/-scikit--learn-F7931E?logo=scikitlearn&logoColor=white)

Plus d'information sur mon [LinkedIn](https://www.linkedin.com/in/zzeghoud).
