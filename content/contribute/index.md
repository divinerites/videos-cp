---
title: "toto"
headless: true
---

### Organisation du site

Les données permettant de générer le site sont publiques et disponibles sur [https://github.com/divinerites/videos-cp](github.com)

Ces données sont dans un fichier texte : `/data/items.toml`.

### Proposer une correction

1. Il suffit de cliquer sur le lien `Contribuer` situé en haut à droite de chaque page.
1. Vous arrivez directement sur la page des informations en *mode modification*.
1. Il vous suffit de modifier l'information désirée.
   - Si besoin faire un recherche *(ctrl-F)* sur la page pour trouver rapidement la ligne concernée
1. En bas de page indiquez la nature du changement, une fois celui ci effectué.
1. Vaidez "Create a new branch and start a pull request".
1. Votre proposition sera examinée et intégrée dans le site. Ne vous inquiétez pas, vous ne pouvez rien casser.

### Organisation du fichier d'information sur les vidéos

Chaque information concernant une vidéo est très simplement structurée, une information = une ligne.

Il s'agit d'un `format texte` de type `toml`. Et n'importe qui sans connaissance technique peut proposer une modification pour corriger une erreur.

L'avantage de ce format universel et ouvert est d'éviter de perdre ces informations publiques
pour cause de base de donnée obsolète ou corrompue.
Il est ouvert, libre, pérenne et très simple à manipuler si besoin, y compris dans 10 ou 20 ans.

#### Exemple de données pour une vidéo

```toml
[items]]
   saison = "WPT National 2011"
   episode = "High Roller - Episode 1"
   description = "WPT National Series"
   circuit =  "WPT National"
   date = "2011"
   ville = "Paris"
   casino = "Aviation Club de France"
   sixmax = false
   vo = false
   buyin = "freeroll"
   variante = "NLHE"
   source = "DivxPoker"
   url = "https://1fichier.com/?hu7xaf5dsbumnrnxb3lu"
```

Un grand merci aux futurs contributeurs.
