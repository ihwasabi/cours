
# Memo HTML

Dans ce memo tu verras les bases des balises du langage de programmation "HTML5"



## Sommaire

- [`Les Balises`](#Les Balises)
  - [`Baliser le texte`](#Baliser le texte)
    - [`Les titres`](#Les titres)
    - [`Les paragraphes`](#Les paragraphes)
    - [`Les listes`](#Les listes)
    - [`Les liens`](#Les liens)
  - [`Balise d'Images`](#Balise d'Images)

* [Message de fin](#Message de fin)
* [Auteur](#Auteur)


## Les balises

Les balises sont la base du code, elles structurent le code et met en forme l'idée que tu as en tête.

### Baliser le texte

Dans cette section tu verras quelques balises faites pour structurer du texte.

#### Les titres

Les éléments de titre permettent de définir certains textes comme des titres ou sous-titres pour le contenu. 
D'une certaine façon, ceux-ci fonctionnent comme pour un livre : on a le titre du livre (le plus important)
puis les titres des différents chapitres et parfois des sous-titres au sein de ces chapitres.
L'HTML contient des éléments pour 6 niveaux de titres : `<h1>`–`<h6>`. La plupart du temps, 3-4 niveaux suffisent

| Balise | Description                   |
| ------ | ----------------------------- |
| h1     | Titre Principal (gros)        |
| h2     | Titre de Section (plus petit) |
| h3     | Sous titre                    |
| h4     | Sous sous titre               |

Exemple :
```html 
<h1>Je suis un titre</h1>
<h2>Je suis un titre de section</h2>
<h3>Je suis un sous titre</h3>
<h4>Je suis un sous sous titre</h4>
```


#### Les paragraphes

Les éléments `<p>` sont utilisés pour contenir des paragraphes de texte. Ce sont les balises les plus utilisées.

| Balise | Description |
| ------ | ----------- |
| p      | Paragraphe  |

Exemple :
```html 
<p>Je suis un texte</p>
```

#### Les listes

| Balises | Description                                                  |
| ------- | ------------------------------------------------------------ |
| ul      | Liste **non ordonnée** ( liste d'ont l'ordre n'a pas d'importance (exemple : liste emplettes)) |
| ol      | Liste **ordonnée** (Liste d'ont l'ordre a de l'importance (recette par exemple)) |
| li      | Elément d'une liste                                          |


Exemple : 

```html 
<p> Le monde est composé de </p>

<ul>
    <li>Cons</li>
    <li>Pas cons</li>
</ul>
```


#### Les liens

Les éléments `<a>` sont utilisés comme liens, ils servent a transformer un texte en lien.

| Balise | Description | Paramètre essentiel |
| ------ | ----------- | ------------------- |
| a      | Lien        | href (lien)         |

On peut rajouter a la balise `<a>` un paramètre (`href`) permettant de spécifier ou rediriger l'utilisateur (lien web par exemple)

Exemple :
```html
<a href='https://www.spiie.netlify.app'> Site de Spiie </a>
```


### Balise d'Images

Les éléments `<img>` sont utilisés comme images, ils servent a intégrer une image a la page.

| Balise | Description | Paramètres essentiels                             |
| ------ | ----------- | ------------------------------------------------- |
| img    | Image       | src (source de l'image)<br />alt (nom alternatif) |

Pour intégrer une image les paramètres `src` et `alt` sont essentiels. `src` permet de préciser ou ce trouve l'image et `alt` lui donner un nom.

Exemple :

```html
<img src='https://shorturl.at/FJPT7' alt='spiieImage' />
```

( `img` est un élément dit 'vide' il n'a pas de contenue alors la balise ce ferme directement ( `<Contenu />` ) )



## Message de fin

Voila, c'est la fin de ce petit memo, entraine toi déja avec ça, je te montrerais les styles plus tard. Montre moi ce que tu as fais quand tu finis.

Si tu veux en savoir plus sur les bases du html tu peux te rendre [ici](https://developer.mozilla.org/fr/docs/Learn/Getting_started_with_the_web/HTML_basics) ou me demander directement.



## Auteur

- Ton petit amis [@spiie](https://www.github.com/spiie) ! ❤️🐝
