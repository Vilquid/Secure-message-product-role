# English
# Definitions
Authentication: verify "you are who you say you are"

Authorization: check "you are authorized to do what you are trying to do"

Scope: smallest entity that describes a single permission (ex: read: message)

Role: set of several staves
A role can be assigned to a user or included in another role (eg admin, manager, user).

Token: object containing all scopes for an authenticated user
A token can be used by applications to check if a user is authorized to access to an endpoint.

# Scopes VS roles
Main difference: who determines what the customer is allowed to do
- Roles and user groups are assigned by an administrator
- Scope: indicate the permissions that a user allows to a client application
- Role: designate if the user is just a regular user or an administrator

# Français
# Définitions
Authentification : vérifier « vous êtes qui vous dites être »

Autorisation : vérifier « vous êtes autorisé à faire ce que vous essayez de faire »

Portée (scope) : plus petite entité qui décrit une seule permission (ex : read:message)

Rôle (role) : ensemble de plusieurs portées
Un role peut être attribué à un utilisateur ou inclus dans un autre rôle (ex : admin, manager, user).

Jeton (token) : objet contenant toutes les portées pour un utilisateur authentifié
Un token peut être utilisé par les applications pour vérifier si un utilisateur est autorisé pour accéder 
à un point de terminaison (endpoint).

# Scopes VS roles
Principale différence : qui détermine ce que le client est autorisé à faire
- Les rôles et groupes d'utilisateurs sont attribués par un administrateur
- Scope : indiquer les autorisations qu'un utilisateur autorise à une application cliente
- Role : désigner si l'utilisateur est juste un utilisateur régulier ou un administrateur
