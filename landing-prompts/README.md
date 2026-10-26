# 10 prompts landing page qui ne font pas IA

Copie un prompt dans Claude Code (ou claude.ai), remplace ce qui est entre `[crochets]`, et tu obtiens une landing page codée, propre et qui ne ressemble pas à toutes les autres.

> Pour de meilleurs résultats, installe d'abord les skills de ce repo : Claude appliquera automatiquement `landing-page-humaine`, `textes-humains`, `design-pas-ia` et `typo-francaise`.

| # | Pour | Prompt |
|:-:|---|---|
| 01 | Artisan / commerce local | [Voir](#01--artisan-ou-commerce-local) |
| 02 | SaaS / outil en ligne | [Voir](#02--saas-ou-outil-en-ligne) |
| 03 | Restaurant | [Voir](#03--restaurant) |
| 04 | Coach / consultant | [Voir](#04--coach-ou-consultant) |
| 05 | Application mobile | [Voir](#05--application-mobile) |
| 06 | Freelance / agence | [Voir](#06--freelance-ou-agence) |
| 07 | Événement | [Voir](#07--événement) |
| 08 | Produit e-commerce unique | [Voir](#08--produit-e-commerce-unique) |
| 09 | Bot Discord / serveur | [Voir](#09--bot-discord-ou-serveur) |
| 10 | Liste d'attente / lancement | [Voir](#10--liste-dattente-ou-lancement) |

---

## 01 · Artisan ou commerce local

```text
Crée une landing page en HTML/CSS (un seul fichier index.html, sans framework) pour [MÉTIER] à [VILLE].

Fiche :
- Pour qui : [CLIENT TYPE, ex. propriétaires de maisons anciennes à Lyon]
- Son problème, avec ses mots : "[PHRASE DU CLIENT]"
- Promesse : [CE QU'IL OBTIENT, avec un délai si possible]
- Preuves : [3 FAITS RÉELS : années d'expérience, nombre de chantiers, un avis Google avec le prénom]
- Action unique : [appeler / demander un devis / réserver]

Règles :
- Hero aligné à gauche, titre de moins de 10 mots avec le bénéfice, téléphone cliquable visible sans scroller sur mobile.
- Une section "Comment ça se passe" en 3 étapes concrètes.
- Emplacements photo explicites [PHOTO : …] au lieu d'images génériques.
- Pas de dégradé, pas d'icônes fusée/éclair, pas de faux témoignages, pas de section "Nos valeurs".
- Couleurs tirées de [COULEUR DU LOGO / DU CAMION / DE LA VITRINE].
- Typographie française correcte (espaces insécables avant : ; ! ?).
À la fin, liste tout ce qui est marqué [À FOURNIR].
```

## 02 · SaaS ou outil en ligne

```text
Crée une landing page en React + Tailwind pour [NOM DU PRODUIT], un outil qui [CE QU'IL FAIT EN UNE PHRASE].

Fiche :
- Pour qui : [RÔLE + TAILLE D'ENTREPRISE]
- Problème actuel : [CE QU'ILS FONT AUJOURD'HUI ET QUI LEUR FAIT PERDRE DU TEMPS]
- Résultat mesurable : [GAIN, ex. "2 h par semaine en moins sur la facturation"]
- Preuve : [CAPTURE DE L'APP dans public/app.png, OU un chiffre réel d'utilisateurs]
- Action : [essai gratuit / démo de 15 min]

Règles :
- Le hero montre une vraie capture de l'interface, pas une illustration.
- Section "Avant / Après" sous forme de tableau à 2 colonnes, pas de cartes à icônes.
- Prix affichés clairement si [PRIX] est fourni, sinon pas de section prix.
- Un seul bouton principal, même texte partout.
- Pas de "Révolutionnez", "Boostez", "Libérez", "Solution tout-en-un".
```

## 03 · Restaurant

```text
Crée une landing page mobile d'abord pour le restaurant [NOM] à [VILLE] ([TYPE DE CUISINE]).

Infos réelles :
- Adresse : [ADRESSE] — horaires : [HORAIRES]
- 3 plats signatures avec prix : [PLAT 1 — PRIX], [PLAT 2 — PRIX], [PLAT 3 — PRIX]
- Ce qui nous différencie : [UNE PHRASE VRAIE, ex. "pâtes fraîches faites le matin"]
- Réservation : [LIEN / TÉLÉPHONE]

Règles :
- En haut : nom, une phrase, bouton "Réserver une table" et horaires du jour.
- Le menu en vrai texte (pas en image), lisible et sélectionnable.
- Emplacements [PHOTO : …] pour les plats, la salle, la cuisine.
- Carte Google Maps intégrée en bas, lien "Itinéraire".
- Ton chaleureux mais sans superlatifs ("le meilleur", "incontournable" interdits).
```

## 04 · Coach ou consultant

```text
Crée une landing page pour [PRÉNOM NOM], [MÉTIER] qui aide [CIBLE PRÉCISE] à [RÉSULTAT].

Fiche :
- Méthode en 3 étapes : [ÉTAPE 1], [ÉTAPE 2], [ÉTAPE 3]
- Parcours réel : [2–3 FAITS SUR LA PERSONNE]
- Résultats clients : [AVIS RÉELS AVEC PRÉNOM + CONTEXTE, ou laisse vide]
- Offre : [FORMAT, DURÉE, PRIX OU "sur demande"]
- Action : [appel découverte de 20 min]

Règles :
- Écris à la première personne, avec la voix de la personne (pas "notre équipe").
- Pas de promesse de transformation de vie, pas de "libère ton potentiel".
- Une section "Pour qui ce n'est pas fait" (2–3 lignes honnêtes).
- Photo réelle de la personne en [PHOTO : portrait au travail], pas de photo de stock.
```

## 05 · Application mobile

```text
Crée une landing page pour l'app [NOM] (iOS et Android) qui permet de [ACTION PRINCIPALE].

Infos :
- 3 écrans à montrer : public/screen1.png, screen2.png, screen3.png (ou maquettes CSS si absentes)
- Pour qui : [UTILISATEUR TYPE]
- Ce que l'app fait mieux : [1 POINT CONCRET]
- Liens stores : [APP STORE] / [PLAY STORE]

Règles :
- Hero : titre court + mockup de téléphone avec la vraie capture + badges stores officiels.
- Section qui montre l'app en 3 étapes avec les 3 écrans.
- Pas de liste de 9 fonctionnalités avec icônes : 3 maximum, avec captures.
- QR code vers le store sur desktop.
```

## 06 · Freelance ou agence

```text
Crée la landing page de [NOM], [MÉTIER] (freelance / petite agence) spécialisé en [SPÉCIALITÉ].

Fiche :
- Clients types : [SECTEURS]
- 3 projets réels : [NOM PROJET — CE QUI A ÉTÉ FAIT — RÉSULTAT], x3
- Process : [ÉTAPES]
- Contact : [WHATSAPP / E-MAIL / CALENDLY]

Règles :
- Les projets passent avant les services : captures + une ligne de contexte + un résultat.
- Services en tableau (service, ce qui est inclus, délai), pas en cartes.
- Pas de "solutions innovantes et sur mesure", pas de "passionnés".
- Formulaire court : nom, e-mail, "Parlez-moi du projet en 2 lignes".
```

## 07 · Événement

```text
Crée une landing page pour l'événement [NOM] le [DATE] à [LIEU].

Infos :
- Programme : [HEURE — ACTIVITÉ], …
- Intervenants : [NOM — RÔLE], …
- Prix : [PRIX / GRATUIT] — places : [NOMBRE]
- Inscription : [LIEN]

Règles :
- Date, lieu et bouton d'inscription visibles sans scroller.
- Programme en tableau horaire.
- Compte à rebours discret, pas de faux "plus que 3 places !" si ce n'est pas vrai.
- Bouton "Ajouter à mon agenda" (.ics).
```

## 08 · Produit e-commerce unique

```text
Crée une page produit / landing pour [PRODUIT] vendu [PRIX].

Infos :
- Ce que c'est, en une phrase : [DESCRIPTION]
- 3 détails concrets (matière, taille, origine…) : [DÉTAILS]
- Photos : public/p1.jpg, p2.jpg, p3.jpg
- Livraison et retours : [CONDITIONS RÉELLES]
- Paiement : [LIEN STRIPE / SHOPIFY]

Règles :
- Galerie en haut, prix et bouton "Acheter" à côté, frais de livraison affichés avant le clic.
- Caractéristiques en tableau.
- Avis uniquement s'ils sont réels, avec la date.
- Aucune urgence artificielle.
```

## 09 · Bot Discord ou serveur

```text
Crée une landing page pour le bot Discord [NOM] qui [FONCTION PRINCIPALE].

Infos :
- 4 commandes clés : [/commande — ce qu'elle fait], x4
- Nombre de serveurs réels : [NOMBRE ou rien]
- Lien d'invitation : [LIEN]
- Serveur support : [LIEN]

Règles :
- Hero avec une fausse fenêtre Discord en CSS qui montre une vraie commande et la réponse du bot.
- Les commandes en tableau (commande, effet, permission requise).
- Pas d'avatar de robot 3D, pas de néon violet.
- Bouton "Ajouter à Discord" + lien support.
```

## 10 · Liste d'attente ou lancement

```text
Crée une page "bientôt disponible" pour [PRODUIT] qui sort [DATE / PÉRIODE].

Infos :
- Ce que ce sera, concrètement : [DESCRIPTION]
- Pourquoi s'inscrire maintenant : [AVANTAGE RÉEL : prix de lancement, accès anticipé…]
- Formulaire : [SERVICE, ex. Formspree / Supabase]

Règles :
- Une seule section : titre, 2 phrases, champ e-mail + bouton "Être prévenu".
- Message de confirmation qui dit quand la personne recevra des nouvelles.
- Pas de compteur d'inscrits inventé.
- Mention RGPD d'une ligne sous le champ.
```

---

Fait par **[Varhex by Ȥrk Team](https://varhex.com)** · [Discord](https://discord.gg/4qRhB4c5me) · [TikTok](https://www.tiktok.com/@vertex.code.zrk)
