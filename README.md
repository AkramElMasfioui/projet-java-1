
[README.md](https://github.com/user-attachments/files/23430905/README.md)
# 📚 [projet-java-1](https://github.com/AkramElMasfioui/projet-java-1)
**Système de gestion de bibliothèque**

## 🧩 À propos  
Ce projet est un **système de gestion de bibliothèque en Java**.  
Il permet de gérer les **membres**, **livres**, **emprunts** et **bibliothécaires** pour faciliter l’administration d’une bibliothèque.

---

## 🚀 Fonctionnalités principales  
- 👥 Gestion des membres (ajout, modification, suppression)  
- 📘 Gestion des livres (ajout, modification, suppression, disponibilité)  
- 🔁 Gestion des emprunts (création, retour de livres)  
- 🧑‍💼 Gestion des bibliothécaires (identification, droits d’accès)  
- 💾 Sauvegarde des données dans des fichiers CSV :  
  - [`Livre.csv`](./Livre.csv)  
  - [`Membre.csv`](./Membre.csv)  
  - [`Emprunt.csv`](./Emprunt.csv)  
  - [`Bibliothecaire.csv`](./Bibliothecaire.csv)

---

## 🗂️ Structure du projet  
```
projet-java-1/
├── src/                 # Code source Java
├── out/                 # Dossier de compilation (optionnel)
├── Livre.csv
├── Membre.csv
├── Emprunt.csv
├── Bibliothecaire.csv
└── README.md
```

---

## ⚙️ Prérequis  
- ☕ **Java JDK 8+**  
- 🧠 **IDE Java** (IntelliJ IDEA, Eclipse, NetBeans) ou terminal  
- 📂 Fichiers CSV accessibles dans le répertoire du projet

---

## 🏗️ Installation & exécution  
1. **Cloner le dépôt :**  
   ```bash
   git clone https://github.com/AkramElMasfioui/projet-java-1.git
   cd projet-java-1
   ```
2. **Compiler et exécuter :**  
   ```bash
   javac -d out src/**/*.java
   java -cp out com.nomdupackage.Main
   ```
3. **Vérifier les fichiers CSV** : ils doivent exister ou être créés au premier lancement.  

---

## 🧭 Utilisation  
- ➕ Ajouter un membre : saisir nom, prénom, âge, région, catégorie  
- 📖 Ajouter un livre : saisir titre, auteur, ISBN, disponibilité  
- 🔄 Créer un emprunt : choisir membre et livre, définir date d’emprunt  
- ✅ Retourner un livre : marquer l’emprunt comme terminé  
- 🗑️ Modifier ou supprimer selon les droits bibliothécaire  

---

## 🧱 Architecture & design  
- Programmation orientée objet : classes `Livre`, `Membre`, `Emprunt`, `Bibliothecaire`  
- Utilisation des **collections Java** (`List`, `Map`)  
- **Persistance simple** via fichiers CSV  
- Organisation en packages (`model`, `service`, `ui`, etc.)

---

## 🤝 Contributions  
Les contributions sont les bienvenues !  
1. Forkez le dépôt  
2. Créez une nouvelle branche  
3. Proposez une **Pull Request**  
4. Décrivez clairement vos changements  

🔗 [Créer une Pull Request](https://github.com/AkramElMasfioui/projet-java-1/pulls)

---

## 📜 Licence  
Ce projet est libre d’utilisation.  
➡️ [Voir le dépôt GitHub](https://github.com/AkramElMasfioui/projet-java-1)
