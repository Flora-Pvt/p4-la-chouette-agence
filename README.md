# La chouette agence

Ce dépôt héberge le site de la chouette agence après que j'ai apporté des améliorations sur son SEO, son accessibilité, sa vitesse et ses bonnes pratiques.
Ce projet a été réalisé dans le cadre de la formation de développeur web d'Open Classrooms (OC) en août 2020, grâce à des fichiers fournis par OC.

Lighthouse nous a permis de tester le site. Tout d'abord les résultats affichés par Lighthouse étaient les suivants :

![premiers resultats](https://raw.githubusercontent.com/Flora-Pvt/p4-la-chouette-agence/master/img/startingwebsiteindexSC.png)

Puis après les changements ils affichent : 

![derniers resultats](https://raw.githubusercontent.com/Flora-Pvt/p4-la-chouette-agence/master/img/startingwebsiteindexSC-9label.png)

## Les changements apportés 

### SEO
- Ajout du titre et de la description dans la balise `<head>`.
- Remplacer des images par du texte lorsque cela s'y prête.
- Changement du format et diminution de la taille des images. On passe d'une taille de 7,64 MB à 198 KB.
- Les mots cachés et les liens abusifs sont supprimés.
- Correction de la description des images.
- Pour respecter l'affichage mobile, le texte passe à 12px minimum et liens 48px/48px
minimum.
- Les fichiers javascript et CSS sont minifiés et différés pour les fichiers javascript.

### Accessiblité
- Changement de la langue en indiquant fr dans le html.
- Ajout des titres h2 avant les titres h3.
- Les préconisations pour le contraste sont maintenant suivies.
- Focus rendu apparent.
- Les balises `<label>` sont rattachées aux balises `<input>` correspondantes et les
aria-label nécessaires sont rajoutées.


    

