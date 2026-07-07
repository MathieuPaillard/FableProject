# Plan de monétisation — FactureLibre

Objectif du projet (cf. README) : générer une source de revenu, même minime.
Ce document décrit **les étapes concrètes, dans l'ordre**, pour y parvenir avec
l'outil livré dans ce dépôt. Coût de fonctionnement : **0 €**.

## Pourquoi ce produit ?

- « facture auto entrepreneur », « modèle facture auto entrepreneur »,
  « générateur de facture gratuit » sont des recherches Google massives et
  récurrentes en France (des dizaines de milliers de recherches par mois).
- Le public (auto-entrepreneurs, freelances) est nombreux, renouvelé chaque
  année, et cherche des outils **gratuits et simples**.
- L'argument « vos données ne quittent jamais votre navigateur » est un vrai
  différenciateur face aux concurrents qui exigent une inscription.

## Étape 1 — Mise en ligne gratuite (15 minutes)

1. Fusionner ce travail dans la branche `main`.
2. Sur GitHub : **Settings → Pages → Source : Deploy from a branch →
   Branch : `main` / dossier `/ (root)`**.
3. Le site est en ligne à `https://<votre-compte>.github.io/FableProject/`.
4. (Recommandé, ~8 €/an) Acheter un nom de domaine du type `facturelibre.fr`
   ou similaire et le brancher sur GitHub Pages (Settings → Pages →
   Custom domain). Un domaine propre est quasi indispensable pour le
   référencement Google.

## Étape 2 — Premier canal de revenu : la donation ✅ FAIT

Compte Ko-fi créé et branché sur le site : le bloc « soutenir le projet »
de `index.html` pointe vers https://ko-fi.com/mathieupaillard (paiements
reçus via PayPal). Revenu attendu : faible au début, mais réel dès qu'il y a
du trafic — c'est le « premier euro » le plus rapide.

## Étape 3 — Affiliation (le vrai potentiel de revenu)

Les visiteurs de cet outil sont **exactement** la cible des logiciels de
comptabilité/facturation payants, qui rémunèrent bien l'apport de clients :

| Programme | Type | Commission typique |
|---|---|---|
| Shine (banque pro en ligne) | parrainage/affiliation | prime par compte ouvert |
| Qonto (banque pro) | affiliation | prime par compte ouvert |
| Freebe, Abby, Indy (compta auto-entrepreneur) | affiliation | % ou prime par abonnement |
| Amazon Partenaires (livres « créer sa micro-entreprise ») | affiliation | ~3-5 % |

Mise en œuvre : s'inscrire aux programmes (souvent via Affilae, Effinity ou
directement sur le site du service), puis ajouter dans la section SEO de
`index.html` un encart honnête du type « Pour aller plus loin : un logiciel
qui déclare l'URSSAF à votre place ». **Une seule conversion peut rapporter
50-150 €.** C'est le canal au meilleur ratio effort/revenu pour ce type d'outil.

## Étape 4 — Trafic (la condition de tout le reste)

Sans visiteurs, pas de revenu. Actions gratuites, par ordre d'efficacité :

1. **SEO** : la page contient déjà du contenu optimisé. Ajouter ensuite des
   pages satellites (`/mentions-obligatoires-facture.html`,
   `/modele-devis-auto-entrepreneur.html`…) qui pointent vers l'outil.
2. **Forums et groupes** : répondre aux questions « comment faire une
   facture ? » sur les groupes Facebook d'auto-entrepreneurs, r/vosfinances,
   forums de freelances — en donnant le lien quand c'est pertinent.
3. **Annuaire d'outils gratuits** : soumettre le site à des annuaires
   (ProductHunt, alternativeto, annuaires d'outils pour indépendants).
4. Publier le dépôt en open source avec un bon README — GitHub apporte aussi
   du trafic et de la crédibilité.

## Étape 5 — Plus tard, si le trafic décolle

- **Version Pro** (paiement unique 9-19 € via Gumroad/Lemon Squeezy) :
  logo sur la facture, modèles de couleurs, numérotation automatique,
  export de l'historique. Le cœur reste gratuit.
- **Publicité discrète** (ex. Carbon Ads) une fois > ~10 000 pages vues/mois.

## À savoir (honnêteté oblige)

- Les revenus d'affiliation/donations doivent être déclarés (le statut
  auto-entrepreneur convient très bien — le sujet même de l'outil !).
- Le levier n'est pas le code (il est terminé) mais la **distribution** :
  quelques heures par semaine sur l'étape 4 font toute la différence.
- Échelle de temps réaliste : premières visites en quelques jours via les
  forums, premier revenu (donation ou affiliation) en quelques semaines,
  trafic SEO significatif en 3-6 mois.
