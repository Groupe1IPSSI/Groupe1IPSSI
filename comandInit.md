---
title: Installation projet
category: Git
---


## Initialiser un projet

```shell
$ echo "# monprojet" >> readmeGR1.md
$ git init
Reinitialized existing Git repository in /home/brigitte/projetGit/.git/
$ git add readmeGR1.md
$ git commit -m "tapez votre commentaire ici"
 1 file changed, 1 insertion(+)
$ git fetch
$ git remote add origin https://github.com/Username/repo.git/
$ git remote show origin
$ git push --set-upstream origin
FETCH_HEAD    HEAD          main          origin/main
to generate token for connexion: https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/creating-a-personal-access-token#using-a-token-on-the-command-line
$ git push --set-upstream origin main
Username: your_username
Password: your_token
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 300 bytes | 300.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0)
To https://github.com/Username/repo.git/
   79dd5a9..427ad42  main -> main
Branch 'main' set up to track remote branch 'main' from 'origin'.
```
