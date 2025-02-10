# 🚀 Projet Symfony - API

## 📖 Description
API, qui reçoit le pays au format fr/en/us et renvoie le drapeau sous forme de lien

## ⚙️ Installation

**1. Clonez le dépôt 🛠️**
   ```bash
   git clone https://github.com/FoodBoxOrg/API
   cd API
   ```

**2. Installation des dépendances 📦**
   ```bash
   composer install
   ```

**3. Exécuter les migrations de base de données 🗄️**
   ```bash
   php bin/console doctrine:migrations:migrate
   ```

**4. Charger les données de test 🗂️**
   ```bash
   php bin/console doctrine:fixtures:load
   ```
⚠️ Attention : Cette commande réinitialisera les données existantes en base !

**5. Démarrez le serveur 🚀** 
   ```bash
   symfony serve
   ```

   L'API sera disponible à l'adresse [http://localhost:8000/api](http://localhost:8000/api).
