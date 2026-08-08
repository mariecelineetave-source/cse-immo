# cse.immo — consignes pour les sessions automatisées

**CE = comité d'entreprise** (aujourd'hui CSE).

Domaine : **cse.immo** (domaine racine, chez Gandi), et lui seul.

Le site a brièvement vécu sur `cse.idf.immo` le 7 août 2026. Ce sous-domaine a
été **définitivement supprimé** par Marie-Céline, sans redirection : décision
assumée, l'adresse n'a jamais été diffusée. Ne jamais la réintroduire, ne jamais
proposer de la rétablir.

Il n'y a **pas d'adresse en `www`** : `www.cse.immo` n'existe pas et
Marie-Céline n'en veut pas. Ne pas la remettre dans les liens, les exemples ni
les consignes.

Site de proposition commerciale de Marie-Céline Etave aux **comités d'entreprise,
partout en France**. Objectif unique : convaincre les élus d'un CSE de la
référencer auprès de leurs salariés, pour la **vente** et la **recherche** de
leur bien immobilier **personnel** (pas le patrimoine de l'entreprise).

⚠️ **Périmètre géographique — deux régimes distincts, depuis le 7 août 2026 :**

| Prestation | Périmètre | Qui fait le travail |
|---|---|---|
| Mandat de vente | **Toute la France** | Marie-Céline en Île-de-France ; ailleurs, un confrère qu'elle choisit, elle restant l'interlocutrice du salarié |
| Mandat de recherche | **Toute la France** | idem |
| Expertise en valeur vénale | **Île-de-France uniquement** | Marie-Céline personnellement — un rapport engage celle qui le signe, il n'est jamais délégué |

Ne jamais étendre l'expertise au national, ni restreindre la vente et la
recherche à l'Île-de-France. Ne jamais laisser croire que Marie-Céline se
déplace elle-même partout en France : le réseau de confrères est assumé et
expliqué, c'est ce qui rend la promesse crédible.

Le domaine `cse.immo` ne porte aucune marque régionale : c'est volontaire,
l'offre de vente et de recherche étant nationale.

L'offre nationale ouvre un argument propre aux **entreprises multi-sites** : un
accord avec le comité couvre tous les établissements, pas seulement le siège.
C'est développé dans la FAQ, à conserver.

L'offre faite aux salariés des entreprises partenaires :

| Prestation | Tarif |
|---|---|
| **Mandat de vente** (salarié qui vend son bien personnel) | **3 %** du prix de vente, à la charge du vendeur, dus à la signature de l'acte authentique |
| **Mandat de recherche** (salarié qui cherche un bien) | **3 %** du prix d'acquisition, à la charge du salarié acquéreur, dus uniquement si l'acquisition aboutit |
| Expertise en valeur vénale | **990 €** au lieu de 1 190 € |

**Le 3 % est fixe, quel que soit le prix du bien**, et aucun montant plancher
n'est appliqué (confirmé par Marie-Céline). Ne jamais introduire de plancher, de
palier ni de barème dégressif dans les textes. Pas de frais de dossier, de photos
ni de publicité ; rien n'est dû si l'opération ne se fait pas. Le site doit
toujours nommer explicitement **les deux mandats** — de vente et de recherche —
et non parler vaguement d'« accompagnement ».

**Règle de vocabulaire (demande expresse de Marie-Céline) : ne pas écrire
« minimum » ni « sans minimum » dans le texte visible du site.** La promesse se
formule toujours en positif : « sans mauvaise surprise », « quel que soit le prix
du bien », « rien ne s'ajoute en cours de route ». Le mot « minimum » attire
l'attention sur une pratique du métier qu'il vaut mieux ne pas évoquer ; la
formule retenue dit la même chose sans planter l'idée.

Le CSE, lui, ne paie rien, ne perçoit rien, ne signe aucun engagement financier
et n'a rien à gérer. C'est l'argument central du site : **il faut donner envie
aux élus, en levant d'abord la crainte que ça les engage.**

## Positionnement par rapport aux autres sites

- **antony.immo** — transaction locale à Antony (92), actu immo quotidienne,
  estimateur en ligne, expertise à 1 190 €. Grand public.
- **cse.immo** — offre comités d'entreprise, sur toute la France. Cible :
  les élus de CSE d'abord, les salariés ensuite.

Ne pas mélanger : pas d'actu immo ni d'estimateur de prix ici, pas de contenu
« comité d'entreprise » sur antony.immo.

## Structure

- `index.html` — la proposition aux comités d'entreprise (page principale,
  CSS et JS inclus). Sections : héros, chiffres clés, pourquoi cet avantage,
  simulateur d'économie, l'offre en trois volets, **« Partout en France » (qui
  fait le travail, et pourquoi Marie-Céline reste l'interlocutrice)**, ce que
  reçoit le salarié, rôle du CSE (ce qu'il fait / ne fait pas), mise en place, bande
  expertise 990 €, l'interlocutrice, FAQ des élus, formulaire de demande.
- `expertise.html` — l'expertise en valeur vénale, tarif CSE à 990 €.
- `mentions-legales.html` — mentions légales, RGPD, portée du simulateur et de
  l'offre CSE.
- `CNAME` — domaine personnalisé (`cse.immo`), ne pas toucher.
- `sitemap.xml` / `robots.txt` — référencement. **Quand le contenu d'une page
  publiée change, mettre sa balise `<lastmod>` à la date du jour (AAAA-MM-JJ).**

## Règles de contenu

1. **Ne jamais affirmer un « taux moyen du marché »** sans source vérifiable.
   Le simulateur laisse volontairement le visiteur choisir le taux de
   comparaison (4 à 7 %) ; seul le 3 % est présenté comme un engagement ferme.
   Ne pas remplacer ce choix par un chiffre asséné.
2. **Aucun chiffre ni référence juridique inventés.** Sans source vérifiée, on
   n'écrit rien.
3. **Ne jamais promettre un résultat** (« vente garantie », « valeur acceptée
   par le fisc »). On décrit la méthode et la portée, pas une garantie.
4. **Ne rien écrire qui laisse croire que le CSE perçoit quelque chose.**
   L'absence totale de rétrocession est un argument, et c'est vrai : le garder
   explicite.
5. **Tarifs** : 3 % et 990 €. Ne les modifier que sur demande explicite de
   Marie-Céline.
6. **Aucune donnée personnelle dans le dépôt** (le dépôt est public). Les
   formulaires restent en `mailto:` ; rien n'est stocké côté site.
7. **Ne jamais contacter qui que ce soit** ; ne jamais collecter de coordonnées
   d'élus ou d'entreprises dans le dépôt.
8. Avant tout commit : vérifier l'équilibre des balises HTML des pages modifiées
   (python `html.parser`).

## Publication

- Toute modification attend la validation explicite de Marie-Céline (« publie »).
- Aucune rubrique de ce site n'est en publication automatique.

## Divers

- Tout en français. Commits clairs en français.
- Le proxy réseau bloque le fetch HTTP direct (curl/WebFetch) : utiliser
  WebSearch uniquement ; un échec curl ne signifie PAS que le site est en panne.
- Push : `git push -u origin <branche>` ; en cas d'erreur réseau, retenter
  jusqu'à 4 fois (2, 4, 8, 16 s).

## Points tranchés par Marie-Céline

- **Honoraires** : 3 % sur le mandat de vente comme sur le mandat de recherche,
  taux fixe, sans montant plancher. Confirmé le 7 août 2026.
- **Périmètre** : vente et recherche au national, expertise en Île-de-France
  seulement. Confirmé le 7 août 2026.
- **Nom de domaine** : `cse.immo` seul, décidé le 7 août 2026 en même temps que
  le passage au national. `cse.idf.immo` supprimé sans redirection ; pas de
  `www`. Décisions prises et confirmées par Marie-Céline.

## Contact — règle stricte

- **Adresse e-mail : `contact@cse.immo` uniquement.** Ne jamais remettre
  `contact@antony.immo`, `contact@idf.immo` ni `contact@cse.idf.immo` : ces
  adresses appartiennent à d'autres sites ou n'existent pas.
  Domaine géré chez Gandi, MX `spool.mail.gandi.net` déjà en place.
- **Téléphone : 06 60 98 92 92** — le même que sur antony.immo.

## Vocabulaire

Dire **« comité d'entreprise »** dans le texte visible, et **« CSE »** (comité
social et économique) seulement en rappel : première mention du héros, section
« Rôle du comité », balises meta et données structurées (les élus cherchent
« CSE » sur Google). Ne pas truffer les pages de sigles.
