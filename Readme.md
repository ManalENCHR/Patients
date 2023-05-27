<h1>Compte rendu Activite 4: Spring Security</h1>


<h2>Structure du projet:</h2>
Les quatres packages principales de ce projet:
`entities` contient les classes d'entité suivantes:

- `Patient`: décrit un patient avec des informations telles que le nom, la date de naissance, etc.

`repository` contient les interfaces de repository suivantes:

- `PatientRepository`: fournit des méthodes pour interagir avec la base de données pour la classe `Patient`.

`security` contient les classes de configuration suivantes qui existe dans different packages pour l'authentification et l'autorisation des utilisateurs:
Sous ce packages il y a trois packages:

- `SecurityConfig`: configure la sécurité de l'application.

1: `entities` contient les classes d'entité suivantes pour l'authentification et l'autorisation des utilisateurs:

- `AppRole`: décrit un rôle d'utilisateur pour l'authentification et l'autorisation.
- `AppUser`: décrit un utilisateur avec des informations telles que le nom d'utilisateur, le mot de passe, etc.

2: `repo` contient les interfaces de repository suivantes pour l'authentification et l'autorisation des utilisateurs:

- `AppRoleRepo`: fournit des méthodes pour interagir avec la base de données pour la classe `AppRole`.
- `AppUserRepo`: fournit des méthodes pour interagir avec la base de données pour la classe `AppUser`.



Le dossier `templates` contient les pages HTML suivantes:

- `template.html`: barre de navigation commune à toutes les pages.
- `login.html`: page pour l'authentification des utilisateurs.
- `noAuthorized.html`: page pour afficher un message d'erreur lorsque l'utilisateur n'est pas autorisé à accéder à une page.
- `formPatient.html`: page pour ajouter un nouveau patient.
- `editPatient.html`: page pour modifier les informations d'un patient.
- `patients.html`: page pour afficher une liste de patients.




