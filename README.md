# Application de Gestion des Épreuves Scolaires

## Description
Ce projet vise à créer une application web pour la **reconnaissance**, **classification** et **génération** d'épreuves scolaires.  
L'application permettra de :  
- **Scanner** des épreuves papier et de les convertir en fichiers numériques.  
- **Reconnaître** le texte des épreuves scannées grâce à une technologie OCR.  
- **Classifier** les épreuves par niveau, matière et type d'évaluation.  
- **Générer** de nouvelles épreuves basées sur des modèles existants.  

**Technologies utilisées** :  
- **Frontend** : Angular 17 (interface utilisateur moderne et réactive).  
- **Backend** : Python (dernière version) avec Flask ou Django (pour le traitement des données et l'API).  
- **Base de données** : PostgreSQL ou MongoDB (pour stocker les épreuves et les métadonnées).  
- **OCR** : Tesseract ou Google Vision API (pour la reconnaissance de texte).  
- **Machine Learning** : TensorFlow ou scikit-learn (pour la classification des épreuves).  

---

## Fonctionnalités
- **Scan d'épreuves** : Numérisation des épreuves papier via une interface intuitive.  
- **Reconnaissance de texte (OCR)** : Extraction du texte des épreuves scannées.  
- **Classification automatique** : Classement des épreuves par niveau, matière et type d'évaluation.  
- **Génération d'épreuves** : Création de nouvelles épreuves basées sur des modèles existants.  
- **Interface utilisateur** : Une interface conviviale pour les enseignants et les administrateurs.  

---

## Installation et Configuration

### Prérequis
Avant de commencer, assurez-vous d'avoir installé les outils suivants :  
- **Node.js** (pour Angular) : [Télécharger Node.js](https://nodejs.org)  
- **Python** (dernière version) : [Télécharger Python](https://python.org)  
- **Git** (pour la gestion de version) : [Télécharger Git](https://git-scm.com)

  
### Frontend (Angular 17)
1. **Installez Angular CLI** :  
   Pour installer Angular CLI globalement avec la version 17, utilisez la commande suivante :  
   ```bash
   npm install -g @angular/cli@17
