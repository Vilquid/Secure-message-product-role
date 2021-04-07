# Autorisation avec des portées, des rôles et des tokens
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
