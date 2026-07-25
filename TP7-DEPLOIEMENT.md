# TP7 - Mise en ligne

Le site est un simple site statique HTML/CSS, donc j'ai choisi GitHub Pages
(gratuit, pas besoin d'hébergement payant).

## Étapes suivies

```
git init
git add .
git commit -m "Version initiale du site Ndimbal Textile"
git branch -M main
git remote add origin https://github.com/Rougui266/ndimbal-textile.git
git push -u origin main
```

Puis sur GitHub : Settings > Pages > Source = branche main, dossier /root.

Site en ligne : https://rougui266.github.io/ndimbal-textile/

## Remarque sur le .htaccess

Le fichier .htaccess (TP5) ne fonctionne que sur un serveur Apache. GitHub
Pages force déjà HTTPS de son côté, donc ce n'est pas bloquant pour ce TP,
mais à savoir si on utilisait un vrai hébergement Apache (OVH, Hostinger...).

## Configuration DNS (si on avait un vrai nom de domaine)

| Type | Nom | Valeur |
|---|---|---|
| A | @ | IP du serveur |
| CNAME | www | domaine ou IP |
| TXT | @ | vérification Search Console |
