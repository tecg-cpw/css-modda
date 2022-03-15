# CSS "Modda"

> CSS exercise given at HEPL

* * *

**CSS "Modda"** is an educational project, which will be used for `HTML`/`CSS` courses.

**Note:** the school where the course is given, the [HEPL](http://www.provincedeliege.be/hauteecole) from Liège, Belgium, is a french-speaking school. From this point, the instruction will be in french. Sorry.

* * *

## Modda E-Commerce

Vous trouverez dans ce dossier une page HTML nommée **index.html**. Cette page est tirée d'un template disponible[ici](http://csform.com/product/modda-e-commerce-ui-kit-free-sample-for-adobe-xd/).

Le rendu final désiré est le suivant : ![rendu final](./rendus/modda.jpg)

### Consignes

* Créer et lier le fichier **styles.css** à la page **index.html**.
* Utiliser un reset, celui d'[Eric Meyer](https://meyerweb.com/eric/tools/css/reset/) par exemple.
* En vous fiant aux rendus attendus du fichier Adobe XD, compléter la feuille de styles.
* Toutes les images à utiliser se trouvent dans le dossier **img**.
* Bon travail et bon amusement&nbsp;!


## Récuperer le reset et les polices : `reset.css`

Dans un dossier `css`, créez le fichier `reset.css`

- Se rendre sur [https://fonts.google.com/](https://fonts.google.com/) et sélectionner les polices 
	- Merriweather 
		- Light 300 
		- Light 300 Italic
	- Raleway 
		- Light 300
		- Medium 500
		- Bold 700

Dans la partie ***Use on the Web*** copiez-collez ensuite le code contenu entre les deux balises `<style>...</style>` du `@import` tout en haut de votre fichier `reset.css`.


Ensuite, rendez-vous sur le site d'Eric Meyer pour copier-coller le code juste après les lignes d'importation des polices : [https://meyerweb.com/eric/tools/css/reset/](https://meyerweb.com/eric/tools/css/reset/).


### Analyse de l'exercice

Une fois que vous avez récupérer les polices et le reset (dans cet ordre), vous pouvez ouvrir le fichier Adobe XD et analyser le contenu.

Vous remarquerez que le contenu est dans la famille de police ***Merriweather*** titres et les liens dans la police ***Raleway***.

Vous pouvez donc cibler appliquer le css correspondant à ces différents éléments.

* * *

### Outils

- [Comment masquer un élément visuellement ?](https://css-tricks.com/places-its-tempting-to-use-display-none-but-dont/)
- [Comment importer une typo avec @font-face ?](https://developer.mozilla.org/fr/docs/Web/CSS/@font-face)
- Comment utiliser adobe XD ? (vidéo à venir) 
- En attendant, si vous avez besoin d'aide pour utiliser Adobe XD, vous pouvez chercher des solutions dans la [documentation officielle](https://helpx.adobe.com/be_fr/xd/tutorials.html) ou me poser des questions sur Slack.


Adaptation et intégration par & [François Parmentier](https://github.com/fprms).
