# Sécurité

Ne publiez jamais de clé privée, de configuration personnelle, de journal d'installation contenant des chemins privés, ni de catalogue local.

Les vulnérabilités doivent être signalées de façon privée à l'auteur du dépôt. Les propositions de catalogue soumises par issue sont traitées comme des données non fiables : elles ne sont jamais distribuées automatiquement.

Le client final doit vérifier une signature ECDSA P-256 et des limites strictes de taille et de contenu avant d'appliquer un catalogue distant.
