---
name: visuels-pas-ia
description: Choisir et décrire les images, illustrations et icônes d'un site pour qu'elles ne trahissent pas un site généré par IA. À utiliser quand Claude place des images dans une page, écrit un prompt d'image, choisit une banque d'images, des icônes ou des illustrations, ou quand l'utilisateur trouve que ses visuels « font IA ».
---

# Visuels pas IA

Les visiteurs repèrent les visuels IA encore plus vite que les textes : peau trop lisse, mains bizarres, lumière dorée partout, personnages en 3D pâte à modeler, bureaux parfaits où personne ne travaille. Un visuel doit **montrer quelque chose de vrai** sur l'entreprise.

## Ordre de préférence

1. **Photos réelles** de l'entreprise : le lieu, l'équipe, le produit, les mains au travail, même prises au téléphone.
2. **Captures réelles** : l'app, le site, le tableau de bord, un vrai résultat.
3. **Schémas simples** faits pour la page : un flux, un avant/après, un plan.
4. **Banque d'images**, seulement des photos documentaires (Unsplash, Pexels) qui ne ressemblent pas à des publicités.
5. **Image générée par IA**, en dernier recours, jamais avec des personnes en gros plan.

Si aucune vraie image n'existe, mets un emplacement explicite `[PHOTO : l'atelier, vue large]` plutôt qu'une image générique.

## Les signes qui trahissent

| Signe | À la place |
|---|---|
| Personnes souriantes face caméra sur fond flou | Personnes de profil, en train de faire quelque chose |
| Lumière dorée, contre-jour, bokeh partout | Lumière normale, même un peu plate |
| Illustrations 3D de personnages aux grosses mains | Pictogrammes au trait, ou rien |
| Écrans avec du faux code ou des graphiques sans sens | Vraie capture, floutée si nécessaire |
| Icônes fusée, cerveau, éclair, ampoule | Icônes qui représentent l'action réelle (calendrier, facture, carte) |
| Mélange de styles d'icônes | Un seul jeu d'icônes, même épaisseur de trait |
| Arrière-plans abstraits en dégradé | Couleur unie de la marque |

## Si une image IA est vraiment nécessaire

Écris le prompt comme une consigne de photographe, pas comme une pub :

- Décris un lieu précis, une heure, un objectif : « Photo documentaire, 35 mm, lumière de fin de matinée, établi de menuisier avec copeaux, aucun personnage. »
- Interdis les clichés : « pas de bokeh, pas d'éclairage cinématographique, pas de sourire face caméra ».
- Évite les mains, le texte et les visages en gros plan.
- Vérifie le résultat à 100 % : doigts, texte, reflets, objets fondus.

## Technique

- Toujours un `alt` qui décrit ce qu'on voit, pas « image » ni le nom du fichier.
- Formats modernes (WebP/AVIF), dimensions fixées pour éviter les sauts de page.
- Une image qui n'apporte aucune information doit être supprimée, pas optimisée.
