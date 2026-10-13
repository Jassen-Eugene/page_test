# page_test

Pages statiques HTTPS (GitHub Pages) où Stripe renvoie un interprète après son inscription Stripe Connect.

- `retour.html` : inscription terminée (`STRIPE_RETURN_URL`)
- `expire.html` : lien expiré ou déjà utilisé (`STRIPE_REFRESH_URL`)

**À CHANGER** : ce dépôt et ce nom (`page_test`) sont provisoires. Remplacez-les par une vraie page du site de
l'entreprise, puis mettez à jour `STRIPE_RETURN_URL` et `STRIPE_REFRESH_URL` dans `ready-call/backend/.env`.
Le dépôt est public (nécessaire à GitHub Pages gratuit) : n'y mettez jamais de secret.
