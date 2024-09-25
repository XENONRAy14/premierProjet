J'ai créé un nouveau projet avec `mkdir projet-entreprise` et `git init`. J'ai ajouté `index.html`, `style.css`, et `about.html`, puis j'ai validé chaque fichier avec `git add` et `git commit`.

J'ai consulté l'historique avec `git log --oneline`, comparé les versions avec `git diff`, et utilisé `git checkout HEAD~1` pour revenir à une version précédente.

J'ai ajouté un lien dans `index.html`, modifié `style.css`, et validé ces changements. Pour annuler le changement de couleur dans `style.css`, j'ai utilisé `git restore`.

J'ai modifié `about.html`, validé les changements, et fusionné les derniers commits avec `git rebase -i HEAD~2`.

J'ai créé un fichier `.gitignore` pour ignorer les fichiers `.log` et le dossier `temp/`, puis je l'ai validé.

Enfin, j'ai vérifié l'historique des commits avec `git log --oneline` et le statut du dépôt avec `git status`.