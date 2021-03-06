# Apprendre Le Web  : 

### Notes synthétiques sur le développement web

Basées sur [Apprendre le web de MDN](https://developer.mozilla.org/fr/Apprendre).


Outils utilisés :
* [Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)


## Commencer avec le Web

### De quels outils ai-je besoin tout de suite ?

* Un ordinateur et OS Linux ([Ubuntu](https://www.ubuntu-fr.org/) ou [Linux Mint](https://www.linuxmint.com/))
* Un éditeur de texte ([Atom](https://atom.io/))
* Un navigateur web ([Firefox](https://www.mozilla.org/fr/firefox/new/), [Chrome](https://www.google.com/chrome/browser/desktop/index.html) ou [Opera](http://www.opera.com/fr))
* Un éditeur graphique ([Gimp](http://www.gimp.org/))
* Un gestionnaire de versions ([Github](https://github.com/)
* Un système d'automatisation ([Grunt](http://gruntjs.com/))

### Commençons par le commencement : planifier !

1. Réfléchir et se poser des questions :
  * De quoi parle votre site web ? Choisir une thématique !
  * Quelles informations allez-vous présenter sur le sujet ? Penser contenu !
  * De quoi a l'air votre site web ? Penser design !

2. Esquisser le concept sur papier !
3. Choisir les composants :
  * Texte : à rédiger !
  * Couleur du thème : [Code couleur](http://www.code-couleur.com/index.html)
  * Images : [Freepik](http://www.freepik.com/), [Freeimages](http://fr.freeimages.com/)
  * Police : [Google Fonts](https://fonts.google.com  a/)

### Où placer votre site web sur votre ordinateur ?

Créer un dossier `projets-web` et un sous-dossier `site-web` quelque part dans votre répertire home.

### Quelle structure mettre en place pour votre site web ?

1. Un fichier index.html
2. Un dossier images
3. Un dossier styles
4. Un dossier scripts

##  Les bases de HTML

Hypertext Markup Language (HTML), c'est un langage de balises utilisé pour structurer le contenu d'une page web et lui fournir une signification et un but.

### Anatomie d'un élément HTML

<img  alt="Anatomie d'un élément HTML" src="https://github.com/CompuTux/ApprendreLeWeb/blob/master/images/html-tag.gif"/>

Il est possible d'imbriquer des éléments et certains éléments sont vides.

### Anatomie d'un document HTML

Squelette HTML5 basique :

```html
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <title>Ma page HTML5</title>
  </head>
  <body>
    
  </body>
</html>
```

### Structurer le texte

HTML contient des éléments pour 6 niveaux de titres : ```<h1>–<h6>```.

Les éléments ```<p>``` sont utilisés pour contenir des paragraphes de texte.

Deux types de liste :

Les listes non-ordonnées ```<ul>``` et les listes ordonnées ```<ol>```.
Chaque élément d'une liste est balisé avec un élément ```<li>```.

Exemple de lien : ```<a href="https://www.mozilla.org/fr/about/manifesto/">Manifeste Mozilla</a>```.
