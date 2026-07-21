**Data Scientist** | **Mathématicien Appliqué** | **Chercheur en Machine Learning**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Edmond_Fossi-blue?style=flat&logo=linkedin)](https://www.linkedin.com/in/edmond-fossi-891829324)
[![Email](https://img.shields.io/badge/Email-fossiedmond8%40gmail.com-red?style=flat&logo=gmail)](mailto:fossiedmond8@gmail.com)
[![WhatsApp 1](https://img.shields.io/badge/WhatsApp-+237_651158280-green?style=flat&logo=whatsapp)](https://wa.me/237651158280)
[![WhatsApp 2](https://img.shields.io/badge/WhatsApp-+237_657287654-green?style=flat&logo=whatsapp)](https://wa.me/237657287654)

---

## 🎯 Aperçu du Profil

**Data Scientist** passionné avec une solide formation en **Mathématiques Pures & Appliquées**. Je fais le pont entre la modélisation mathématique rigoureuse, l'apprentissage statistique avancé et la prise de décision stratégique.

Spécialisé en modélisation mathématique et Data Science, avec un focus sur les GLM, les PINNs et l'analyse spatio-temporelle appliqués aux enjeux de la **Santé Publique et de l'Environnement**.

---

## 🛠️ Compétences Clés & Stack Technique

### **Modélisation Statistique & Machine Learning**
* **Modèles Linéaires Généralisés (GLM) :** Régression Logistique, Régression de Poisson & Binomiale Négative, Régression Gamma (lien Log), Optimisation MCO
* **Apprentissage Automatique Paramétrique & Non-Paramétrique :** Classification, Régression, Sélection de variables (AIC/BIC), Estimation de paramètres
* **Machine Learning Informé par la Physique :** Réseaux de Neurones Informés par la Physique (PINNs), Équations Différentielles (EDO/EDP), Modèles Compartimentaux SIR/SEIR

### **Ingénierie des Données & Analytics**
* **Traitement & Manipulation de Données :** Pandas, NumPy, SciPy, Statsmodels
* **Frameworks de Deep Learning :** PyTorch
* **Analyse de Données Spatiales & de Comptage :** Diagnostic de surdispersion, Modélisation de taux (intégration d'offset), Analyse géospatiale

### **Aide à la Décision & Déploiement**
* **Analyse en Santé Publique :** Stratification des risques, Allocation des ressources, Stratégies de contrôle des épidémies
* **Outils & Environnement :** Python, Git/GitHub, LaTeX, Jupyter

---

## 🔬 Projets Phares & Études de Cas

### 🦟 Stratégie de Lutte Antivectorielle du Paludisme & Ciblage Géospatial
> **Contexte & Recherche :** La prévalence du paludisme dans les régions tropicales varie considérablement selon l'altitude et les microclimats. L'objectif était d'identifier les facteurs environnementaux clés afin d'optimiser des ressources limitées (MILD, pulvérisation intradomiciliaire).
* **Approche de Modélisation :** Traitement de la distribution non-normale de la densité parasitaire en évaluant les hypothèses de Gauss-Markov, suivi d'une sélection de variables via le **critère AIC** pour capturer les prédicteurs environnementaux significatifs et les seuils d'altitude.
* **Impact Décisionnel :** Rédaction d'une note stratégique à l'attention des autorités sanitaires pour la priorisation géographique basée sur des seuils d'altitude prédictifs.
* **Tech :** `Python`, `Statsmodels`, `MCO / GLM`, `Optimisation AIC`

🔗 [Consulter le projet](https://duplexfossi.github.io/Malaria/)

---

### 💧 Contrôle d'Épidémie de Choléra & Analyse des Facteurs Comportementaux
> **Contexte & Recherche :** Une réponse rapide lors d'une épidémie de choléra nécessite d'évaluer l'efficacité relative des infrastructures (accès à l'eau potable) par rapport aux facteurs comportementaux (savon / éducation à l'hygiène) sous contraintes budgétaires.
* **Approche de Modélisation :** Utilisation de la **Régression Logistique (Logit)** pour estimer les probabilités d'infection et calculer les **Odds Ratios (OR)** afin de comparer les facteurs de risque.
* **Impact Décisionnel :** Arbitrage coût-efficacité pour guider les investissements en santé publique entre la réparation des forages et la distribution de kits d'hygiène.
* **Tech :** `Python`, `Régression Logistique`, `Analyse par Odds Ratio`, `Modélisation des risques`

🔗 [Consulter le projet](https://github.com/Duplexfossi/NOM_DU_REPO_CHOLERA)

---

### 🫁 Système d'Alerte Précoce pour Infections Respiratoires Aiguës Basses (IRAB)
> **Contexte & Recherche :** Différencier les véritables flambées épidémiques liées à la pollution atmosphérique de la croissance démographique de base à travers des districts de santé hétérogènes.
* **Approche de Modélisation :** Mise en œuvre de modèles de **régression de Poisson et Binomiale Négative** intégrant des **offsets de population** pour modéliser les taux d'incidence. Diagnostic de la surdispersion pour sélectionner le modèle de comptage optimal et détecter les excès de risque spatiaux.
* **Impact Décisionnel :** Établissement d'une métrique de détection d'anomalies pour identifier les "districts atypiques" nécessitant une investigation épidémiologique de terrain urgente.
* **Tech :** `Python`, `GLM Poisson / Binomiale Négative`, `Diagnostic de surdispersion`, `Modélisation de taux`

🔗 [Voir le dépôt GitHub](https://github.com/Duplexfossi/NOM_DU_REPO_ALRI)

---

### 🏥 Optimisation de la Capacité Hospitalière & Prédiction de la Durée de Séjour
> **Contexte & Recherche :** Prévenir la saturation des hôpitaux lors des pics épidémiques en prédisant avec précision la durée de séjour des patients en fonction de l'âge et des comorbidités.
* **Approche de Modélisation :** Formulation d'un **modèle de Régression Gamma avec une fonction de lien Log**, particulièrement adapté aux données de durée continues, positives et asymétriques.
* **Impact Décisionnel :** Prédiction du taux d'occupation moyen des lits pour les profils démographiques à haut risque et développement d'une stratégie de priorisation des flux pour la gestion de crise.
* **Tech :** `Python`, `GLM Gamma (Lien Log)`, `Analyse prédictive`, `Optimisation des ressources`

🔗 [Voir le dépôt GitHub](https://github.com/Duplexfossi/NOM_DU_REPO_HOSPITAL_LOS)
