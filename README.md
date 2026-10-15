# TCG des potes

Jeu de cartes à collectionner entre amis, illustré avec nos propres photos.

## Voir et modifier la maquette sur ton PC

La maquette des cartes tient dans un seul fichier : `index.html`.

1. Récupère le projet : bouton vert **Code** sur GitHub, puis **Download ZIP** (ou `git clone`).
2. Ouvre `index.html` par un double-clic : il s'ouvre dans ton navigateur.
3. Pour modifier, ouvre le dossier dans un éditeur (par exemple [VS Code](https://code.visualstudio.com/)), change le fichier, enregistre, puis rafraîchis la page (F5).

### Où changer quoi dans `index.html`

| Tu veux changer | Cherche |
|---|---|
| Les couleurs d'une rareté (cadre, plaques, gemme) | `.r-common`, `.r-rare`, `.r-epic`, `.r-legend` |
| Les variantes pixel art, full art, dorée | `.v-pixel`, `.v-full`, `.v-gold` |
| Les reflets et effets | `.glare`, `.sweep`, `.foil`, `.sparks` |
| Les cartes d'exemple (noms, titres, textes, lieux) | `const CARDS` dans le script |
| Les polices | `--f-display`, `--f-card`, `--f-pixel` en haut du style |

Le bouton « Essayer avec ta photo » met une de tes photos sur toutes les cartes, sans l'envoyer nulle part.

## Règles du jeu

Raretés, taux de drop et variantes : voir `design/raretes.md` dans les fichiers du projet.
