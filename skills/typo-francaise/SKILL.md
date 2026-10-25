---
name: typo-francaise
description: Appliquer les règles de typographie française (espaces insécables, guillemets, majuscules accentuées, nombres, dates, unités) aux textes et au code d'un site en français. À utiliser chaque fois que Claude écrit ou relit du texte français destiné à être publié, ou génère du HTML/JSX contenant du texte en français.
---

# Typographie française

Les modèles écrivent souvent le français avec les règles de l'anglais : guillemets droits, pas d'espace avant le point d'interrogation, majuscules sans accents. C'est un signe immédiat de texte généré ou traduit.

## Espaces

En HTML, utilise l'espace insécable `&nbsp;` (ou le caractère U+00A0), et l'espace fine insécable U+202F quand c'est indiqué.

| Signe | Règle | Exemple HTML |
|---|---|---|
| `:` | espace insécable avant, espace après | `Contact&nbsp;: 06…` |
| `;` `!` `?` | espace fine insécable avant | `Prêt&#8239;?` |
| `« »` | espace insécable à l'intérieur | `«&nbsp;Super&nbsp;»` |
| `%` | espace insécable avant | `10&nbsp;%` |
| `€` et unités | espace insécable avant | `49&nbsp;€`, `12&nbsp;km` |
| milliers | espace fine insécable | `12&#8239;500` |

Dans du JSX, utilise `{" "}` ou le caractère directement, jamais une espace normale (le navigateur pourrait couper la ligne avant le `?`).

## Guillemets et apostrophes

- Guillemets français `« »` pour les citations. Guillemets anglais `“ ”` seulement à l'intérieur d'une citation.
- Apostrophe typographique `’` dans le texte affiché. Garde `'` dans le code.

## Majuscules

- Les majuscules prennent leurs accents : « État », « À propos », « ÉQUIPE ».
- Pas de majuscule à chaque mot des titres (règle anglaise) : « Nos services de création », pas « Nos Services De Création ».
- Mois et jours en minuscules : « lundi 3 mars ».

## Nombres et dates

- Décimales avec une virgule : `4,9/5`, `1,5 Mo`.
- Dates : « 25 octobre 2026 » ou `25/10/2026`. Jamais `10/25/2026`.
- Heures : `14 h 30` ou `14h30` (choisis un format et garde-le). Pas `2:30 PM`.
- Ordinaux : `1er`, `2e`, `XXIe siècle` (pas `2ème`, `1st`). En HTML : `1<sup>er</sup>`.

## Ponctuation

- Points de suspension : un seul caractère `…`.
- Tiret d'incise : tiret demi-cadratin `–` entouré d'espaces, ou cadratin `—`. Pas de trait d'union `-`.
- Pas de point après un titre ou un libellé de bouton.

## Vérification rapide

Cherche dans le texte final :
- ` ?`, ` !`, ` :` précédés d'une espace normale → remplace par insécable.
- `"` dans le texte affiché → `« »`.
- `A propos`, `Etat`, `Ecole` → `À propos`, `État`, `École`.
- Un nombre suivi de `%` ou `€` collé ou séparé par une espace normale.
