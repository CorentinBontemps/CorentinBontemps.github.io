CorentinBontemps.github.io
==========================


///////////////// Fichier de procédure \\\\\\\\\\\\\\\\\\\\


//////// VIRTUALBOX CONFIGURATION \\\\\\\\\\

	Lancer la machine virtuel « VirtualBox »
	Dans le menu démarrer, lancer l'émulateur de Terminal.


// Lancer Apache :
	
	sudo service apache2 start

// Relancer Apache :
	
	sudo service apache2 restart

// Installer Ruby :
	
	sudo apt-get install ruby (version de ruby par défaut)

// Installer Git :
	
	sudo apt-get install git

// Installer Jekyll 2.4 :
	
	sudo apt-get install ruby ruby-dev make (version de ruby développeur)
	sudo gem install jekyll --no-rdoc –no-ri
	sudo apt-get install nodejs
	jekyll - v (vérifier la version de jekyll)

// Créer un répertoire site :
	
	mkdir /votredossier/sites


////////////// CONFIGURATION GITHUB \\\\\\\\\\\\\\\\

// Sur le site Github, après avoir crée un compte :

  	Barre de menu > icône « + » > new repository
	Dans repository name = "votreusername".gitbuh.io
	
// Mettre votre projet en public :
	
	Séléctionner « initialize this repository with a README.md »,
	Après, cliquer sur "Create".
	
	
/////////////// CONFIGURATION GITHUB PAGES \\\\\\\\\\\\\\
	

// Aller à la racine de votre dossier "sites"

	cd /votredossier/sites

// Cloner votre répertoire Github :

	git clone https://github.com/votreusername/votreusername.github.io

// Entrer dans votre dossier projet et modifier/ajouter un fichier index.html pour tester votre configuration :

	cd username.github.io
	echo "Hello World" > index.html

// Ajouter, et mettre à jour vos modifications :

	git add --all
	git commit -m "Initial commit"
	git push

// Suivez les indications : 

	Tapez votre nom d'utilisateur Github et votre mot de passe.
	Actualiser votre projet Github sur votre navigateur internet et verifier que le fichier index.html est 	apparu.
	Si oui, votre configuration est valide. Si non, bon courage.

	
Si vous souhaitez faire des modifications sans avoir à entrer votre mot de passe à chaque "git pull", dirigez-vous vers ce lien https://help.github.com/articles/generating-ssh-keys/#platform-linux
