# Fossi Deffo Edmond Duplex 👋
### Data Scientist & Mathématicien | Spécialiste Modélisation Santé & Épidémiologie

Actuellement en **Master 2 Data Science et Ingénierie Mathématique à l’Université de Dschang**, je combine la rigueur des **mathématiques appliquées** (équations différentielles, statistiques) avec la puissance du **Machine Learning** et du **Deep Learning** pour répondre aux enjeux stratégiques de la santé publique et de l'environnement.

---

## 🛠️ Stack Technique

* **Langages & Outils :** Python (`PyTorch`, `Scikit-Learn`, `Statsmodels`, `Pandas`, `NumPy`), R, SQL, Jupyter
* **Modélisation Santé & Épidémiologie :** PINNs (Physics-Informed Neural Networks), Modèles compartimentaux (SIR / SEIR), Régression Binomiale Négative, Modèles d'infections respiratoires & vectorielles
* **Séries Temporelles & Statistiques :** SARIMA, Tests de stationnarité, Feature Engineering, Optimisation d'hyperparamètres

---

## 🔬 Projets Concrets en Santé & Publications LinkedIn

### 1. 🫁 [Pollution Atmosphérique et Infections Respiratoires Aiguës](https://github.com/votre-user/Air-Pollution-Respiratory-Infections)
> 📲 *Projet présenté dans un post LinkedIn sur la cartographie et l'analyse de données de santé publique.*

* **Code & Fichiers :** `respiratory_infections_analysis.ipynb`, `negative_binomial_model.py`
* **Contexte & Objectif :** Évaluation de l'impact des polluants atmosphériques (PM2.5, NO2) sur l'incidence des infections respiratoires aiguës afin d'identifier les districts sanitaires prioritaires.
* **Méthodologie & Code :**
  * Prétraitement et agrégation spatio-temporelle de données épidémiologiques et environnementales.
  * Modélisation par **Régression Binomiale Négative** pour gérer la surdispersion des données de comptage médical.
  * Identification des facteurs de risque majeurs et calcul des ratios d'incidence (IRR).
* **Technologies :** `Python`, `Statsmodels`, `Pandas`, `Seaborn`, `Matplotlib`

---

### 2. 🦠 [PINNs & Modèle Épidémiologique SIR (Physics-Informed Neural Networks)](https://github.com/votre-user/PINN-Epidemiology-SIR)
> 📲 *Projet présenté dans le cadre d'une série LinkedIn sur l'intégration des contraintes physiques et mathématiques dans le Deep Learning.*

* **Code & Fichiers :** `pinn_sir_solver.py`, `train_pinn_epidemiology.ipynb`
* **Contexte & Objectif :** Simulation de la dynamique de propagation des maladies transmissibles (ex. paludisme, choléra) en résolvant le système d'équations différentielles du modèle SIR ($\dot{S}, \dot{I}, \dot{R}$) via des réseaux de neurones.
* **Méthodologie & Code :**
  * Construction d'une architecture PyTorch incorporant les dérivées du modèle SIR directement dans la fonction de perte (`Custom Loss`).
  * Estimation simultanée de la trajectoire épidémique et ajustement automatique des paramètres de transmission ($\beta$) et de guérison ($\gamma$).
* **Technologies :** `Python`, `PyTorch`, `SciPy (odeint)`, `NumPy`

---

### 3. 📊 [Sprint Épidémiologique : Optimisation Multi-Modèles & Modélisation Spatio-Temporelle](https://github.com/votre-user/Epidemiological-Model-Optimization)
> 📲 *Projet documenté au cours d'un sprint de recherche et partagé en série de posts sur le workflow d'un Data Scientist.*

* **Code & Fichiers :** `pipeline_optimization.py`, `spatial_epidemic_eval.ipynb`
* **Contexte & Objectif :** Traitement et benchmark de modèles de machine learning appliqués à un jeu de données épidémiologiques ouvertes pour anticiper les pics d'infection.
* **Méthodologie & Code :**
  * Pipeline complet d'ingénierie des variables (Feature Engineering spatio-temporel, fenêtres glissantes).
  * Benchmark comparatif : Régression Régularisée (Lasso/Ridge), Random Forest et Gradient Boosting.
  * Évaluation sur métriques métiers et sanitaires ($RMSE$, $MAE$, $R^2$) avec validation croisée chronologique.
* **Technologies :** `Python`, `Scikit-Learn`, `Pandas`

---

### 4. 🌤️ [Modélisation Climatique & Santé (Séries Temporelles SARIMA)](https://github.com/votre-user/Climate-Health-SARIMA-Douala)
> 📲 *Projet axé sur la prédiction des risques environnementaux et vectoriels en Afrique centrale.*

* **Code & Fichiers :** `climate_health_forecasting.py`, `stationarity_tests.py`
* **Contexte & Objectif :** Modélisation prédictive des données climatiques (températures, précipitations à Douala) pour anticiper les périodes à risque pour les maladies vectorielles.
* **Méthodologie & Code :**
  * Décomposition saisonnière, tests de stationnarité (ADF) et différenciation des séries.
  * Ajustement et sélection du modèle optimal **SARIMA** via minimisation des critères $AIC$/$BIC$.
* **Technologies :** `Python`, `Statsmodels`, `Matplotlib`, `R`

---

## 📑 Séries Éducatives & Posts Techniques LinkedIn

* 🚴‍♂️ **[Les 9 Roues de l'Apprentissage Statistique](https://github.com/votre-user/9-Roues-Apprentissage-Statistique)** : Série de posts détaillant les piliers fondamentaux des systèmes d'apprentissage (de la théorie du risque empirique aux choix d'architectures).
* 💼 **[Data Science B2B & ROI des Modèles ML](https://github.com/votre-user/ML-Business-Metrics-Series)** : Série sur 10 jours axée sur la traduction des performances techniques ($AUC-ROC$, $Recall$) en impact métier et aide à la décision.

---

## 📫 Me Contacter & Suivre mes Travaux

* **LinkedIn :** [Fossi Deffo Edmond Duplex](https://www.linkedin.com/in/votre-profil)
* **Email :** [fossiedmond8@gmail.com](mailto:fossiedmond8@gmail.com)
* **Localisation :** Dschang, Cameroun
