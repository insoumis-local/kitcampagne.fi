---
layout: article
title: Mettre son blog Wordpress aux couleurs de la France Insoumise
contentdescription:
icon: wordpress-theme.svg
sortinglabel: wordpress-l2
--- 


## Installer le thème

Afin d’installer le thème « FI 2017 » dans une installation WordPress que vous avez déjà, il est nécessaire d’utiliser l’extension « github-updater ». Elle vous permettra aussi de mettre à jour le thème à l’avenir.

### Installation de l’extension

Téléchargez l’archive de l'extension au format « .zip » <https://framadrop.org/r/kE-TNj8aZO#NS5tMI2qqpCkkj0xyVkeZrpRV6uPYb9bm8rrsyQppvE=>

![image](/assets/images/screenshots/wp-zip.jpg)

Rendez-vous dans  « Extensions > Ajouter », puis « Mettre une extension en ligne ». Sélectionnez l’archive .zip, puis cliquez sur installer.

![image](/assets/images/screenshots/wp-upload.jpg)

![image](/assets/images/screenshots/wp-choose.jpg)

Activez l’extension. *En cas de problème, consultez la [documentation de l’extension (EN)](https://github.com/afragen/github-updater/wiki) avant de nous contacter.*

![image](/assets/images/screenshots/wp-activate.jpg)

### Installation du thème

Dans la liste de vos extensions, cliquez sur « réglages » de l’extension « github-updater ». Allez dans « installer le thème ». Dans « Thème URI », copiez cette adresse : <https://github.com/insoumis-local/wordpress-template-legislatives>. Ne touchez pas au reste et cliquez sur « Installer le thème ».

![image](/assets/images/screenshots/wp-install.jpg)

Dans « Apparence > Thème », activez le thème « FI 2017 ».

![image](/assets/images/screenshots/wp-theme.jpg)

### Mises à jour du thème

Se rendre dans « Apparence > Thèmes » et cliquer sur « Mettre à jour automatiquement ».

![Mise à jour du thème](/assets/images/screenshots/wp-majtheme.png)

WordPress est censé vous notifier lors de la disponibilité d’une mise à jour. Si ce n'est pas le cas, vous pouvez vous rendre dans « Réglages > GitHub Updater » et cliquer sur « Actualiser le cache », puis revenir dans « Apparence > Thèmes ». La notification devrait apparaître. En cas de doute, vérifiez que le numéro de version corresponde à celui indiqué ici : <https://github.com/insoumis-local/wordpress-template-legislatives/blob/master/style.css>. 

*Si vous utilisez notre service d’hébergement générique, le thème sera mis à jour automatiquement par nos soins (indisponible pour le moment).*


## Créer du contenu

**Pour modifier l'en-tête de la page d’accueil** : Dans « Apparence > Personnaliser > FI 2017 HOME », il est possible de définir les infos de base pour afficher l'en-tête d’accueil. Cet en-tête ne s’affiche que sur la page d’accueil. Vous pourrez alors choisir une image, indiquer le nom des candidat·e·s, la circonscription ainsi que les villes de la circonscription. Pour désactiver cet en-tête, il suffit de décocher la case « activer l’en-tête ». 

Le template de contenu « Blue card only » correspond à la page d’accueil de <https://lafranceinsoumise.fr>.
 
Le template de contenu « Home » permet d’utiliser l’image mise en avant comme fond et le texte comme contenu de la barre positionnée sur l’image. Il permet donc de faire une page d’accueil différente du modèle fourni par l'en-tête.

Il y a trois zones pouvant accueillir des *widgets* :

- **Barre latérale** : la barre latérale droite sur les pages qui en disposent.
- **Zone bleue avant le pied de page** : la zone bleue en bas de page avant le pied de page.
- **Pied de page** : la zone tout en bas de page.

Il y a quatre zones pouvant accueillir des menus :

- **Menu blanc** : barre blanche à droite du logo sur toutes les pages.
- **Menu rouge** : barre orange sous la « Navigation Primaire ».
- **Zone bleue uniquement - Gauche** : espace à gauche de la zone bleue sur le template « Zone bleue uniquement ».
- **Zone bleue uniquement - Droite** : espace à droite de la zone bleue sur le template « Zone bleue uniquement ».
