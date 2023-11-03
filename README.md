# library-management
API that manages library.


# Ecriture d'une spécification OAS

## Utilisation de la syntaxe YAML ou JSON en suivant ces spécifications OpenAPI:
* les fonctionnalités: ce que permet de faire l'API
* les endpoints: point d'entrée
* les opérations: les actions à effectuer
* les paramètres et les données en entrée
* les types de données et d'autres aspects de votre API

# structure des objets:
* info object: version, nom etc de l'API
* contact OBject: information de contact du fournisseur de l'API
* license object: licence sous laquelle l'API propose ses données
* server object: nom de l'hôte, structure URL et ports du serveur sur lequel sera interrogée l'API
* components object: composants encapsul"s qui sont utilisés plusieurs fois dans la définition API
* paths object: chemins d'accièis relatifs aux points de terminaison de l'API, utilisés avec le Server Object, les endpoints
* path item object: pour les opérations autorisées à prendre un chemin spécifique, come GET, PUT, POST, DELETE
* operation object: définit les paramètres et les réponses du serveur attendues pour une opération
