---
title: Affichage EDF
publishDate: 2021-03-02 00:00:00
img: /assets/Affichage-logo.png
img_alt: Iridescent ripples of a bright blue and pink liquid
description: |
  Petit module Javascript permettant de faciliter le travail d'anciens collègues !
tags:
  - Serverless
  - Functions
  - Dev
---

Ce "helper", comme j'ai l'habitude de l'appeler, a été pensé lors d'un job étudiant, nous devions chaque jour recopier à la main les lignes d'un fichier Excel, contenant les réunions de tout le site, et qui pouvait être très long (jusqu'à 1 h de recopiage). J'ai tout de suite pensé que je devrais l'automatiser plutôt que de me torturer à reproduire ça, j'ai donc codé ce Helper afin qu'il soit utilisé par mes anciens collègues !

A l'heure actuelle, il suffit d'importer/glissez-déposez un fichier pour qu'il soit automatiquement traité et qu'il génère un fichier PDF avec toutes les infos au bon endroit, un petit récapitulatif des données s'affiche sous forme de tableau une fois le fichier déposé ! On est passé de ≈ 1 h à quelques secondes.

J'utilise la library pdftk pour la génération de PDF qui tourne sur une AWS Lambda function (serverless) mise à disposition par Netlify !

Lien vers le site pour démo : [affichage-edf.app](https://affichage-edf.netlify.app/).

---

_Auteur:_ **Nassim** _alias_ [@NasssDev](https://github.com/NasssDev).