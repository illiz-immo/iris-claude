# Iris dans Claude

Le plugin d'[illiz](https://github.com/illiz-immo) qui ouvre Iris, l'assistante des agents du réseau illiz, dans Claude. Il ne contient qu'un connecteur vers le serveur d'Iris et un skill de quelques lignes : la méthode et les données restent sur le serveur d'Iris, réservé aux comptes Google illiz.

## Plugins

| Plugin | Environnement | Serveur |
|---|---|---|
| `iris-staging` | recette | `https://iris-staging.illiz.fr/mcp` |

## Installer

1. Sur claude.ai ou dans l'application de bureau : **Personnaliser › Plugins › Ajouter › Ajouter une marketplace**, puis l'adresse de ce dépôt, `https://github.com/illiz-immo/iris-claude`.
2. Installer le plugin `iris-staging`.
3. Dans l'onglet **Connecteurs** du plugin, connecter le connecteur `iris` et choisir son compte Google illiz.

Dans Claude Code : `/plugin marketplace add illiz-immo/iris-claude`, puis `/plugin install iris-staging@illiz`.

## Ce que fait Iris ici

L'estimation rapide d'un bien à partir des ventes DVF : « combien vaut le 12 rue X, un appartement de 65 m² ? ». Le reste d'Iris (avis de valeur, CRM) se travaille sur iris.illiz.fr.

Ce dépôt ne contient aucun secret.
