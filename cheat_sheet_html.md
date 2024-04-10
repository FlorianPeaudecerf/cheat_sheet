1. `<header>` :  
Utilisé pour représenter l'en-tête d'une section ou d'une page. Il contient généralement des éléments d'introduction tels que le titre, le logo, et éventuellement des éléments de navigation.

2. `<nav>` :  
Utilisé pour représenter une section de navigation. Il contient généralement des liens vers d'autres pages ou sections du site.

3. `<main>` :  
Utilisé pour représenter le contenu principal de la page. Il devrait contenir le contenu central de la page, excluant généralement les en-têtes, pieds de page et barres latérales.

4. `<section>` :  
Utilisé pour regrouper le contenu thématique dans une page. Il peut contenir des sous-sections ou des articles.

5. `<article>` :  
Utilisé pour représenter un contenu autonome et réutilisable, tel qu'un article de blog ou un commentaire.

6. `<aside>` :  
Utilisé pour représenter le contenu à côté du contenu principal, comme des barres latérales ou des notes de bas de page.

7. `<footer>` :  
Utilisé pour représenter le pied de page d'une section ou d'une page.
## Dropdowns (Liste déroulante) :
Les dropdowns, ou listes déroulantes, permettent à l'utilisateur de sélectionner une option à partir d'une liste d'options déroulante.
<select>
  <option value="valeur1">Option 1</option>
  <option value="valeur2">Option 2</option>
  <option value="valeur3">Option 3</option>
</select>  
L'utilisateur peut cliquer sur la flèche ouverte pour afficher toutes les options disponibles et sélectionner celle qui lui convient.  

## Boutons radio :

Les boutons radio permettent à l'utilisateur de sélectionner une seule option parmi plusieurs options.  
<input type="radio" id="option1" name="options" value="option1">
<label for="option1">Option 1</label>  
<input type="radio" id="option2" name="options" value="option2">
<label for="option2">Option 2</label>  
<input type="radio" id="option3" name="options" value="option3">
<label for="option3">Option 3</label>  

L'utilisateur peut sélectionner une seule option à la fois en cliquant sur le bouton radio correspondant. Les boutons radio ayant le même attribut name forment un groupe, et un seul bouton peut être sélectionné à la fois dans ce groupe.









## Insérer une vidéo :  
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ma page avec une vidéo</title>
</head>
<body>
    <h1>Ma vidéo</h1>
    <video width="640" height="360" controls autoplay loop preload="auto">
        <source src="chemin_vers_la_video.mp4" type="video/mp4">
        Votre navigateur ne prend pas en charge la lecture de vidéos HTML5. Vous pouvez la télécharger <a href="chemin_vers_la_video.mp4">ici</a>.
    </video>
</body>

  `width` : Définit la largeur de la vidéo en pixels.  
    `height` : Définit la hauteur de la vidéo en pixels.  
    `controls` : Affiche les contrôles de lecture de la vidéo (lecture, pause, etc.).  
    `autoplay` : Indique au navigateur de démarrer automatiquement la lecture de la vidéo dès que la page est chargée.  
    `loop` : Indique au navigateur de répéter automatiquement la lecture de la vidéo une fois qu'elle est terminée.  
    preload` : Indique au navigateur comment gérer le chargement de la vidéo ("auto", "metadata" ou "none").    

<h2>Conclusion</h2>
En utilisant ces éléments sémantiques, vous pouvez structurer votre code HTML de manière plus significative, ce qui améliore l'accessibilité, l'indexation par les moteurs de recherche, et la lisibilité du code.