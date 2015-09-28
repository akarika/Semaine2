#Semaine 2#
----------

Dans cette deuxiéme semaine **GOC** mise en bouche du code **HTML**

###HTML Le b.a.-ba### 1 er partie
------------------

HTML **signifie HyperText Markup Language** *texte qui inclut des liens* 

-On appelle **balise** ce qui se trouve entre ces ** `< >` ** se ferme  ** `< / >` **.

-La balise `<!DOCTYPE html>` toujours en **1er**.

####Un document est composé de plusieurs partie####

 * `<head>` tête,endroit où l'on met les informations concernant le fichier HTML, comme son titre par exemple
 *  `<body>` corps,partie visible de la page web
 * `<header>` définir zone d'en tête d'un contenu  
 * `<nav>` définir zone contenant des liens 
 * `<main>` définir la zone de contenu principal 
 * `<aside>` permet d'encaspuler des informations complémentaires, 
 * `<section>` définir les limites d'un artcicle relatif 
 * `<footer>` définir une section de conclusion d'un article ou d'une section, voir du document 


![#####exemple de structure basique#####](http://simplonline.co/uploads/images/Front_End/zuliegarnier/structure_de_base_html.jpg)

####Les éléments du corps #### 

* `<p>` balise pour creer des paragraphes
* `<h1>` à `<h6>` balises titres H1 plus grand H6 le plus petit
* Ajout d'image
`<a>` C'est elle qui permet de créer un lien. Cette balise possède un attribut appelé `href`. La valeur donnée à `href` est l'adresse de la page web vers laquelle le lien renvoie
ex:`<a href="http://www.codecademy.com">Mon site préféré !</a>`
`<img>`balise image,**elle se ferme et s'ouvre d'elle-même**
* Avec la balise `<img>`, on utilise la source de l'image que l'on veut mettre. Grâce à cette information, la balise sait où trouver l'image. Pour ajouter cette source, on utilise le code `src`.Ce qui donne de manière générale : `<img src = "" />`
Notez le `/>` qui va fermer la balise.
* code image cliquable
`<a href="http://www.codecademy.com/">
    <img src="http://s3.amazonaws.com/codecademy-blog/assets/f3a16fb6.jpg"/>
</a>`
-commenter avec le code`<!-- commentaire -->` 



-------
###HTML Le b.a.-ba### 2 éme partie

------------------
#### Créer des listes ordonnée et non ordonnées


 * liste ordonnées avec la balise `<ol>`
 * liste non ordonnées avec la balsie `<ul>`
  la balise liste `<li>`correspond à une ligne d'une liste non ordonnée ou ordonnée.

####Avoir le style####

-taille 
`<p style = "font-size:12px">`
-la couleur
`<h2 style="color:red">`
-type de police
`<h1 style="font-family: Arial">Titre</h1>`
attribut `style`
font-size: 14px
color: orange
font-family: Bodoni

c. Changer la couleur d'arrière-plan

`style="background-color: red`

*  Aligner le texte

a. "text-align:left" pour aligner le texte à gauche
b. "text-align:right" pour aligner le texte à droite
c. "text-align:center" pour centrer le texte `"style="text-align:center"`

*  mot en gras`<strong>` `</strong>` et italique `<em>``</em>`

