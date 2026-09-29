# InstallRouteur

Client Windows natif qui adapte le dossier proposé par un installateur selon des règles locales : produit, catégorie et sous-catégorie.

Le client est volontairement limité : il observe les fenêtres visibles, puis modifie uniquement un champ de destination déjà proposé lorsqu'une correspondance locale est sans ambiguïté. Il n'installe aucun pilote, service, hook ni injection.

## État du projet

- client Windows Win32 : prototype fonctionnel local ;
- règles locales et taxonomie : disponibles ;
- catalogue public : en préparation ;
- synchronisation distante : ne sera activée qu'après vérification cryptographique côté client.

Les données personnalisées de chaque utilisateur restent locales et ne sont jamais publiées dans ce dépôt.

## Catalogue public

Le référentiel public est séparé dans [InstallRouteur-catalog](https://github.com/mindofillusion/InstallRouteur-catalog). Une version du catalogue ne pourra être importée par le client qu'après contrôle de sa signature ECDSA P-256, de sa version et de son intégrité.

## Proposer une classification

Utilisez le formulaire « Proposer une classification » dans les issues. Une proposition est revue avant d'être ajoutée au catalogue candidat, puis publiée par une procédure de signature hors ligne.

## Licence

Ce dépôt est public, mais aucune licence de réutilisation n'est encore accordée. Ce choix sera documenté avant toute ouverture aux contributions de code.
