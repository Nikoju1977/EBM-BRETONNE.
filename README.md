# Cyber-Fest-Noz — Groovebox EBM Breizh

**Catégorie : musique électronique & création sonore** · Studio Niko Design

Groovebox expérimentale dans le navigateur mêlant esthétique EBM et références bretonnes. L'interface principale se trouve dans `index.html` ; les fichiers `index.v1.html` et `index.pre-biniou-v3.html` conservent des versions antérieures.

## Démarrage

Ouvrir `index.html` dans un navigateur moderne. Pour travailler depuis un serveur local :

```bash
python3 -m http.server 8000
```

Puis ouvrir http://localhost:8000/.

## Technique

- HTML, CSS et JavaScript côté navigateur.
- Moteur audio [Tone.js](https://tonejs.github.io/) chargé depuis un CDN.
- Typographies chargées depuis Google Fonts.
- Le chargement initial requiert donc une connexion au réseau ; les politiques d'activation audio des navigateurs peuvent exiger une interaction de l'utilisateur.

## Structure

| Élément | Rôle |
| --- | --- |
| `index.html` | Version actuelle de la groovebox |
| `index.v1.html` | Version historique |
| `index.pre-biniou-v3.html` | Sauvegarde antérieure à des évolutions de l'interface |
| `.github/workflows/` | Configuration des automatisations GitHub |

## Statut et limites

**Projet créatif / expérimental.** La présence du code sur GitHub ne garantit pas qu'une démo soit publiée ni que chaque fonctionnalité soit compatible avec tous les navigateurs mobiles. Aucun build audio ni test automatisé n'a été exécuté pendant cette mise à jour de documentation.

Voir aussi : [nikogroove](https://github.com/Nikoju1977/nikogroove) et [Thelovestronautes Machine](https://github.com/Nikoju1977/the-lovestronautes-machine).

[Retour au catalogue Studio Niko Design](https://github.com/Nikoju1977#2-musique-audio--création-sonore).
