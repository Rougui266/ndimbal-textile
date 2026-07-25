# Ndimbal Textile — TP Référencement (SEO)

Projet réalisé dans le cadre du cours de Référencement et mise en ligne de
sites Web (M. Fallou NDIAYE). Il s'agit d'une petite boutique de tissus wax
avec un blog, utilisée comme support pour appliquer les 8 TP du cours.

## Ouvrir le projet

1. Ouvrir le dossier dans VS Code.
2. Installer l'extension Live Server si besoin.
3. Clic droit sur `index.html` → "Ouvrir avec Live Server".

Le fichier `.htaccess` (TP5) ne s'applique que sur un vrai serveur Apache,
donc il ne se passe rien de visible avec Live Server en local, ce qui est
normal.

## Où se trouve chaque TP

| TP | Sujet | Fichier(s) |
|---|---|---|
| TP1 | `<head>` (title, meta description, canonical, robots) | `index.html`, `recherche.html` |
| TP2 | Structure `<body>` (hx, alt, HTML5) | `index.html`, `blog/visiter-casamance.html` |
| TP3 | JSON-LD (Product) | `index.html` |
| TP4 | robots.txt / sitemap.xml | `robots.txt`, `sitemap.xml` |
| TP5 | .htaccess | `.htaccess`, `404.html` |
| TP6 | Maillage interne, rel | sections "À lire aussi" |
| TP7 | Déploiement | `TP7-DEPLOIEMENT.md` |
| TP8 | Search Console | `TP8-SEARCH-CONSOLE.md` |

## Arborescence

```
seo-tp-project/
├── index.html
├── recherche.html
├── 404.html
├── robots.txt
├── sitemap.xml
├── .htaccess
├── TP7-DEPLOIEMENT.md
├── TP8-SEARCH-CONSOLE.md
├── css/style.css
├── blog/
│   ├── visiter-casamance.html
│   ├── wax-tendances-2025.html
│   └── guide-livraison-dakar.html
└── img/
    ├── logo.jpg
    ├── wax-premium.jpg
    ├── casamance.jpg
    ├── wax-tendances.jpg
    └── livraison-dakar.jpg
