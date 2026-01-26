Architecture 3 tiers 
Présentation
Logique métier
Donnees

Navigateur >> react -Frontend>>Node + Express - API >> DB SQL or NoSQL

Frontend:
	Interface user 
	dynamic data display
	gestion interaction user
Outils:
	React
		JSX
		CSS/Bootstrap
		Axios/Fetch API
Backend: 
	Traiter requetes client
	Appliquer regles metier
	securiser appli
	communiquer avec DB
	Outils:
	Node Espress API JSON
Organisation BE:
	Routes: ponits acces url
	Controleurs: logique metier
	Services; logique reutilisable
		Modele: structure des données
	Middleware: fonction execute entre requete et reponse
	Utilisation: Authentification, data validation, error management, logs (ExpressJson, verifyToken, express-validator)
Auth with JWT:
	Processus:
		user sends IDs
		Server gens JWToken
		Client stores token
		token is used for each protected request
Data Layer:
DATABASE
	Role:
		Stocker données
		assurer persistance
		gérer relations
	Types: 
	NoSQL
	SQL
Accès via: ORM or ODL

Why n-tier architecture:
	Can add more layers:
		cache(redis)
			External Services
			Microservices
			Authentication
			More layers>> more modular
Avantages archi 3 tiers:
	Séparation responsabilités
	maintenance facile
	sécurité renforcée
	évolutivité 
	travail équipe simplifié

## Étude Préliminaire

- Planification: express. des besoins, définition des  périmètres
- Conception: Réalisation arborescence, définition parcours, gabarits de page.
- Maquettes: Création de maquettes graphiques
- Diagrammes: UML
- Contraintes techniques
- Objectif:
	- Comprendre fonctionnement global 
	- identifier règles de métier
	- repérer contraintes(sécurité, performance, technologiques)
#### Fonctionnalité

Ce que user peut faire dans application
- Exemple:
-Fonctionnalité doit être claire, mesurable et testable

Une fois identifiée, découpée en Tâche technique
	Ex: créer formulaire React
	Créer route Express
	Tester API
	Etc..

#### Découpage en tâches
- Frontend:
	- Form React
	- Validation coté client
	- Appel API
- Backend:
	- route POST-register
	- Tableaux fonctionnalités
	- Backlog tâches
	- User stories
	- Schémas architecture

START WITH MVP AND ADD EXTRA AFTER THAT

Outils:
	- Diagrammes UML
	- Tableau de fonctionnalités
	- Backlog de tâches
	- User stories
	- Schémas archi

