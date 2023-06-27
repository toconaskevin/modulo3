# Ejercicio 1
## Pasos a seguir para cumplir el objetivo del ejercicio:
- git add .
- git stash save "Staging changes to fix an incident"
- git checkout master
- git checkout -b "fix/incident"
- git rm status.js
- git commit -m "Remove status.js"
- git push

Abrir Pull Request a master

- git checkout custom-navbar
- git stash apply "Stag.." ó git stash pop "Stag..."