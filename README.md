# Html-Css
## Terminologies Html / Css :

+ `<head>` : Le head contient toutes les <meta> ou métadonnée. Ce sont les informations structurelles de la page qui n'apparaîtront pas directement à l'écran mais qui sont nécessaire pour le bon fonctionnement de la page.

+ `<body>` : Représente le corps de la page HTML.(un seul par document)

+ `<header>` : Partie haute de la page web/html. Contient en général le `<h1>` et la navigation `<nav>`
````html
<link>  : balise servant à charger du contenus CSS -- police + feuille de style
<p> définit un paragraphe.
<span> : pour sélectionner une partie du texte que l’on veut modifié.
<strong> / <b> : affiche un texte en gras
<u> : souligne un texte
<i> : affiche le texte en italique
<em> : italique ou gras pour un texte ( dépend du navigateur )
<div> :définit une division ou une section,appelé aussi calque
  ````



+ `.container` : la classe container va nous servir à définir un espace donné qui contient les données dans une partie de la page. C’est une classe que l’on définit soi même.
attributs : les attributs sont les informations notées

+ `float → left / right` :
Mettre une image en habillage du texte
positionner un élément à droite ou à gauche d’un autre.
inconvénients : sort du flux → certaines propriétés ne fonctionnent pas et les éléments ne sont plus relatif entre eux

+ `font-family` :change la police de caractères

+ `display` :
inline : aligne les éléments les uns à la suite des autres.
block  : réserve tout l’espace disponible sur la ligne, illustré par une marge qui remplis l’espace.
inline-block : lorsque des éléments inline-block sont côte à côte, ils se mettent à la suite et ensemble, forment un block.
+ `Les commentaires` :
Les commentaires servent à noter des informations textuels au milieu du code sans perturber son exécution. Ils peuvent également servir à masquer une partie du code sans avoir à effacer son contenus.


+ __commentaires en html :→__ `<!--  Zone de commentaire -->`

+ __commentaire en CSS : →__ `/*  Zone de commentaire   */`

### Définitions générales Css :

+ __Class :__
Éléments central du html / css, les classes permettent de sélectionner plusieurs éléments et de leur appliquer du style dans l’ensemble.
On définit à travers les classes, des propriétés communes à plusieurs éléments.

+ __Id :__
Identité de la balise, l’attribut ID permet d’identifier un balise précisément. Elle va nous permettre d’appliquer du style qui ne doit apparaître que sur cet élément.

+ __Typo / Font / Police de caractère :__
La police de caractère correspond à ce que l’on nomme en css la font-family.
Ce sont les visuels de caractère qui vont nous permettre de changer l’affichage du texte.
On peut les récupérer sur  google font ou Dafont et les charger via un système de balise <link> ou directement dans le css via ce que l’on appel les media queries
