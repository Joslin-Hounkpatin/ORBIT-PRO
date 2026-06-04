## Orbit PRO - Project Intelligence Engine



**Pilotage Financier, Reporting \& Intelligence Artificielle.**



**Orbit PRO** est une application web de gestion de projet de type SaaS moderne, conçue pour transformer des données froides en décisions stratégiques. Contrairement aux outils classiques, Orbit se concentre sur la corrélation dynamique entre la **santé financière**, l'**avancement réel** et le **temps écoulé**, désormais boostée par l'**Intelligence Artificielle**.



##### &#x20;**Pourquoi Orbit PRO ?**



Le plus grand risque d'un projet est de consommer son budget plus vite que le temps ne s'écoule. Orbit PRO résout ce problème grâce à un tableau de bord prédictif et une couche d'intelligence artificielle qui analyse les dérives avant qu'elles ne deviennent critiques.



##### &#x20;**Fonctionnalités Clés**



###### 1\.  **Intelligence Artificielle (Google Gemini)**



* **Orbit AI Consultant** : Un audit de risque narratif qui analyse votre portefeuille et génère des conseils stratégiques en langage naturel.



* **Planificateur Assisté (Smart Setup)** : Créez des projets complexes via une simple phrase. Tapez "*Villa R+1 de 50M en 8 mois*" et l'IA configure automatiquement les dates, le budget et suggère les tâches clés.



###### 2\.  **Pilotage Hybride (Double Saisie)**



* **Mode Manuel** : Saisie ultra-rapide pour un suivi macro.
* **Mode Granulaire** (Tâches) : Bascule automatique vers un moteur de calcul mathématique dès l'ajout de tâches (Σ budgets, Σ dépenses).



###### 3\.  **Algorithme de Score de Santé (EVM Logic)**



Calcul dynamique du statut (**Sain, Vigilance, Critique**) basé sur la méthode de la valeur acquise :



* Comparaison entre l'avancement réel et le "Time Burn Rate".
* Détection immédiate des dépassements budgétaires.



###### 4\.  **Visualisation \& Reporting**



* **Bento Grid UI** : Interface sombre, élégante et ultra-réactive.
* **Performance Chart** : Graphiques ApexCharts comparant les courbes de progression vs temps.
* **Export Professionnel** : Génération de rapports Excel (Data) et PDF Haute Définition (Présentation client).



##### &#x20;**Stack Technique**



* **UI/UX** : HTML5, CSS3 (Bento Grid, Animations fluides).
* **Design System** : Bootstrap 5 + Lucide Icons + Bootstrap Icons.
* **Moteur IA** : Google Gemini API (v1 / v1beta).
* **Logique** : Vanilla JavaScript (ES6+ Class-based).
* **Visualisation** : ApexCharts.
* **Exports** : SheetJS (XLSX) \& html2pdf.js.



##### &#x20;**Installation Rapide (Open Source)**



Ce projet est **100% Client-Side.** Aucune base de données ou serveur n'est requis.

1. **Cloner le dépôt** :



&#x20; <> Bash

&#x20;

&#x20; git clone https://github.com/Joslin-Hounkpatin/orbit-pm.git



2\. **Lancer l'app** : Ouvrez simplement index.html dans votre navigateur.



3\. **Configurer l'IA** :



&#x20;  a- Obtenez une clé gratuite sur Google AI Studio.

&#x20;  b- Cliquez sur l'icône ⚙️ (Paramètres) dans Orbit PRO et collez votre clé.



##### &#x20;**Logique de Calcul**



Orbit PRO utilise une hiérarchie stricte pour garantir l'intégrité des données :



1. **Si Tâches présentes :**



&#x20;  **a- Budget Total = Sum(Budgets Tâches)**

&#x20;  **b- Avancement = Moyenne Pondérée (Avancement \* Budget)**

&#x20;

2\. **Statut Critique** : Déclenché si **Budget Consommé > Budget Prévu** OU si **% Avancement < % Temps écoulé - 15%.**



##### &#x20;**Confidentialité \& Sécurité**





Orbit PRO adopte une approche **Privacy-First :**



* **Zéro Serveur** : Vos données financières ne quittent jamais votre machine.
* **Stockage Local** : Utilisation exclusive du LocalStorage de votre navigateur.
* **Clé API Sécurisée** : Votre clé Google Gemini est stockée localement et n'est jamais codée en dur dans le script.



##### 🤝 **Contribution**



Le projet est ouvert à tous !



1. Forkez le projet.

2\. Créez votre branche (git checkout -b feature/AmazingFeature).

3\. Commitez vos changements (git commit -m 'Add AmazingFeature').

4\. Ouvrez une Pull Request.



⚖️ Licence



Distribué sous la licence MIT. Voir **LICENSE** pour plus d'informations.



**Développé avec passion pour simplifier le pilotage de projet complexe.**



