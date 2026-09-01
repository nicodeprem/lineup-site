# Le site de Line-up

Deux pages, hébergées par GitHub Pages. Elles sont **autonomes** : la feuille
de style et l'icône sont écrites dedans, il n'y a aucun fichier annexe et
aucun chemin relatif qui puisse casser.

| Fichier | Sert de |
|---|---|
| `index.html` | page d'assistance — l'URL d'assistance dans App Store Connect |
| `confidentialite.html` | politique de confidentialité — l'URL obligatoire |

## Les modifier

Ne pas retoucher le HTML à la main : la source est `docs/confidentialite.md`
dans le dépôt de l'app, et `python3 tools/build_site.py` régénère la page.
