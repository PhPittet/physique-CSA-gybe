# Physique-CSA-gybe
Repo pour le cours de Physique des élèves de CSA

1. Création du site modulo-gybe (sur githubpages)
2. mettre à jour le repo avec les modifs
3. mettre à jour la table des matières (_toc.yml)
4. `git commit -m "blabla"`
5. `git push`
6. construire le jupyter book localement (cela prend du temps) : `jupyter-book  build .` depuis la racine
7. vérifier localement qu'il est correct `_build/html/index.html`
8. uploader le résultat depuis le dossier local sur ghpages: `ghp-import -n -p -f _build/html`
9. attendre 5 minutes et vérifier le résultat
9. détruire le répertoire complet `rm -Rf _build`
