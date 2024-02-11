------------------------------------------------------------------------------------------------------
PROJET METRIQUES
------------------------------------------------------------------------------------------------------
Quels sont les notions qui vont être abordés lors cet atelier ?
Cet atelier a pour objectif de vous apprendre à créer des graphiques (métriques) grace à Python et la construction d'API.
Vous allez utiliser et mettre en oeuvre, au travers de cet atelier, un serveur Python utilisant le frameworks Flask. 
Vous allez créer des API, découvrir les actions et les secrets de GitHUB pour au final la mise en services des bibliothèques graphiques.
Large programme mais tout à fait accessible et ne nécessitant pas de base technique particulière. Juste de l'observation et de la rigueur.

-------------------------------------------------------------------------------------------------------
Séquence 1 : GitHUB
-------------------------------------------------------------------------------------------------------
Objectif : Création d'un repository GitHUB pour travailler avec son code
Difficulté : Faible (~10 minutes)
-------------------------------------------------------------------------------------------------------
GitHUB est une plateforme en ligne utilisée pour stocker le code de son programme.
GitHUB est organisé en "Repository", c'est à dire en répertoire (contenant lui même des sous répertoires et des fichiers). Chaque Repository sera indépendant des autres. Un Repository peu être vu comme un projet unique.

**Procedure :**
1° - Créer vous un compte sur GitHub : https://github.com/
Si besoin, un vidéo pour vous aider à créer votre propre compte GitHUB : https://docs.github.com/fr/get-started/onboarding/getting-started-with-your-github-account
A noter que si vous possédez déjà un compte GitHUB vous pouvez le conserver pour réaliser cet atelier. Pas besion d'en créer un nouveau.

2° - Faites un Fork du Repository suivant : https://github.com/OpenRSI/5MCSI_Metriques.git
Si besion, voici une vidéo d'accompagnement pour vous aider à "Forker" ce projet : https://www.youtube.com/watch?v=yoBAszjRI3o

Remarque : Pour faciliter l'atelier ne modifiez pas le nom de votre fork et intitulez le flask_hello_world

Travail demandé :
Créé votre compte, faites le fork et copier l'URL de votre repository GitHUB dans la discussion public.

Notion acquise lors de cette séquence :
Vous avez appris lors de cette séquence à créer des repository pour stocker et travailler avec votre code informatique. Vous pourez par la suite travailler en groupe sur un projet. Vous avez également appris également des forks. C'est à dire, faire des copies de code déjà existant dans GitHUB (vous l'approprier..)




---------------------------------------------------
Séquence 1: Création d'un hébergement en ligne
---------------------------------------------------
Objectif : Créer un hébergement sur Alawaysdata
Difficulté : Faible (~20 minutes)
---------------------------------------------------

Rendez-vous sur https://www.alwaysdata.com/fr/

1° - Créez votre compte (gratuit jusqu'à 100Mo)
2° - Depuis la console d'administration (Panel d'administration) :
	2.1 - Cliquez sur "Sites" (Colonne de gauche) puis supprimer votre site PHP (Poubelle)
	2.2 - Installer ensuite une application Flask (Bouton + Installer une application)
		2.2.1 Adresses = utilisez le sous-domaine qui vous appartient que vous trouverez dans l'information " Les sous-domaines suivants vous appartiennent et sont actuellement inutilisés : {Site}.alwaysdata.net
		2.2.2 Répertoire d'installation = /www/flask
		2.2.3 N'oubliez pas d'Accepter les conditions
		
Travail demandé : **Mettre en ligne votre application** et copier l'URL dans la discussion Discord

Remarque : **Attention à bien vous rappeler vos Login/Password** car vous en aurez besoin plus tard pour les connexions SSH.

Notion acquise lors de cette séquence :
Vous avez créer un hébergement (gratuit) et découvert que vous auriez pu installer bien d'autres applications. 





