---
name: audit-site-ia
description: Auditer un site existant (fichiers du projet ou URL) pour repérer tout ce qui fait « généré par IA » dans les textes, le design et la structure, avec un score et une liste de corrections classées. À utiliser quand l'utilisateur demande si son site fait IA, veut un avis critique sur une page, ou avant une mise en ligne.
---

# Audit « ça fait IA ? »

Tu fais l'audit d'un site comme le ferait un visiteur exigeant, puis comme un directeur artistique. Tu ne réécris rien pendant l'audit : tu constates, tu notes, tu proposes.

## 1. Récupérer le contenu

- Projet local : lis les pages (HTML, JSX, MDX, templates), le CSS ou la config Tailwind, et les fichiers de contenu.
- URL : récupère la page et les pages liées principales (accueil, à propos, services, contact).
- Note la langue et le tutoiement ou vouvoiement utilisé.

## 2. Passer la grille

Pour chaque critère, note 0 (problème net), 1 (moyen) ou 2 (bon), et cite **l'extrait exact** qui justifie la note.

**Textes (10 points)**
1. Phrases interchangeables avec un concurrent
2. Mots et tournures du skill `textes-humains` (liste à bannir)
3. Faits vérifiables : chiffres, noms, lieux, délais
4. Groupes de trois et questions rhétoriques
5. Longueur : est-ce que chaque section pourrait perdre 30 % sans rien perdre ?

**Design (10 points)**
6. Dégradés, glassmorphism, badges « ✨ »
7. Sections qui ont toutes la même structure (titre centré + grille de cartes)
8. Images qui n'informent pas (illustrations 3D, icônes génériques)
9. Typo : polices par défaut, hiérarchie plate
10. Présence d'une signature visuelle propre à la marque

**Confiance (6 points)**
11. Témoignages vérifiables ou suspects
12. Chiffres crédibles ou ronds et invérifiables
13. Contact réel (nom, e-mail, adresse, mentions légales)

**Finition (4 points)**
14. Typographie de la langue (voir `typo-francaise`)
15. Microcopy des boutons, formulaires et erreurs (voir `microcopy`)

## 3. Rendre le rapport

Format :

```
## Score : XX/30 — [Très humain / Correct / Ça se voit / Template IA]

### Les 5 corrections qui changent le plus
1. [Problème] — extrait : « … » — fichier:ligne
   → [Correction concrète, avec proposition de texte si c'est du texte]
...

### Détail par critère
| # | Critère | Note | Constat |
...

### Ce qui marche déjà
- …
```

Barème : 26–30 très humain, 20–25 correct, 13–19 ça se voit, 0–12 template IA.

## Règles

- Sois précis et cite toujours. « Le texte est générique » sans extrait ne sert à rien.
- Classe les corrections par impact, pas par ordre d'apparition.
- Ne propose pas d'inventer des chiffres ou des avis. Si une preuve manque, dis quelle info demander au propriétaire du site.
- Termine en proposant d'appliquer les corrections, sans les appliquer d'office.
