---
name: design-pas-ia
description: Concevoir l'interface d'un site ou d'une landing page (HTML/CSS, React, Tailwind, Next.js…) sans les clichés visuels des sites générés par IA. À utiliser chaque fois que Claude crée ou refait une page web, choisit des couleurs, une police, une mise en page ou des composants, surtout quand l'utilisateur dit que son site « fait IA », « fait template » ou « ressemble à tous les autres ».
---

# Design pas IA

Un site généré par IA se reconnaît avant même de lire : dégradé violet-bleu, hero centré avec un badge « ✨ Nouveau », trois cartes d'icônes identiques, police Inter partout, des coins arrondis à 24 px sur tout. Ce n'est pas moche. C'est juste la moyenne de tout ce qui existe, donc ça ne dit rien de la marque.

## Étape 1 : partir de la marque, pas d'un template

Avant de coder, fixe ces choix et écris-les en commentaire en haut du CSS :

- **Une référence réelle.** Un objet, un lieu ou un métier lié à la marque (une enseigne de garage, un menu de bistrot, un ticket de caisse, un plan de métro). Les choix visuels en découlent.
- **Couleurs :** une couleur principale prise dans le logo ou la référence, un neutre qui n'est pas du gris pur (légèrement chaud ou froid), une couleur d'accent utilisée sur moins de 5 % de la page.
- **Typo :** deux polices au maximum, avec un vrai contraste (une avec du caractère pour les titres, une très lisible pour le texte). Évite Inter + Inter par défaut.
- **Une règle de forme :** des coins carrés, ou très arrondis, ou un seul rayon partout. Mais un choix assumé, pas `rounded-2xl` partout par réflexe.

## Les clichés à éviter (et quoi faire à la place)

| Cliché IA | À la place |
|---|---|
| Dégradé violet → bleu ou rose → orange en fond | Aplat de couleur de marque, ou photo réelle |
| Hero centré : badge + titre + sous-titre + 2 boutons | Mise en page asymétrique, titre aligné à gauche, une seule action principale |
| 3 cartes « icône + titre + 2 lignes » | Une liste numérotée, un tableau, une capture annotée, un vrai exemple |
| Glassmorphism et flous partout | Fonds pleins, bordures nettes |
| Icônes génériques (fusée, éclair, bouclier) | Photos du produit, captures, schémas spécifiques |
| Illustrations 3D de personnages | Photos de vraies personnes ou du vrai lieu |
| Témoignages « John D., CEO » avec avatar généré | Vrais avis avec source (Google, Malt, lien), ou rien |
| Chiffres ronds inventés (« 10 000+ clients ») | Chiffres réels, même petits (« 37 clients depuis 2023 ») |
| Animations de fondu sur chaque section au scroll | Une ou deux animations qui ont un sens, le reste statique |
| Emoji devant chaque titre de section | Rien, ou un pictogramme dessiné pour la marque |
| Section FAQ générique en accordéon | Les 3 vraies questions que posent les clients, avec de vraies réponses |
| Footer à 4 colonnes de liens vides | Adresse, contact, mentions légales. Le strict utile. |

## Détails qui font « fait main »

- Une grille qui casse une fois volontairement (une image qui déborde, un titre qui chevauche un bloc).
- Des tailles de titres très contrastées (un H1 énorme, des H2 sobres) plutôt que tout en taille moyenne.
- Du texte réel dans les maquettes dès le début, jamais de lorem ipsum.
- Des états soignés : bouton au survol, focus clavier visible, page 404 avec le ton de la marque.
- Une signature : un détail récurrent propre à la marque (un soulignement dessiné, un tampon, un motif tiré du logo).

## Vérification avant de rendre

Pose-toi ces questions et corrige si la réponse est oui :

1. Si j'enlève le logo, est-ce qu'on pourrait croire que c'est le site d'un concurrent ?
2. Est-ce que la page contient un dégradé, un badge « ✨ », trois cartes identiques et Inter, tout à la fois ?
3. Est-ce qu'il y a une image ou une illustration qui n'apporte aucune information ?
4. Est-ce que chaque section a la même structure (titre centré, sous-titre gris, grille) ?

Combine ce skill avec `textes-humains` : un design original avec des textes génériques fait toujours IA.
