# Créer le fichier README.md avec du contenu initial
echo "# Mon Premier Projet Git" > README.md
# Ajouter le fichier à la staging area
git add README.md
# Effectuer le premier commit
git commit -m "init: création du fichier README.md avec le titre du
projet"

# Modifier le README.md (ajout d'une description)
echo "Ce projet est un exercice d'initiation à Git." >> README.md
git add README.md
git commit -m "docs: ajout de la description du projet dans README.md"

# Modifier à nouveau le README.md (ajout d'informations d'auteur)
echo "Auteur : SOBZE MAFFO | Date : 2026" >> README.md
git add README.md
git commit -m "docs: ajout des informations d'auteur et de date"

#Ajout de la page d'acceuil
#Fusion des branches(main et feature/home)
