# 📈 SAE S3 — Modélisation de séries temporelles (VCOD)

![Formation](https://img.shields.io/badge/BUT-VCOD-blue)
![Semestre](https://img.shields.io/badge/Semestre-3-green)
![R](https://img.shields.io/badge/R-276DC3?logo=r&logoColor=white)
![Excel](https://img.shields.io/badge/Excel-217346?logo=microsoftexcel&logoColor=white)

**Auteur** : Alexan RAVONNEAUX | **IUT de Niort** – Université de Poitiers | **S3 VCOD (2025-2026)**

---

## 📋 Description

Modélisation et prévision de séries temporelles sur des données économiques réelles (cours Air France et inflation). Ce projet décompose les séries (tendance, saisonnalité, résidus), ajuste des modèles ARIMA et réalise des prévisions à court terme avec intervalles de confiance.

## 🎯 Objectifs pédagogiques
- Décomposer une série temporelle (tendance, saisonnalité, résidus)
- Tester la stationnarité (test ADF, différenciation)
- Identifier et ajuster un modèle ARIMA (p,d,q)
- Réaliser des prévisions et valider le modèle

## 🔧 Technologies

| Outil | Rôle |
|-------|------|
| R (forecast, tseries) | Modélisation ARIMA et prévisions |
| Excel | Exploration initiale et visualisation |
| ggplot2 | Graphiques des séries et prévisions |

## 📂 Structure

`
SAE3_Series_Temporelles/
├── README.md
├── projet.xlsx          # Données et analyses Excel
├── Air_France.xlsx      # Cours boursiers Air France
├── Inflation.xlsx       # Données d'inflation
└── analyse_R/           # Scripts R (si présents)
`

## 📊 Résultats
- Décomposition STL des séries étudiées
- Modèle ARIMA sélectionné par critère AIC/BIC
- Prévisions à 3-6 mois avec intervalles de confiance 95%
