# Renovate Config

Configuration globale de [Renovate](https://docs.renovatebot.com/) pour nos projets.

## Installation sur un nouveau projet

À la racine d'un projet, créer le fichier `renovate.json` : 

```json
{
  "$schema": "https://docs.renovatebot.com/renovate-schema.json",
  "extends": ["github>Yproximite/renovate-config"],
  "hostRules": [
    {
      "hostName": "repo.packagist.com",
      "hostType": "packagist",
      "encrypted": {
        "username": "<username chiffré>",
        "password": "<password chiffré>"
      }
    }
  ],
}
```

## Liens utiles

- [Configurer Renovate](https://docs.renovatebot.com/configuration-options/)
- [Dashboard Renovate](https://app.renovatebot.com/dashboard)
- [Chiffrer des secrets pour Renovate](https://app.renovatebot.com/encrypt)
