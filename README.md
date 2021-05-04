# Renovate Config

Configuration globale de [Renovate](https://docs.renovatebot.com/) pour nos projets.

## Installation sur un nouveau projet

À la racine du projet, créer un nouveau fichier `renovate.json` avec ce contenu : 
```json
{
  "$schema": "https://docs.renovatebot.com/renovate-schema.json",
  "extends": ["local>Yproximite/renovate-config"]
}
```
