#Semaine 2#
----------

Dans cette deuxiéme semaine **GOC** mise en bouche du code **HTML**

##HTML Le b.a.-ba 1 er partie
------------------

HTML **signifie HyperText Markup Language** *texte qui inclut des liens* 

-On appelle **balise** ce qui se trouve entre ces `< >`  se ferme   `< / >`.

-La balise `<!DOCTYPE html>` toujours en **1er**.

-Puis `<html>` et fermer le texte par `</html>`

-écrire un commentaire non`<!-- Commentaire -->` 

-codage de la page occidental `<meta charset="UTF-8">`

###Un document est composé de plusieurs partie####

 * `<head>` tête,endroit où l'on met les informations concernant le fichier HTML, comme son titre par exemple
 *  `<body>` corps,partie visible de la page web
 * `<header>` définir zone d'en tête d'un contenu  
 * `<nav>` définir zone contenant des liens 
 * `<main>` définir la zone de contenu principal 
 * `<aside>` permet d'encaspuler des informations complémentaires, 
 * `<section>` définir les limites d'un artcicle relatif 
 * `<footer>` définir une section de conclusion d'un article ou d'une section, voir du document 


![#####exemple de structure basique#####](http://simplonline.co/uploads/images/Front_End/zuliegarnier/structure_de_base_html.jpg)

###Les éléments du corps  

* `<p>` balise pour creer des paragraphes
* `<h1>` à `<h6>` balises titres H1 plus grand H6 le plus petit
* Ajout d'image
`<a>` C'est elle qui permet de créer un lien. Cette balise possède un attribut appelé `href`. La valeur donnée à `href` est l'adresse de la page web vers laquelle le lien renvoie
ex:`<a href="http://www.codecademy.com">Mon site préféré !</a>`
`<img>`balise image,**elle se ferme et s'ouvre d'elle-même**
* Avec la balise `<img>`, on utilise la source de l'image que l'on veut mettre. Grâce à cette information, la balise sait où trouver l'image. Pour ajouter cette source, on utilise le code `src`.Ce qui donne de manière générale : `<img src = "" />`
<span style="color:red">Notez le `/>` qui va fermer la balise.</span>
* code image cliquable
`<a href="http://www.codecademy.com/">
    <img src="http://s3.amazonaws.com/codecademy-blog/assets/f3a16fb6.jpg"/>
</a>`
-commenter avec le code`<!-- commentaire -->` 



-------
##HTML Le b.a.-ba 2 éme partie

------------------


### Créer des listes ordonnée et non ordonnées


 * liste ordonnées avec la balise `<ol>`
 * liste non ordonnées avec la balisee `<ul>`
* la balise liste `<li>`correspond à une ligne d'une liste non ordonnée ou ordonnée.
 <ul style="color:red">
 <li><strong>exemple de types de listes non ordonnées</li>
 	<ol>
 		<li>liste</li>
 		<li>ordonnés</li>
 	</ol>
 <li>qui sont imbriqués</strong></li>
 </ul>
 
 ```
  <ul style="color:red">
 <li><strong>exemple de types de listes non ordonnées</li>
 	<ol>
 		<li>liste</li>
 		<li>ordonnés</li>
 	</ol>
 <li>qui sont imbriqués</strong></li>
 </ul>
 ```
 


###Avoir le style####

* <span style = "font-size:30px">taille </span>`style = "font-size:12px">` 
`<p style = "font-size:12px">`
* <span style="color:red">la couleur</span>
`<tr style="color:red">`
* <span style="font-family:Calibri">type de police</span>
`<h1 style="font-family: Arial">Titre</h1>`


### Changer la couleur d'arrière-plan

`style="background-color: red`

###Aligner le texte####

* "text-align:left" pour aligner le texte à gauche
* "text-align:right" pour aligner le texte à droite
* "text-align:center" pour centrer le texte `style="text-align:center"`

*  mot en gras`<strong>` `</strong>` et italique `<em>``</em>`

----
##HTML Le b.a.-ba 3 éme partie
-----
###Tableau

* tout tableau commence par la balise `<table>`
	* créations de ligne avec `<tr>`(pour table row signifiant "ligne du tableau")
	*  une cellule de données `<td>` (pour table data, signifiant "donnée du tableau")
	
	
		<table border="1px">
            <tr>
                <td>Un</td>
                <td>quatre</td>
                </tr>
            <tr>
               <td>Deux</td>
               <td>cinq</td>
               </tr>
            <tr>
                <td>Trois</td>
				 <td>six</td>
            </tr>
        </table>

```
	<table border="1px">
            <tr>
                <td>Un</td>
                <td>quatre</td>
                </tr>
            <tr>
               <td>Deux</td>
               <td>cinq</td>
               </tr>
            <tr>
                <td>Trois</td>
				 <td>six</td>
            </tr>
        </table>
 ```                               
        

* L'en-tête du tableau
	* Ces balises sont à insérer à l'intérieur de la balise `<table>`.
	* la balise `<thead>` contient des informations sur le tableau 
	* la balise `<tbody>` contiendra les données à l'intérieur du tableau
	* pour qu'une ligne de titre sur toute la longueur du tableau, ici s'étend sur 3 colonnes `<th colspan="3">` `</th>`
	
	
	<html>
    <head>
        <title>Les tableaux</title>
    </head>
    <meta charset="utf-8">

    <body>
    <table style="border-collapse:collapse;">
            <thead>
                <tr>
                    <th colspan="2"style="color:red">Les monstres célèbres par année de naissance</th>
                </tr>
                <tr style="border-bottom:1px solid black;">
                    <th style="padding:5px;"><em>Les monstres célèbres</em></th>
                    <th style="padding:5px;border-left:1px solid black;"><em>Année de naissance</em></th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td style="padding:5px;">King Kong</td>
                    <td style="padding:5px;border-left:1px solid black;">1933</td>     
                </tr>
                <tr>
                    <td style="padding:5px;">Dracula</td>
                    <td style="padding:5px;border-left:1px solid black;">1897</td>
                </tr>
                <tr>
                    <td style="padding:5px;">Frankenstein</td>
                    <td style="padding:5px;border-left:1px solid black;">1944</td>
                </tr>
            </tbody>
        </table>
        
    </body>

</html>	
	
```

<html>
    <head>
        <title>Les tableaux</title>
    </head>
    <meta charset="utf-8">
    <body>
    <table style="border-collapse:collapse;">
            <thead>
                <tr>
                    <th colspan="2"style="color:red">Les monstres célèbres par année de naissance</th>
                </tr>
                <tr style="border-bottom:1px solid black;">
                    <th style="padding:5px;"><em>Les monstres célèbres</em></th>
                    <th style="padding:5px;border-left:1px solid black;"><em>Année de naissance</em></th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td style="padding:5px;">King Kong</td>
                    <td style="padding:5px;border-left:1px solid black;">1933</td>     
                </tr>
                <tr>
                    <td style="padding:5px;">Dracula</td>
                    <td style="padding:5px;border-left:1px solid black;">1897</td>
                </tr>
                <tr>
                    <td style="padding:5px;">Frankenstein</td>
                    <td style="padding:5px;border-left:1px solid black;">1944</td>
                </tr>
            </tbody>
        </table>
    </body>
</html>
```
###DIV et SPAN

* la balise `<div>``</div>` vous permet de diviser votre page en plusieurs patries et d'affecter à chacune d'elles un style particulier


<html>
<meta charset="utf-8">
	<head>
		<title>Résultat</title>
	</head>
	<body>
		<div style="width:50px; height:50px; background-color:red"></div>
		<div style="width:50px; height:50px; background-color:blue"></div>
		<div style="width:50px; height:50px; background-color:green"></div>
		<a href="http://websitesetup.org/html5-cheat-sheet/"><div style="width:50px; height:50px; background-color:yellow"></div></a>
	</body>
</html>

```
<!DOCTYPE html>
<html>
<meta charset="utf-8">
	<head>
		<title>Résultat</title>
	</head>
	<body>
		<div style="width:50px; height:50px; background-color:red"></div>
		<div style="width:50px; height:50px; background-color:blue"></div>
		<div style="width:50px; height:50px; background-color:green"></div>
		<a href="http://websitesetup.org/html5-cheat-sheet/"><div style="width:50px; height:50px; background-color:yellow"></div></a>
	</body>
</html>
```


* `<span>` vous permet de contrôler le style des parties les plus petites de votre page, vous pouvez amodifier la taille et la famille de police et n'importe quel attribut de style que vous connaissez. 

<html>
	<head>
		<title>Résultat</title>
	</head>
	<body>
		<p>Ma police <span style="color:red">favorite</span>, c'est <span style="font-family:Impact">Impact</span></p>
	</body>
</html>

```

<html>
	<head>
		<title>Résultat</title>
	</head>
	<body>
		<p>Ma police <span style="color:red">favorite</span>, c'est <span style="font-family:Impact">Impact</span></p>
	</body>
</html>

```

###Lien vers mes **badges** [code academy](https://www.codecademy.com/fr/users/akarika/achievements)