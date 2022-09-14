# HTML
## comment ça se passe ?
Tu as des balises genre : `<balise>` qui ne peuvent rien avoir dans elle.

Tu as des balises genre : `<balise></balise>` qui peuvent avoir plein de choses en elles.

## Comment ça ce construit ?
Le but de l'html c'est d'avoir une hiérarchie, une architecture qui va 
te permette de pouvoir afficher des choses genre du texte, images, video, sons, lien, ...

par exemple si je veut ecrire "hello world" qui est généralement le premier exo en html je pourrait marqué `<p>Hello world</p>`.

Mais avant tout de chose je doit dire a mon ordinateur que cet page est une page web et pour ça y a différente choses a faire

1. Créer un fichier html `index.html` pourquoi index? Parce que c'est généralement toujours le nom du premier fichier html qui va être ouvert quand on visite un site.
2. ecrire le `doctype`: c'est ce qui va correctement définire que ton fichier html est une page web. A l'intérieur de ce fichier.
3. Commencer a écrire dans la balise `<body></body>` de la page.

## Revenons au `doctype`
### Voici a quoi il ressemble

```HTML
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Is this a title?™ </title>
</head>
<body>
    
</body>
</html>
```

<br>
### Explications
<br>

```HTML
<!DOCTYPE html>
```
1. ça c'est la ligne très bizarre qui dit que c'est de l'html je pense. 
On s'en fous de pas le savoir y a des trucs commeça, c'est intéréssant de les savoirs mais pas directement.

Mais je pense que ça veut dire:

- `!` attention
- `DOCTYPE` le doctype
- doit être en `html`

<br><br><br>
```HTML
<html lang="en">

</html>
```
2. ça c'est la balise `html` le document commence ici. Et il y a autre choses

`lang="en"` en gros ça c'est un `attribut` ça sert a definire quelque chose d'addittionnel sur la balise.

Il y a plein d'attribut différent. Il y en a qui peuvent être que sur une seul balise par exemple celle là `<html lang="en"></html>` peut être que sur elle même

Il y en à qui peuvent être sur n'import quelle balise par exemple `<body class="ma-classe-pour-faire-du-css"></body>` est la balise `classe` qui permet de faire du css.

Il y a plein de balise différente renseigne toi fait le tour de ça par toi même.

Il y a plein de site pour apprendre ça genre le MDN, W3school, et le site qui les dominent tous c'est celui de la W3C mais il est horrible :)


<br><br><br>
```HTML
<head>

</head>
```
3. la balise `head` est une balise qui permet de mettre plein d'informations supplémentaire dans ta page.
Il y a le principe de la tête et du corps sur de l'HTML la tête c'est l'ame de ta page y a plein de trucs qui la définisse mais rien est apparent.


<br><br><br>
```HTML
    <meta charset="UTF-8">
```
4. la une nouvelle balise `meta` avec l'attribut `charset` qui va définir l'encodage des lettre en encodage UTF-8: 

pour faire très simple dans un ordinateur quand tu tape la touche 'a' ça va donner 'u/221' 
C'est parce que tout les symbole son enregistrer dans un tableau. un peu comme un fichier excel avec deux colonne.

Voici la page du mdn qui là définit [balise meta](https://developer.mozilla.org/fr/docs/Web/HTML/Element/meta)


<br><br><br>
```HTML
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
```
5. La y a `http-equiv` je sais pas c'est quoi mes apparemment ça rend quelque chose compatible

et y a `content="IE=edge"` encure un truc pour internet explorer et edge qui son les navigateur les plus nul que le monde ai connu.


<br><br><br>
```HTML
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
```
6. la c'est une ligne de code qui permet de bien définir la largeur par la largeur de l'appareil utilisé, ça pourrait etre un ordi, une tablette, un téléphone, un télé, une nitendo switch ...
et aussi ça définir le ration d'ascpect a 1 a 2 la page serait doubler je ne sais pas comment, jamais essayer essaye une fois et tu verra bien.


<br><br><br>
```HTML
    <title>Is this a title?™ </title>
```
7. ça c'est la balise title: elle permet de donner un nom d'onglet a ton navigateur
<br>

![image](https://www.wikihow.com/images/thumb/2/25/Title-tag-view.jpg/728px-Title-tag-view.jpg)

<br><br><br>
la je vais te demander ton premier exercice.
Tu va devoir te renseigner sur toute les balises que je vais te donner à chercher et tu va essayer de les implémenter

0. **Regarde aussi aux** `attributes`
1. balise de texte: `p, h1, h2, h3, h4, h5, h6, blockquote, code, strong, span, et si tu en trouve d'autre vasi fait le`
2. balise image: juste `img` si tu veut tu peut aussi regarder à la balise `video` c'est le même principe
3. balise pour les listes: `ul, ol, li`
4. balise pour faciliter la vie au robots qui scan ton site et qui permettent aussi fortement de mieux diviser chaque partie de ton site: `nav, aside, section, et regarde pour les autre elle porte un noms c'est balise de structure`
5. balise `div` MDR

## Exercice final pour cloturer l'html (presque)
Raconte moi qu'elle on été tes début sur un ordinateur, qu'est ce que tu as déja pu apprendre en informatique et qu'est ce que tu connais déja dans le web développement.
### TOUS ça avec les balises qu'il faut donc les balise d'organisation aussi. Une section une idée comme une slide d'une presentation :)
