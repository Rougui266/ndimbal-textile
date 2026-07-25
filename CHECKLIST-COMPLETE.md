# Checklist TP1 à TP8

Notes pour cocher les points de contrôle du support de cours en m'appuyant sur ce projet.

## TP1 - head
- title 50-60 caractères, mot-clé + marque : ok (index.html)
- meta description avec mot-clé + verbe d'action : ok
- meta robots noindex sur la page de recherche interne : recherche.html
- canonical sur toutes les pages : ok

## TP2 - body
- un seul h1 par page : ok
- pas de saut de niveau hx : ok (visiter-casamance.html : h1 > h2 > h3 > h2 > h3)
- alt descriptifs sans bourrage de mots-clés : ok
- header/nav/main/article/footer à la place des div : ok

## TP3 - JSON-LD
- à valider avec le Rich Results Test de Google (coller le script de index.html)
- type Product cohérent avec le contenu de la page
- prix/note dans le JSON = prix/note affichés sur la page

## TP4 - robots.txt / sitemap
- robots.txt à la racine
- admin/panier/recherche/factures bloqués, blog autorisé
- sitemap.xml valide, déclaré dans robots.txt
- reste à soumettre dans Search Console une fois en ligne (TP8)

## TP5 - .htaccess
- force HTTPS puis www
- redirection 301 d'une ancienne page
- 404 personnalisée
- ne fonctionne qu'une fois déployé sur un vrai serveur Apache, rien à tester en local

## TP6 - maillage interne
- pas d'ancre du type "cliquez ici"
- lien payé (FilDakar) en rel="sponsored"
- liens vers avis externes en rel="ugc"

## TP7 / TP8
À faire une fois le site réellement déployé (voir TP7-DEPLOIEMENT.md et TP8-SEARCH-CONSOLE.md).
