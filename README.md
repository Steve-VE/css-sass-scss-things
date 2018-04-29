# css-sass-scss-things
Veille du 30/04

## Background Gradient
En *_CSS_*, il est possible de placer des dégradés (linéaire ou radial) en tant que background (`background-image` plus précisément !).

Il est possible de placer plusieurs images, et donc plusieurs dégradés dans un seul background, simplement en séparant chacunes des images par une virgule. 

En jouant sur le `background-position` et le `background-size`, il est possible de faire quelques combinaisons intéressantes. Comme pour le `background-image`, on peut définir plusieurs valeurs en les séparants par une virgule, chacune de ces valeurs se rapportera alors au background correspondant.

### Liens : 
- [MDN web docs : background-image](https://developer.mozilla.org/fr/docs/Web/CSS/background-image)
- [MDN web docs : linear-gradient](https://developer.mozilla.org/fr/docs/Web/CSS/linear-gradient)
- [MDN web docs : radial-gradient](https://developer.mozilla.org/fr/docs/Web/CSS/radial-gradient)

## Clip-path
### Liens : 
- [MDN web docs : clip-path](https://developer.mozilla.org/fr/docs/Web/CSS/clip-path)

## Thèmes à l'aide des variables CSS
### Liens : 
- [HTML: data-*](https://developer.mozilla.org/fr/docs/Web/HTML/Attributs_universels/data-*)
- [MDN web docs : Les variables CSS](https://developer.mozilla.org/fr/docs/Web/CSS/Les_variables_CSS)
- [Contextual styling with custom properties](http://simurai.com/blog/2018/04/01/contextual-styling)


## Sass Map
En *_Sass_*, nous disposont d'un objet *map* qui ressemble fortement à un tableau, ou plutôt à un objet, tel qu'on a pu le voir en *PHP* ou *Javascript*, c'est-à-dire un ensemble de données contenu au sein d'une même variable et chacun nommé à l'aide d'une clé.

- ```map-get(map, key)``` : Renvoitla valeur de *key* contenu dans le tableau *map*.
- ```#{variable}``` : imprime la valeur de la variable en texte brute.
- Création d'une map : 
```CSS
$map: (
    key1: value,
    key2: value,
    ...
    keyn: value
);
```
### Liens : 
- [Using Sass Maps](https://www.sitepoint.com/using-sass-maps/)
- [SASS – Leçon 5 : les conditions et les boucles](https://www.ice-dev.com/decoupe-html-css/sass-lecon-5-les-conditions-et-les-boucles/)