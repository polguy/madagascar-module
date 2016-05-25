# madagascar-module

echo "# madagascar-module" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add custom-module https://github.com/polguy/madagascar-module.git
git push -u custom-module master

# NOTE : custom-module remplace origin (origin est vu dans tous les exemples de codes)


# PUSH
User : polguy
Password : dV***Y***

# Récupérer sur le serveur prod le nouveau code envoyé depuis le local :
Pour le repo dans G:\wamp\www\chauffeur-madagascar\modules\custom, correspondant au repo sur Github madagascar-module.git
Se positionner où est le dossier .git, dans subsites/madagascar/modules/custom
git clone https://github.com/polguy/madagascar-module.git
