# Xmonad 

*version: 0.1*
*deps: [xmonad 0.12]*
*github: *

## Lexique

* Layout régle d'affichage des fenetres 

* Tag emplacment ou s'ouvrent les fenetres ( "bureau" )

## Layouts

Tiled: La fenètre principale se trouve à gauche. Les fenètres secondaires s'empilent à droite.

Mirror Tiled: La fenètre principale est au dessus. Les fenètres secondaires se mettent en colonnes en dessous.

Full: La fenètre occupe toute la place

## Bindings

mod = win

### Layouts

Iterer les layouts: mod + ²

Rester le layout: mod + shift + ²

### Applications

Afficher les applis en cours : mod + shift + tab
Terminal : mod + a

Editeur 1 ( vim ) : mod + z

Editeur 2 ( gedit ) : mod + shift + z

Navigateur 1 ( google-chrome ) : mod + e

Navigateur 2 ( firefox ) : mod + shift + e

Navigateur 3 ( chromium ) : mod + shift + ctrl + e

Lanceur d'applis 1 ( dmenu ) : mod + p

Lanceur d'applis 2 ( gmrun ) : mod + shift + p

Augmenter le volume : mod + n

Diminuer le volume : mod + b

Mute  : mod + v

### Deplacements tags

Déplacer le focus sur le tag n: mod + [0,9]

Déplacer la fenètre sur le tag n: mod + shift + [0,9]

Retourner sur le tag précédent: mod + tab

Focus sur tag suivant: mod + right

Focus sur tag précédent : mod + left 

Déplacer la fenètre courante sur tag suivant: mod + right 

Déplacer la fenètre courante  sur tag précédent : mod + left

### Déplacements screens

Focus sur l'écran suivant: mod + up

Focus sur l'écran précédent : mod + down 

Déplacer la fenètre courante sur l'écran suivant: mod + up 

Déplacer la fenètre courante  sur l'écran précédent : mod + down 


### Focus

Déplacer le focus à la fenètre suivante : mod + µ

Déplacer le focus à la fenètre précédente : mod + ù

Changer la position de la fenètre actuelle avec la suivante : mod + shift + µ

Changer la position de la fenètre actuelle avec la précédente : mod + shift + ù

Focus sur la fenètre principale : mod + delete

Passe le fenètre courante en fenètre principale: mod + return

### Fenètres

Fermer la fenètre : mod + w 

Agrandir l'espace dédié à la fenètre : mod + $

Réduir l'espace dédié à la fenètre : mod + ^

### Xmonad

Relancer : mod + escape 

Quitter : mod + shift + escape

### Docs 

## Barre de status

* trayer avec nm-applet.

* température

* charge moyen du système

* pourcentage cpu utilisé

* pourcentage ram utilisé

* Batterie en charge ou decharge + temps restant

* date, heure
