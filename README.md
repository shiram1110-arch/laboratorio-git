# laboratorio-git
laboratorio dos

git config --global user.name Shirley
git config --global user.email [shiram1110@gmail.com](mailto:shiram1110@gmail.com)

git init
git branch -m main

git add .
git commit -m "Estructura inicial del proyecto"

git log

git branch desarrollo
git switch desarrollo

git add .
git commit -m "Agrega contenido en index"

git switch main
git merge desarrollo

git diff

git add .
git commit -m "Cambio temporal"

git reset --hard HEAD~1

git reflog

git reset --hard HEAD@{1}

git reset --hard d4e5f6g

git reflog

git reset --hard c9472ad

git add .
git commit -m "Agrega gitignore"

git remote add origin https://github.com/shiram1110-arch/laboratorio-git.git

git push -u origin main

git pull origin main --rebase

git push -u origin main

git branch login
git switch login

git add .
git commit -m "Agrega login"

git push -u origin login

