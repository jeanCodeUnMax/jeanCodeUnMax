# testwebdev

…or create a new repository on the command line
echo "# testwebdev" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:w3bdev5/testwebdev.git
git push -u origin main


…or push an existing repository from the command line


git remote add origin git@github.com:w3bdev5/testwebdev.git
git branch -M main
git push -u origin main

installation reussit avec:

 # erreur# git clone origine =>  git@github.com:w3bdev5/testwebdev.git
 la cle ssh contien lidentite et la premiere clef rsa a le host github.com !



fonctionne  avec :

git clone origine =>  git@github.com_team:w3bdev5/testwebdev.git

la cle ssh contien l identite de la deuxieme clef rsa qui se trouve sur le host  github.com_team

info le fichier config se trouve dans le rep .ssh
le fichier gitconfig  contien des identifiants  mais ne changera rien au autorisation 
(pour le moment je pense que c'est peut etre utile pour pouvoir creer a partir de rien et non cloner depuis github )



