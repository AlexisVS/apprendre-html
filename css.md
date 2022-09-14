#CSS

Alors le css ça veut dire Feuilles de style en cascade

en gros tu t'imagine une cascade et du css mdr 

en gros il y a un principe de priorité en css si: 

je charge la feuille 'A' qui dit que tous les titre son rouge et que 

je charge la feuille 'B' qui dit que tous les titres son en bleu

et ben les titre seront en bleu ben ouais foorcément `il va prendre la dernière arrivé`

## Comment écrire du css?
c'est très simple y' a 2 étape de préparation:

1. tu créé un fichier que tu peut appeler n'importe comment moi je vais lui donner le nom de `main.css`
2. tu va rajouter la ligne suivante apres la balise title dans le head.
    ```HTML
        <link href="main.css" rel="stylesheet">
    ```
    `href` pour le `chemin` de ton fichier `path` en anglais
    Je te conseille de t'arreter ici vite fait pour regarder vite fait un guide sur les chemins.
    Genre pour comprendre ça `   .  , ./  , ../  , ../../   ` ça sera obligatoire pour l'après CSS
    
3. et la ben tu peut commencer à écrire

à partire d'ici, je vais te demander de te documenter sur les paths que je t'ai expliqué audessus et aussi de `emmet` ça permet d'écrire plus rapidement de l'html.
Genre imagine je veut une section avec un titre puis un sous-titre puis un paragraphe puis une liste numéroté avec 3 item à l'intérieur j'ai plus qu'a écrire ça:

`section>h1+h2+p+(ol>li*3)` et appuyer sur tab ( qui est soit dit en passant au dessus de ta touche majuscule gauche)

## Ecrire correctement du css et écrire bien les choses de manière générale
Je te conseille de te baser sur des normes !

Personnellement j'aime bien la norme [BEM](https://getbem.com/) lis le site en entier et ça ira c'est vite fait et puis même, 
en informatique on passe notre temps a torcher des docs (documentations)

## Apprendre le css
Maintenant que tu as lu la norme normalement tu as du comprendre que pour chaque element HTML tu va devoir mettre un attribut `class=""` avec un nom **normé**

Pour apprendre pas a pas je te conseille d'abord:
1. modifier le design du texte (`couleur taille majuscule espacement des lettres espacement des mots, ... italique changer la police ( avec google font pour le moment (regarde une video qui explique avec google font)`)
2. modifier tes container genre mettre (`bordure ombres espacement(margin padding with height)`)
3. mettre des dispoosition a tous tes éléments avec `display:flex`
4. faire du responsive design de 320 pixel de largeur a 1920 pixel

## Je pense que avec ça tu es pret a être envoyé au Goulag :)

Dit moi quand tu as finit       on vera bien mouahahahaha 

Goulag Goulag Goulag Goulag !!!
