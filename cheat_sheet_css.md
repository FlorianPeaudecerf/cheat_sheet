## Sélecteurs CSS :

- Sélecteur d'élément : element {} (ex. p {})
- Sélecteur de classe : .classname {} (ex. .container {})
- Sélecteur d'id : #idname {} (ex. #header {})
- Sélecteur descendant : ancestor descendant {} (ex. .parent p {})
- Sélecteur enfant direct : parent > child {} (ex. .container > div {})
- Sélecteur d'attribut : [attribute="value"] {} (ex. [type="text"] {})
- Sélecteur de pseudo-classes : :pseudo-class {} (ex. :hover {})
- Sélecteur de pseudo-éléments : ::pseudo-element {} (ex. ::before {})

## Propriétés CSS :
### Mise en forme du texte :

- color : couleur du texte
- font-family : famille de police
- font-size : taille de la police
- font-weight : épaisseur de la police
- text-align : alignement du texte
- text-decoration : décoration du texte (souligné, barré, etc.)
- line-height : hauteur de ligne

## Mise en forme du conteneur :

- width : largeur du conteneur
- height : hauteur du conteneur
- margin : marges extérieures
- padding : rembourrage intérieur
- border : bordure
- background-color : couleur de fond

## Positionnement :

- position : positionnement (relative, absolute, fixed, etc.)
- top, bottom, left, right : décalage par rapport à la position de base
- z-index : ordre d'empilement des éléments

## Flexbox (Disposition flexible) :

- display: flex : active le modèle de boîte flexible
- flex-direction : direction des éléments flexibles
- justify-content : alignement horizontal des éléments flexibles
- align-items : alignement vertical des éléments flexibles
- flex : attribue une taille flexible à un élément

## Grilles (Grids) :

- display: grid : active le modèle de grille
- grid-template-columns : définit la taille des colonnes de la grille
- grid-template-rows : définit la taille des lignes de la grille
- grid-gap : espace entre les cellules de la grille
- grid-column, grid-row : positionnement des éléments dans la grille

## Animation :

- animation-name : nom de l'animation
- animation-duration : durée de l'animation
- animation-delay : délai avant le début de l'animation
- animation-iteration-count : nombre de répétitions de l'animation
- animation-timing-function : fonction de temporisation de l'animation

## Transitions :

- transition-property : propriétés à animer
- transition-duration : durée de la transition
- transition-delay : délai avant le début de la transition
- transition-timing-function : fonction de temporisation de la transition

## Unités CSS :

- px : pixels
- % : pourcentage
- em : taille de police de l'élément parent
- rem : taille de police de l'élément racine
- vh : hauteur de la fenêtre visible
- vw : largeur de la fenêtre visible