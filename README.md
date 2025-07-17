
# 💬 Application ChatBot avec Flutter & API ChatGPT

Une application mobile développée avec Flutter, intégrant un assistant conversationnel intelligent grâce à l’API ChatGPT d’OpenAI.

---

## 🚀 Fonctionnalités

- Interface utilisateur responsive et moderne
- Communication en temps réel avec un chatbot intelligent
- Requêtes API via HTTP vers ChatGPT
- Gestion des erreurs et des états de chargement
- Personnalisation simple de la clé API
- Prise en charge du mode clair/sombre

---

## 🛠️ Technologies utilisées

- **Flutter** / **Dart**
- **API OpenAI (ChatGPT)**
- `http` – pour les requêtes réseau
- `provider` ou `bloc` – pour la gestion d'état (optionnel selon ton choix)
- `flutter_dotenv` – pour la configuration sécurisée des clés

---

## 🔧 Configuration

1. Installer les dépendances :
   ```bash
   flutter pub get
   ```

2. Ajouter votre clé API OpenAI :

   Créer un fichier `.env` à la racine du projet :

   ```env
   OPENAI_API_KEY=sk-xxxxxxxxxxxxxxxxxxxxxxxxxxxx
   ```

3. Exécuter l'application :
   ```bash
   flutter run
   ```

---

## 🤝 Contributions

Les contributions sont bienvenues !  
N'hésitez pas à proposer des améliorations, signaler des bugs ou soumettre une pull request.
```
