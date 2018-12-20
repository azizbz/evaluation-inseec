# Évaluation individuelle

## Programmation - Coaching

```
Nom : Bouzghaia	
Prénom : Aziz
URL de votre compte Github : https://github.com/azizbz
```

## Déroulé et fonctionnement. 

L'évaluation est à faire sur [Typora](https://typora.io/). Les réponses sont à écrire dans les blocks de code. 
Pour la partie Ruby, testez votre code sur [repl.it](https://repl.it/) et copiez le dans les blocks de code prévu à cet effet. 
Une fois fini, pushez votre feuille sur Github, dans un nouveau repository que vous appelerez "evaluation-inseec".
L'évaluation est individuelle et durera 1h30. Elle intègre des notions d'HTML, CSS, Ruby et computer science. 

![alt](https://media.giphy.com/media/26xBBfd0ii1khakpy/giphy.gif)

## Quelques mises en garde.

Je connais très bien ce merveilleux site qu'est Wikipédia. Je vous saurais gré de ne pas me remplir certaines questions avec les définitions de Wikipédia. Accessoirement, je sais aussi faire une recherche Google. Si j'ai un doute, je n'hésiterais pas rechercher "Qu'est-ce qu'une API" et comparer les définitions en tête de recherche avec les votre. Si je trouve une similarité trop grande et que je doute de votre bonne foi, je n'hésiterais pas à mettre 0 à la question. 
Pareil pour la copie sur les voisins. Si c'est trop gros et que j'ai un doute trop prononcé... 🔫

![alt](https://media.giphy.com/media/BtedgmzGNCiuk/giphy.gif)



------

### 1. Avec vos mots, expliquez l'interaction client-serveur

```t
L'iteraction client-serveur est un mode de communication à travers un réseau entre plusieurs programmes: les clients envoient des requêtes, et les serveurs receptionnent ces requêtes et y répondent
```



 ### 2. HTML est un langage côté... 

```
client
```



### 3. Donnez-moi la structure de base d'une feuille HTML

```html
<!DOCTYPE html>
<!-- Completez après cette ligne -->
<html>

  <head>
    <title>Titre affiché dans la barre de titre du navigateur</title>
  </head>

  <body>
    <!-- C'est ici que vous mettrez votre contenu  -->
  </body>

</html>
```



### 4. Changez la couleur du texte "J'adore la programmation" en rose en utilisant du CSS.

```html
<div>
   <p>J'adore la programmation</p>
</div>
```

```css
/* Ecrire le code CSS sous cette ligne */
p
{
    color: #pink;
}

```



### 5. Qu'est-ce que Bootstrap ?

```
Bootstrap est une boîte à outils open source pour le développement HTML, CSS et JS pour la création du design de sites et d'applications web.
```



### 6. Reprenez votre code de la question 3 et ajoutez Bootstrap à votre feuille HTML, au bon endroit.

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">

    <!-- Bootstrap CSS -->
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/css/bootstrap.min.css" integrity="sha384-MCw98/SFnGE8fJT3GXwEOngsV7Zt27NXFoaoApmYm81iuXoPkFOJwJ8ERdknLPMO" crossorigin="anonymous">

    <title>Titre affiché dans la barre de titre du navigateur</title>
  </head>
  <body>
```



### 7. Mettez ces trois divs sur le même plan horizontal avec trois colonnes de même taille.

```html
<div id="colonne1">Google</div>

<div id="colonne2">Microsoft</div>

<div id="colonne3">Apple</div>

```



### 8. Avec le même code, changez le texte par le logo de la marque en question

```html
<div>
    Google
</div>

<div>
    Microsoft
</div>

<div>
    Apple
</div>
```

 

### 9. Toujours sur le même bout de code, rendez les logos cliquables. Quand on clique sur le logo, on doit arriver sur le site officiel de la marque.

```html
<div>
    Google
</div>

<div>
    Microsoft
</div>

<div>
    Apple
</div>
```

![Mon gars sûr !](https://media.giphy.com/media/l0K4mbH4lKBhAPFU4/giphy.gif)

### 10. Parlons Ruby. Ruby est un langage côté...

```
client et serveur
```



### 11. Listez-moi tous les types de données que vous connaissez.

```
string - pour les petits types de données tels qu'un titre.
text - pour des données textuelles plus longues, comme un paragraphe d'information.
binary - sert à stocker des données telles que des images, de l'audio ou des films.
boolean - est pour stocker des valeurs vraies ou fausses.
date - stocker uniquement la date.
datetime - stocke la date et l'heure dans une colonne.
time - est pour l'heure seulement.
timestamp - pour stocker la date et l'heure dans une colonne.
decimal - est pour les décimales.
float - est pour les décimales. 
integer - est pour les nombres entiers.
primary_key - clé unique qui peut identifier de manière unique chaque ligne d'une table.
```



### 12. Assignez à des variables votre prénom, nom et le lien de votre compte Github puis affichez chacune des variables. En 6 lignes.

```ruby
first_name= "aziz"
puts first_name
name "bouzghaia"
puts name
github_account= "https://github.com/azizbz"
puts github_account
```



### 13. Assignez 674 et 311 à des variables `a` et `b` et stockez le résultat `a` modulo `b` dans une variable `c` et affichez la. 

```ruby

# Le résultat attendu est 52. 
a = 674
b = 311
c = a%b
print c

```



### 14. Qu'est-ce qu'une gem ? 

```texte
Les gems sont des modules de codes produits par d'autres développeurs qui apportent des fonctionnalités à l'application Ruby
```



### 15. Qu'est-ce qu'une API et qu'est-ce qui nous permet de nous y connecter ?

```
API signifie Application Programming Interface c'est un ensemble normalisé de classes, de méthodes ou de fonctions qui sert de façade par laquelle un logiciel offre des services à d'autres logiciels. Une clé nous permet de se connecter.
```



### 14. On va créer un script pour dire bonjour ou bonsoir, en fonction de l'heure de la journée. Votre script doit demander à l'utilisateur de rentrer son prénom. Si `hour` est inférieur à 12, lui dire `Bonjour Anthony` sinon `Bonsoir Anthony` (évidemment, le prénom doit être celui renseigné par l'utilisateur).

```Ruby
# <- Demander le prénom de l'utilisateur

hour = 15

# Si hour est inférieur à 12
	# j'écris mon code permettant de dire Bonjour prénom

# sinon
	# j'écris mon code permettant de dire Bonsoir prénom

```



### 15. Itérer sur l'array contenant des noms de twitos un peu famous et follow chacun d'eux grâce à une méthode trouvée dans la [doc de la gem twitter](https://github.com/sferik/twitter). Pas besoin de lancer le code et de faire la partie authentification. Juste le bloc d'itération suffira. 

```ruby
handles = ["@richardbranson", "@jeffweiner", "@LinkedInQueen", "@ericschmidt", "@elonmusk", "@petecashmore", "@SteveForbesCEO", "@mtbarra"]


```



### 16. Félicitations, vous êtes arrivé·e à la fin, pushez cette feuille sur votre Github dans un repo appelé `evaluation-inseec`. N'oubliez pas de remplir le premier block avec votre identité tout en haut ! 

![alt](https://media.giphy.com/media/l0MYJnJQ4EiYLxvQ4/giphy.gif)

