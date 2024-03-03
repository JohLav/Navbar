# Navbar

## Introduction
Vous êtes chargé(e) de créer une barre de navigation (navbar) responsive pour un site web. L'objectif est de concevoir une navbar qui s'adapte à différentes tailles d'écrans, avec un menu hamburger (burger menu) qui s'affiche sur les écrans plus petits.

## Instructions

HTML de Base : Utilisez le modèle HTML fourni comme point de départ.
Ajoutez un titre ou un logo pour la section de la navbar.

Styles de Base : Stylez la navbar pour qu'elle ait une couleur de fond différente, une hauteur appropriée, et que le texte soit en blanc.
Le logo ou le titre de la navbar doit être stylisé pour être plus grand que les liens de navigation.

Liens de Navigation : Ajoutez des liens de navigation pour "Home", "About", "Services", et "Contact" à l'intérieur de la navbar.
Stylisez les liens pour qu'ils aient une marge à droite et une apparence distincte.

Menu Hamburger : Ajoutez un élément div avec la classe "burger-menu" à la navbar.
Stylisez le menu hamburger pour qu'il ait une apparence distinctive (par exemple, utilisez le caractère "☰").
Cachez le menu hamburger par défaut sur les écrans plus larges.

Media Query pour la Responsive Design : Utilisez une media query pour rendre la navbar responsive lorsque la largeur de l'écran est inférieure à 768 pixels.
Dans la media query, stylisez les liens de navigation pour qu'ils s'affichent en colonne et ajoutent une marge appropriée.
Assurez-vous que le menu hamburger est visible sur les écrans plus petits.
Lorsque le menu hamburger est cliqué, faites en sorte que les liens de navigation s'affichent (utilisez les classes CSS appropriées).
Bonus (facultatif) : Ajoutez des animations de transition pour rendre l'expérience utilisateur plus fluide.
Personnalisez davantage le style de la navbar en utilisant des couleurs, des polices, etc.

Ressources : Vous pouvez utiliser n'importe quelle icône pour le menu hamburger. Une ressource pratique est Font Awesome.
N'hésitez pas à ajuster les couleurs, polices, et autres styles pour correspondre à l'esthétique de votre site.

## Consignes

Travaillez principalement dans le fichier styles.css pour ajouter vos styles.
Vous pouvez utiliser des médias externes (par exemple, Font Awesome) si nécessaire.
Testez votre navbar sur différentes tailles d'écrans pour assurer une expérience utilisateur cohérente.
Commentez votre code pour expliquer chaque section.
Model de Référence :

`

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="stylesheet" href="styles.css">
  <title>Responsive Navbar Exercise</title>
</head>
<body>
  <header>
    <div class="logo">Your Logo</div>
    <nav>
      <ul class="nav-links">
        <li><a href="#">Home</a></li>
        <li><a href="#">About</a></li>
        <li><a href="#">Services</a></li>
        <li><a href="#">Contact</a></li>
      </ul>
      <div class="burger-menu">&#9776;</div>
    </nav>
  </header>
</body>
</html>
`
