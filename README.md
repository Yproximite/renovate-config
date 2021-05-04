# Renovate Config

Configuration globale de [Renovate](https://docs.renovatebot.com/) pour nos projets.

## Installation sur un nouveau projet

Cette configuration globale est en réalité déjà effective pour tous les projets, car c'est une [configuration "au niveau de l'organisation"](https://docs.renovatebot.com/config-presets/#organization-level-presets).

En revanche, il est préférable [d'être explicite plutôt qu'implicite](https://www.python.org/dev/peps/pep-0020), et donc de configurer Renovate au niveau du projet en créant un fichier `renovate.json` :
```json
{
  "$schema": "https://docs.renovatebot.com/renovate-schema.json",
  "extends": ["local>Yproximite/renovate-config"]
}

```
