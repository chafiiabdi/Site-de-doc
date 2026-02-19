git init

🎯 Rôle

Initialiser un dépôt Git dans le dossier courant.
📌 Ce que ça fait

    Crée un dossier caché .git

    Active le suivi de version

    Crée la branche par défaut (master ou main)

2️⃣ Vérifier l’état du projet

git status

🎯 Rôle

Afficher l’état actuel du dépôt.
📌 Affiche

    Les fichiers modifiés

    Les fichiers non suivis (untracked)

    Les fichiers prêts à être commit (staged)

3️⃣ Ajouter des fichiers à la zone de préparation

git add *

ou

git add .

🎯 Rôle

Ajouter les fichiers à la staging area.
🧠 Cycle Git

Working Directory → Staging Area → Commit

4️⃣ Créer un commit

git commit -m "premier commit"

🎯 Rôle

Enregistrer officiellement les modifications dans l’historique.
📌 -m

Permet d’ajouter un message descriptif.
5️⃣ Configurer l’identité Git

git config --global user.name "TonNom"
git config --global user.email "tonemail@example.com"

🎯 Rôle

Définir l’auteur des commits.
📌 Pourquoi ?

Chaque commit doit contenir :

    Un nom

    Un email

6️⃣ Commit rapide des fichiers modifiés

git commit -a -m "modification"

🎯 Rôle

Commit directement les fichiers déjà suivis et modifiés.
⚠️ Important

Ne fonctionne pas pour les nouveaux fichiers non suivis.
🔁 Processus complet
🚀 Premier commit

git init
git add .
git commit -m "Premier commit"

🔄 Après modification d’un fichier

git add fichier.md
git commit -m "Modification"

Ou plus rapide :

git commit -a -m "Modification"
