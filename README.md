# Site Web Statique avec HTML, CSS et Markdown (Pandoc)

Ce projet est un site web statique créé à partir de fichiers Markdown, convertis en HTML grâce à l’outil **Pandoc**.  
Le style du site est défini à l’aide d’une feuille de style CSS personnalisée.

## Contenu

- **Markdown (.md)** : pour rédiger le contenu de manière simple et lisible.
- **HTML** : généré automatiquement par Pandoc.
- **CSS** : pour la mise en forme visuelle du site.

## Objectif

Fournir un site statique facile à maintenir, sans CMS, avec un contenu clair écrit en Markdown et un rendu HTML propre.

## Génération

Les fichiers `.md` sont convertis en `.html` avec Pandoc à l’aide d’une commande du type :

```bash
pandoc page.md -o page.html --css=style.css
