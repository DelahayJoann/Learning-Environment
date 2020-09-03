1. [Retour au README](./README.md)
2. [What is Markdown](./WhatisMarkdown.md) by Joann
3. [Markdown origin](./texte.md) by Yvan
4. [Offbeat design](./lepetitplus.md) by Florence

# syntaxe Markdown

## Formatage

Pour mettre du texte en emphase , ce qui produit une mise en italique dans un navigateur courant :

  _Ceci est une phrase en italic_

Pour mettre du texte en grande emphase, ce qui produit une mise en gras dans un navigateur courant :

  __Ceci est une phrase en gras__

Pour mettre du code dans le texte :

  Mon texte `code` fin de mon texte

Ou sur plusieurs lignes avec coloration syntaxique selon le langage mis en préfixe :

```php
Mon code PHP en couleurs
sur plusieurs lignes
```

Pour un paragraphe de code, mettre quatre espaces devant:

    Première ligne de code
    Deuxième ligne

Comme dans les courriels, il est possible de faire des citations :

> Ce texte apparaîtra dans un élément HTML.

Pour faire un nouveau paragraphe, sauter deux lignes, c'est à dire laisser une ligne vide entre les deux paragraphes. Sauter une seule ligne dans le texte d'origine n'aura aucun effet à l'affichage (l'affichage sera en continu).

Premier paragraphe

Deuxième paragraphe   

## Listes

Sauter une ligne avant le début de la liste.

Pour créer une liste non ordonnée :

* Pommes
* Poires
  * Sous élément avec au moins quatre espaces devant.

Et une liste ordonnée :

    1. mon premier
    2. mon deuxième

Et une liste en mode case à cocher

    - [ ] Case non cochée
    - [x] Case cochée

## Titres

Les titres sont créés avec un certain nombre de # avant le titre, qui correspondent au niveau de titre souhaité

    # un titre de premier niveau
    #### un titre de quatrième niveau

Pour les deux premiers niveaux de titre, il est également possible de souligner le titre avec des = ou des - (leur nombre réel importe peu, mais il doit être supérieur à 2)

    Titre de niveau 1
    =====================
    Titre de niveau 2
    -------------------

## Tableaux

Pour créer des tableaux:

    | Titre 1       |     Titre 2     |        Titre 3 |
    | :------------ | :-------------: | -------------: |
    | Colonne       |     Colonne     |        Colonne |
    | Alignée à     |   Alignée au    |      Alignée à |
    | Gauche        |     Centre      |         Droite |

## Liens

Pour créer des liens:

    [texte du lien](url_du_lien "texte pour le titre, facultatif")

## Images

Pour afficher une image:

    ![Texte alternatif](url_de_l'image "texte pour le titre, facultatif")
