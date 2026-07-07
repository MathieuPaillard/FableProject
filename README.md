# FactureLibre

Projet fable qui va consister à créer une source de revenu même minime pour
déclencher potentiellement un intérêt grandissant pour cette technologie.

## Le produit

**FactureLibre** — générateur gratuit de **factures et devis pour
auto-entrepreneurs et micro-entreprises** françaises.

- 100 % côté client : aucune donnée n'est envoyée sur un serveur, tout reste
  dans le navigateur (localStorage).
- Mentions légales obligatoires incluses automatiquement : TVA non applicable
  (art. 293 B du CGI), pénalités de retard (art. L441-10), indemnité
  forfaitaire de 40 € (art. D441-5), « Bon pour accord » sur les devis.
- Calcul automatique des totaux, avec ou sans TVA (20 %).
- Export PDF via l'impression du navigateur (mise en page dédiée).
- **Export Factur-X** (XML CII, profil BASIC) : le format de la réforme de la
  facturation électronique 2026-2027, généré côté client.
- **Historique local** : documents enregistrés dans le navigateur,
  numérotation automatique continue, carnet de clients, duplication,
  sauvegarde/restauration par fichier JSON — toujours sans compte ni serveur.
- **Catalogue de prestations** : libellés et prix unitaires mémorisés
  automatiquement, suggérés pendant la frappe (autocomplétion), prix
  pré-rempli pour les prestations connues.
- Zéro dépendance, un seul fichier : [`index.html`](index.html).
- Coût d'hébergement : **0 €** (GitHub Pages).

## Essayer en local

Ouvrir `index.html` dans un navigateur. C'est tout.

## Mettre en ligne

GitHub → Settings → Pages → « Deploy from a branch » → `main` / `/ (root)`.

## Gagner de l'argent avec

Le plan complet, étape par étape (donations, affiliation, SEO, version Pro),
est dans [`MONETISATION.md`](MONETISATION.md).

## Avertissement

Cet outil ne constitue pas un conseil juridique ou comptable. Vérifiez vos
obligations sur [entreprendre.service-public.fr](https://entreprendre.service-public.fr).
