---
name: voix-de-marque
description: Extraire la façon de parler d'une marque ou d'une personne à partir de ses textes existants (site, messages, posts, e-mails) et en faire un guide de voix réutilisable, puis écrire de nouveaux textes avec cette voix. À utiliser quand l'utilisateur veut que ses textes « sonnent comme lui », fournit des exemples de son style, ou démarre un site pour une marque qui a déjà du contenu.
---

# Voix de marque

Un texte sonne IA quand il sonne comme personne. La solution n'est pas « un ton professionnel et chaleureux » : c'est de copier la façon d'écrire de la vraie personne derrière la marque.

## 1. Collecter des exemples

Demande ou récupère au moins 5 textes écrits par la personne elle-même, idéalement spontanés : messages Discord ou WhatsApp, réponses à des clients, posts, notes vocales retranscrites. Les textes déjà « marketing » sont moins utiles.

## 2. Analyser

Relève, avec des citations :

- **Pronoms et adresse :** je / on / nous, tu / vous.
- **Longueur des phrases :** courte et sèche, ou longue avec des virgules ?
- **Vocabulaire récurrent :** expressions, mots familiers, anglicismes, jargon du métier.
- **Ce qu'elle ne dit jamais :** formules qu'elle n'utiliserait pas.
- **Ponctuation et tics :** points d'exclamation, emojis (lesquels, combien), points de suspension, majuscules.
- **Humour :** présent ? de quel type ?
- **Rapport au client :** copain, expert, artisan, grand frère ?

## 3. Écrire le guide

Crée un fichier `VOIX.md` à la racine du projet :

```markdown
# Voix de [MARQUE]

En une phrase : [ex. « Un dev qui parle à ses clients comme à des potes, sans jargon, mais qui ne rigole pas avec la sécurité. »]

## On dit
- « … » (citation réelle)
- …

## On ne dit jamais
- « … »
- …

## Règles
- Tutoiement partout.
- Phrases courtes. Une idée par phrase.
- Emojis : 1 maximum par bloc, parmi 🔥 👀 🎃.
- …

## Exemples avant / après
…
```

## 4. Écrire avec la voix

- Relis `VOIX.md` avant chaque texte.
- Écris, puis compare à 2 citations réelles : si on ne peut pas croire que c'est la même personne, réécris.
- Applique en plus les règles de `textes-humains`.
- En cas de doute entre la voix et une règle de « bonne rédaction », la voix gagne (sauf faute d'orthographe).
