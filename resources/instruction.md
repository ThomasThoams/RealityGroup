# M07 - REALITY GROUP


1. Mettre le footer en pied de page en exploitant Flexbox
2. Introduction aux variables css  
3. Mettre en forme la bannière et le menu en exploitant Flexbox
4. Créer et faire fonctionner un menu déroulant (faire apparaître un sous-menu au survol) à l'aide des positions CSS
5. Introduction aux tableaux HTML et selecteurs `:nth-child`
6. Introduction aux formulaires et sélecteurs d'attribut
7. Un mot sur le débordement de contenu


Un code de départ est fourni et doit être complété.

## Charte graphique et variables CSS

Les couleurs sont stockées dans des variables, fournies ci-dessous; le préfixe correspond au projet (Reality Group) afin d'éviter les conflits.

--rg-color-default      : #a49e9e;
--rg-color-link         : #2cbcd6;
--rg-color-link-hover   : #89deed;
--rg-color-even         : #f2f2f2;
--rg-color-odd          : #fafafa;

Ces variables sont affectées à la balise `<html>` avec la pseudo-classe `:root` car sa spécificité plus forte que le sélecteur de balise `html`.

## Mettre le footer en pied de page

Les éléments HTML se placent les uns derrière les autres. 
En fonction de leur contenu et de la taille du viewport, la hauteur n'est pas suffisante pour que le pied de page soit au pied de la fenêtre, ce qui peut apparaîre comme disgracieux.

Comment utiliser flexbox sur la balise body pour corriger ce problème ?

## Mise en forme de la bannière et du menu

Flexbox à la rescousse !

## Menu déroulant 

** Dans cet exercice, nous n'utiliserons pas de classes ni d'identifiants pour cibler les balises.
L'objectif est de bien repérager l'emboitement des balises afin d'utiliser les selecteurs CSS d'enfants directs et de descendants.  **


Le menu de navigation est construit avec une liste html.
Chaque item de cette liste contient un lien toujours visible.

Un sous-menu est une liste, insérée dans un item (`<li>`) à la suite du lien, et qui doit être cachée au chargement.
Au survol du lien la précédant, elle doit apparaitre.

1. Créer 2 sous-menus en insérant une liste dans 2 des items déjà présents  
2. Mettre en forme le menu à l'aide de flexbox (+ d'autres bricoles)
3. Faire disparaître les sous-menus au chargement
4. Les faire apparaître au survol du lien correspondant 


### Ressources 

Code des 2 sous-menus

#### Sous-menu Products

```
<ul>
    <li><a href="#">Catch the Bullet</a></li>
    <li><a href="#">Snoopydoo</a></li>
    <li><a href="#">Fallen Angel</a></li>
    <li><a href="#">Sui Maker</a></li>
    <li><a href="#">Wave Master</a></li>
    <li><a href="#">Golf Pro</a></li>
</ul>

```

#### Sous-menu Application

```
<ul>
    <li><a href="#">Gadget Finder</a></li>
    <li><a href="#">Green Tree Express</a></li>
    <li><a href="#">Green Tree Pro</a></li>
    <li><a href="#">Wobbler 3.0</a></li>
    <li><a href="#">Coolkid</a></li>
</ul>

```

## Tableaux html

https://developer.mozilla.org/fr/docs/Web/HTML/Element/table

## Formulaires

https://developer.mozilla.org/fr/docs/Learn/Forms/Your_first_form

## Sélecteurs CSS

https://developer.mozilla.org/fr/docs/Web/CSS/:nth-child
https://developer.mozilla.org/fr/docs/Web/CSS/Attribute_selectors
https://code.tutsplus.com/fr/tutorials/the-30-css-selectors-you-must-memorize--net-16048

## Gérer le débordement de contenu

https://www.alsacreations.com/tuto/lire/1038-gerer-debordement-contenu-et-cesures-css.html