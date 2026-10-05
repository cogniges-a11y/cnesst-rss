# Flux RSS – Formulaires et Publications CNESST

Flux RSS non officiel des **formulaires et publications** de la [CNESST](https://www.cnesst.gouv.qc.ca/).

**Source** : [Formulaires et Publications](https://www.cnesst.gouv.qc.ca/fr/organisation/documentation/formulaires-publications)

## URL du flux (à coller dans Inoreader / Feedly / etc.)

Une fois ce dépôt public, l’URL raw est :

```
https://raw.githubusercontent.com/VOTRE-UTILISATEUR/VOTRE-REPO/main/feed.xml
```

Remplacez `VOTRE-UTILISATEUR` et `VOTRE-REPO` par les vôtres.

## Contenu

| Fichier     | Description                                      |
|-------------|--------------------------------------------------|
| `feed.xml`  | Le flux RSS 2.0 (à souscrire)                    |
| `state.json`| État interne (publications déjà vues) – utilisé par l’automation de mise à jour |

## Mise à jour

Le flux est mis à jour de façon **incrémentale** (uniquement les nouvelles publications).  
Une automation Grok peut le rafraîchir automatiquement (étape 2).

## Licence / Avertissement

- Contenu issu du site public de la CNESST.
- Ce dépôt n’est **pas** officiel et n’est pas affilié à la CNESST.
- Utilisation à vos propres risques.
