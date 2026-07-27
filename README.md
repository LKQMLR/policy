# ateqo-policy

Documents légaux publics de l'application **ATEQO** :

- **Politique de confidentialité** : [https://ateqo.fr/ateqo-policy/](https://ateqo.fr/ateqo-policy/)

## Structure du repo

- `index.html` — politique de confidentialité, version publique stylée (RGPD-compliant, en français)
- `index.en.html` — même document, version anglaise
- `terms.html` — conditions générales d'utilisation
- `support.html` — page de support : FAQ, dépannage, contact
- `confirmed.html` — page d'arrivée après confirmation d'e-mail à l'inscription
- `delete-account.html` — procédure de suppression de compte (exigence Google Play)

URLs à fournir aux stores lors de la soumission :
- **Privacy Policy URL** : https://ateqo.fr/ateqo-policy/
- **Support URL** : https://ateqo.fr/ateqo-policy/support.html

Les liens internes sont volontairement écrits en chemins absolus depuis la
racine (`/ateqo-policy/...`), et non en URL complètes : ils restent ainsi
valides quel que soit le domaine servant le site.

## Ancien nom du repo

Ce dépôt s'appelait `cargoV1-policy` et était publié sur `/cargoV1-policy/`.
GitHub ne redirige pas les URL des sites Pages de projet après un renommage.
Des pages relais ont donc été placées dans le dépôt `LKQMLR.github.io`, sous
`cargoV1-policy/`, pour maintenir les anciennes URL vivantes. Voir le README de
ce dossier avant toute suppression.

L'ancienne URL de confirmation d'e-mail doit rester dans la liste blanche
**Supabase → Authentication → URL Configuration → Redirect URLs** aussi
longtemps que des versions antérieures de l'app circulent.

## Mise à jour

Toute modification de la politique :
1. Édite `index.html`
2. Met à jour la version + date « En vigueur depuis »
3. Commit + push sur `main`
4. GitHub Pages déploie automatiquement en ~1 minute

L'historique des versions est tracké dans les commits Git.

## Repo lié

Code source de l'application : [github.com/LKQMLR/cargoV1](https://github.com/LKQMLR/cargoV1) (privé).

L'inventaire complet des données (`DATA_INVENTORY.md`) est dans ce repo privé, sert
de source pour les formulaires Apple Privacy Nutrition Labels + Google Play Data
Safety form au moment de la soumission.
