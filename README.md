<div align="center">

# Komhidi Jean Jacques

### Développeur & Analyste de Données | Master 2 UCAO Dakar

[![GitHub](https://img.shields.io/badge/GitHub-jean--jacques--komhidi-181717?style=flat&logo=github)](https://github.com/jean-jacques-komhidi)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-komhidi--jean--jacques-0A66C2?style=flat&logo=linkedin)](https://www.linkedin.com/in/komhidi-jean-jacques-a13842280)
[![Email](https://img.shields.io/badge/Email-jkomhidi2002@gmail.com-EA4335?style=flat&logo=gmail)](mailto:jkomhidi2002@gmail.com)
[![Location](https://img.shields.io/badge/Localisation-Dakar%2C%20Sénégal-00B96B?style=flat&logo=googlemaps)](https://maps.google.com/?q=Dakar,Senegal)

*"Programmation it's life"*

</div>

---

## À propos de moi

Étudiant en **Master Informatique de Gestion** (option Développement et Analyse de Données) à l'UCAO Dakar, avec une double compétence en **développement logiciel** et **analyse de données**.

Passionné par les projets data-driven, je maîtrise l'ensemble du cycle ML : collecte, nettoyage, modélisation, déploiement et monitoring. Également spécialisé en développement fullstack (Django, FastAPI, React) et en Business Intelligence.

Expérience pratique sur des projets réels : pipeline MLOps complet, ERP Django, système d'approvisionnement, dashboard Power BI PMO, et déploiement Odoo chez des clients.

---

## Projets phares

### Score Crédit MLOps
> Pipeline MLOps complet de scoring crédit — Master 2 UCAO

[![Repo](https://img.shields.io/badge/GitHub-score--credit--mlops-181717?style=flat&logo=github)](https://github.com/jean-jacques-komhidi/score-credit-mlops)
[![CI/CD](https://github.com/jean-jacques-komhidi/score-credit-mlops/actions/workflows/ci.yml/badge.svg)](https://github.com/jean-jacques-komhidi/score-credit-mlops/actions/workflows/ci.yml)
![Python](https://img.shields.io/badge/Python-3.11-3776AB?style=flat&logo=python)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi)
![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react)
![XGBoost](https://img.shields.io/badge/XGBoost-FF6600?style=flat)

Système complet de prédiction du risque de défaut de paiement sur le dataset Home Credit Default Risk (307 000 clients, 178 features).

**Fonctionnalités :**
- Modèle XGBoost (AUC-ROC : 0.7294) entraîné avec SMOTE
- Explicabilité SHAP avec visualisation animée des facteurs de décision
- Dashboard interactif avec graphiques Chart.js et animations
- Monitoring du Data Drift avec Evidently
- Pipeline CI/CD GitHub Actions
- Tracking des expériences MLFlow + PostgreSQL

**Stack :** Python · FastAPI · XGBoost · SHAP · Evidently · MLFlow · React · Tailwind · PostgreSQL

---

### ERP MEA — Système de Gestion d'Entreprise
> ERP complet pour la région Middle East & Africa — Django + Jinja2

[![Repo](https://img.shields.io/badge/GitHub-erp--mea-181717?style=flat&logo=github)](https://github.com/jean-jacques-komhidi/erp-mea)
![Stars](https://img.shields.io/github/stars/jean-jacques-komhidi/erp-mea?style=flat)
![Python](https://img.shields.io/badge/Python-Django-3776AB?style=flat&logo=python)
![Jinja](https://img.shields.io/badge/Jinja2-B41717?style=flat)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker)

Application ERP complète développée en Django avec tous les modules métier en français.

**Modules :**
- Gestion des stocks multi-entrepôts (entrées/sorties, alertes rupture)
- Ventes : workflow complet Brouillon → Confirmé → Expédié → Facturé
- Achats : commandes fournisseurs, réception marchandises
- Base clients/fournisseurs avec calcul automatique TVA
- Interface moderne avec barre latérale fixe et cartes statistiques

**Stack :** Python · Django 5.0 · Jinja2 · SQLite · Docker · CSS3

---

### UCAO Approvisionnements
> Système de gestion des approvisionnements — UCAO-ISG-CSM

[![Repo](https://img.shields.io/badge/GitHub-ucao--approvisionnements-181717?style=flat&logo=github)](https://github.com/jean-jacques-komhidi/ucao-approvisionnements)
![Python](https://img.shields.io/badge/Python-Django-3776AB?style=flat&logo=python)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql)

Application web complète de gestion du cycle d'approvisionnement à l'UCAO, de la demande (FEB) au paiement, développée en projet tutoré Master 1.

**Fonctionnalités :**
- 8 rôles utilisateurs + authentification sécurisée (blocage 5 tentatives)
- Workflow FEB complet : DRAFT → EN_INSTANCE → VALIDÉE/CLÔTURÉE/REJETÉE
- Bon de commande automatique si montant > 50 000 F CFA + génération PDF
- Circuit de paiement DFC → DG → Comptable avec acomptes partiels
- Notifications in-app + emails HTML Gmail
- Dashboard analytics avec 4 graphiques Chart.js + alertes intelligentes

**Stack :** Python · Django 4.2 · PostgreSQL · Jinja2 · WeasyPrint · Chart.js · SMTP Gmail

---

### Dashboard PMO — Pilotage des Projets IT & Marketing
> Tableau de bord Power BI interactif — 247 projets sur 4 régions

[![Repo](https://img.shields.io/badge/GitHub-Projet__Dashboard__PMO-181717?style=flat&logo=github)](https://github.com/jean-jacques-komhidi/Projet_Dashboard_PMO)
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat&logo=powerbi)
![DAX](https://img.shields.io/badge/DAX-0078D4?style=flat)
![Status](https://img.shields.io/badge/Status-Completed-success?style=flat)

Tableau de bord décisionnel Power BI pour le Project Management Office d'une entreprise internationale, permettant le suivi de 247 projets IT et Marketing à travers 4 régions géographiques.

**Fonctionnalités :**
- Carte géographique interactive (Azure Maps) avec code couleur alerte
- Détection automatique des projets en alerte (écart ≥ 15% sur coûts/délais/livrables)
- 4 pages interactives : Vue d'ensemble, Analyse détaillée, Suivi temporel, Documentation
- Diagramme de Gantt + graphique en cascade (Waterfall) des dépassements
- Filtres contextuels par région, pays, type de projet, période

**Stack :** Power BI Desktop · DAX · Power Query (M) · Azure Maps · Gantt Chart

---

## Compétences techniques

### Data & ML
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat&logo=scikit-learn)
![XGBoost](https://img.shields.io/badge/XGBoost-FF6600?style=flat)
![MLFlow](https://img.shields.io/badge/MLFlow-0194E2?style=flat&logo=mlflow)
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat&logo=powerbi)

### Développement Web & Backend
![Django](https://img.shields.io/badge/Django-092E20?style=flat&logo=django)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi)
![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat&logo=php)
![HTML](https://img.shields.io/badge/HTML%2FCSS-E34F26?style=flat&logo=html5)

### Bases de données
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat&logo=sqlite)

### ERP & Outils métier
![Odoo](https://img.shields.io/badge/Odoo-875A7B?style=flat&logo=odoo)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat&logo=github-actions)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat&logo=postman)

---

## Formation

| Diplôme | Institution | Année |
|---------|-------------|-------|
| **Master Informatique de Gestion** (en cours) — option Data | UCAO, Dakar, Sénégal | 2025 – présent |
| **Licence Génie Informatique** | IUC, N'Djamena, Tchad | 2021 – 2024 |
| **BTS Informatique** | IUC, N'Djamena, Tchad | 2021 – 2023 |
| **Baccalauréat Série D** | Lycée Saint Étienne, Tchad | 2021 |

---

## Certifications

- **Certification Scrum** — Méthodologie Agile (2025)
- **Attestation SIG** — Systèmes d'Information Géographiques (2023)

---

## Statistiques GitHub

<div align="center">

![Stats](https://github-readme-stats.vercel.app/api?username=jean-jacques-komhidi&show_icons=true&theme=default&hide_border=true)

![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=jean-jacques-komhidi&layout=compact&theme=default&hide_border=true)

</div>

---

## Langues

| Langue | Niveau |
|--------|--------|
| Français | Langue maternelle |
| Anglais | Intermédiaire (lu, écrit, parlé) |

---

## Me contacter

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/komhidi-jean-jacques-a13842280)
[![Email](https://img.shields.io/badge/jkomhidi2002@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:jkomhidi2002@gmail.com)
[![GitHub](https://img.shields.io/badge/jean--jacques--komhidi-181717?style=for-the-badge&logo=github)](https://github.com/jean-jacques-komhidi)

📞 +221 78 482 32 96 (Sénégal) · +235 62 71 17 07 (Tchad)

</div>

---

<div align="center">

*"Programmation it's life"*

</div>
