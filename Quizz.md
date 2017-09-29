## Qu'est ce qu’un navigateur ?

```




```

________________________________________________________________________________________

## Définissez l’ensemble HTML/CSS/JavaScript et leur utilités.


```

Css : mise ne forme 




```
________________________________________________________________________________________


## Qu’est-ce qu’un élément HTML ? Un attribut ?

```
Elément HTML : balise html, permettant l'insertion d'objects, d'images, de textes..
	ex: <p>

Attrbut : appliqué à une balise l'attrbut permet "d'attribuer" des caractéristique spécifiques à celle-ci.





```
________________________________________________________________________________________


## Dans quels cas utilisez-vous des id au lieu des classes (et vice-versa) ?


```
id = éléments unique dans le document (appelé uniquement une fois)
classes : éléments pouvant se répéter dans le document, peut être appelé plusieurs fois. Permet d'appliquer le même style à plusieurs éléments. 


```
________________________________________________________________________________________


## Qu’est-ce que EcmaScript ?

```




```

________________________________________________________________________________________

## Pourquoi est-il important de bien indenter vos fichiers ?

```
L'indentation permet de faciliter la lecture et donc la compréhension du code = facilite le travail du développeur. Une bonne indentation pemret à des personnes extérieur au projet de comprendre plus facilement l'architecture de la page. 



```
________________________________________________________________________________________


## Quelle est la différence entre margin et padding ? 

```
margin : créer un ecart entre la bordure et l'élément et son voisin 
padding : créer un ecart entre le contenu d'un élément et sa bordure



```

________________________________________________________________________________________


## Citez au moins 3 types de positionnement en CSS et expliquer leurs rôles.

```

fixed : permet de maintenir l'élémen à sa position initial (ex: barre de navigation fixed restera visible en haut de la fenêtre lors du scroll).
relatif : le positionnnement de l'élément dépent de l'élement parent. 
absolu : permet de sortir l'élément du flux




```
________________________________________________________________________________________

## Qu’est-ce qu’une variable ?

```
Elément qui permet de stocker des informations, des fonctions... afin de pouvoir les utiliser par la suite. 

Le contenu d'une variable peut être modifié 



```
________________________________________________________________________________________


## Citez le plus de types JavaScript possible et définissez les rapidement.


```




```
________________________________________________________________________________________


##  À quoi sert le mot-clef “if” ?

```

definir une condition en JS. On realisera une action uniquement si l'action est remplie par exemple.



```

________________________________________________________________________________________

##  Définissez l’objet XHR en JavaScript, son abréviation. À quoi sert-il ?


```

Xhr = XMLhttpRequest = permet de faire des requête http (permet d'envoyer et de recevoir des informations utilisable sur notre site par exemple : API...). 



```

________________________________________________________________________________________

## Qu’est-ce qu’une requête HTTP ? 

```
Demande effectué à un serveur HTTP, (ex : demande d'affichage d'une page web..)



```
________________________________________________________________________________________


## Quelle sont les deux types de requêtes permettant de récupérer et d’envoyer de la donnée sur un serveur HTTP ?

```

synchrone 
asynchrone 


```

________________________________________________________________________________________

## À quoi sert le Header d’une requête ? Le “Content-Type” ?

```




```
________________________________________________________________________________________


## Donnez au moins 3 codes de réponse HTTP et définissez les.


```

2xx : Tout c'est bien déroulé 
3xx : problème lié au serveur 
4xx : erreur, adresse introuvable (404)



```
________________________________________________________________________________________


## Définissez les rôles de Scrum Master et Product Owner.


```
Scrum Master : s'assure du respect des procédures SCRUM en cours de projet

Product owner : Client 




```
________________________________________________________________________________________


## Citer 4 commandes utilisées avec GIT et expliquer leurs rôles.
```

git init : initialiser un dépôt git 
git status : visualiser l'état des fichiers à l'instant T (commité ou non...)
git push : Envoyer les fichoier sur le repos distant



```
________________________________________________________________________________________


## Expliquer le code suivant et indiquer le résultat retourné par la fonction.

```
function counter(){
        const sentence = "Validation de la première phase";
        const words = sentence.split(' ');
        let count = 0;


        for (let i = 0; i < words.length; i++) {
            var word = words[i];
            count += word.length;
        }
        return count;
}
```
```




```
________________________________________________________________________________________


## Algo 

Ecrire l’algorithme d’une fonction prenant en paramètre 2 arguments : le premier est une chaîne de caractère et le second correspondant au caractère recherché. Cette fonction retourne le nombre de fois que le caractère recherché est rencontré dans la chaîne de caractères.
Ex. 
   * chaîne : ‘examen’, caractère : ‘x’ => 1
   * chaîne : ‘wild code school’, caractère : ‘w’ => 1



```




```


