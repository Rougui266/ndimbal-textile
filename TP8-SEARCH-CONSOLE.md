# TP8 - Search Console

À faire sur search.google.com/search-console une fois le site en ligne.

1. Ajouter une propriété (type domaine ou préfixe URL)
2. Valider la propriété
3. Soumettre le sitemap : https://rougui266.github.io/ndimbal-textile/sitemap.xml
4. Inspection de l'URL sur la page d'accueil, demander l'indexation
5. Après quelques jours, vérifier le rapport "Pages"

## Vérifications en ligne de commande

```
curl -I https://rougui266.github.io/ndimbal-textile/robots.txt
curl -s https://rougui266.github.io/ndimbal-textile/ | grep -i "robots"
```

## À vérifier

- propriété validée
- sitemap accepté sans erreur
- page d'accueil indexée
- pas d'erreur de contenu dupliqué

Compte-rendu : captures d'écran de chaque étape ci-dessus.
