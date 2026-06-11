# Encor'Utile — site vitrine + boutique

Site web complet du projet de création d'entreprise **Encor'Utile** (BUT GEA).
Concept anti-gaspillage : revente d'invendus **neufs non alimentaires** des marques,
en paniers surprise ou en achat classique, à retirer chez un commerçant partenaire.

> Slogan : « Les invendus qu'on veut tous » · Lancement 1ᵉʳ janvier 2026 · conforme loi AGEC

## Contenu

Le site tient dans **un seul fichier** : `index.html` (HTML + CSS + JavaScript, aucune dépendance, aucune installation).
Le logo `logo.png` l'accompagne.

### Côté Particuliers (perso)
- **Accueil** — hero, double offre surprise/visible, fonctionnement, catégories, parrainage
- **Boutique** — grille filtrable (les vendeurs sponsorisés apparaissent en premier, avec mention transparente)
- **Paniers surprise** — les 4 offres PPS / PPSS / GPS / GPSS
- **Marques à la une** — vendeurs partenaires mis en avant (référencement payant, signalé clairement comme Google le fait)
- **Parrainage** — système 5 € / 5 €
- **Concept** — modèle économique, répartition 70 % marque / 30 % Encor'Utile, équipe
- **Panier** — ajout à l'unité, quantités, total, économie « prix vérité », retrait en magasin

### Côté Pros & Marques
- **Espace pros** — présentation de l'offre marque
- **Vendre mes invendus** — devenir fournisseur (0 € de frais, 70 % reversés)
- **Booster ma visibilité** — forfaits de mise en avant (Standard 0 € / Visible 49 € / Premium 129 €)
- **Influenceurs** — agence d'affiliation intégrée, commissions par paliers (8 % / 12 % / 15 %), codes uniques
- **Devenir créateur** — inscription influenceur

Le sélecteur **Particuliers / Pros & Marques** en haut bascule entre les deux univers.

## Tester en local

Double-cliquez simplement sur `index.html` : il s'ouvre dans n'importe quel navigateur.
Aucun serveur n'est nécessaire.

## Héberger gratuitement sur GitHub Pages

1. Créez un dépôt GitHub (par ex. `encor-utile`).
2. Déposez **`index.html`** et **`logo.png`** à la racine du dépôt.
3. Dans le dépôt : **Settings → Pages**.
4. Sous *Build and deployment* → *Source*, choisissez **Deploy from a branch**,
   branche `main`, dossier `/ (root)`, puis **Save**.
5. Au bout d'une minute, le site est en ligne à l'adresse :
   `https://<votre-pseudo>.github.io/encor-utile/`

## Charte graphique

Couleurs reprises du logo :

| Rôle | Couleur | Hex |
|------|---------|-----|
| Teal (principal) | bleu-vert | `#1E7B95` |
| Bleu marine | titres / contraste | `#0D294E` |
| Blanc | fonds | `#FFFFFF` |
| Ambre | accent « surprise / cadeau » | `#F2A63B` |

Typographies : Bricolage Grotesque (titres), Inter (texte), Space Mono (prix / étiquettes).

## Pour aller plus loin (optionnel)

- **Vraies photos produits** : les visuels actuels sont des illustrations vectorielles.
  Remplacez-les par de vraies photos en éditant le tableau `PRODUCTS` dans `index.html`
  (champ image de chaque produit).
- **Panier persistant** : une fois le site hébergé, vous pouvez stocker le panier dans le
  navigateur avec `localStorage` pour qu'il survive au rafraîchissement de la page.
- **Paiement réel** : brancher un prestataire (Stripe, etc.) sur l'étape de retrait/commande.

---

*Projet étudiant fictif — BUT GEA, Université Gustave Eiffel (IUT de Marne-la-Vallée).*
*Porteurs : Elsa Jubeaux, Jovenca Lumeus, Célia Chestier, Keshawashen Nagendran, Aure Salibur.*
