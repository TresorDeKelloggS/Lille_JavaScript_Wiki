# Les Variables

**Une variable** est une zone de stockage d'information. 
On peut l'imaginer comme une boîte dans laquelle on range des choses. 
Une variable possède trois propriétés importantes :

* son **nom** : pour identifier la variable facilement.
* sa **valeur** : la donnée qu'elle contient.
* son **type** : qu'elle type de donnée elle contient.

> En Javascript on ne définit jamais le type d'une variable, on laisse l'ordinateur le faire pour nous.

## Lexique :
* On appelle `déclaration` ou `instanciation` d'une variable le fait d'initialiser une variable, de la créer :

![Variable declaration](../../ressources/basics/variables/declaration.png)


* On appelle `assignation` d'une valeur à une variable le fait de donner une valeur à une variable préalablement déclarée :

> Une assignation arrive toujours après une déclaration de variable.

![Variable assignation](../../ressources/basics/variables/assignation.png)

* Il est possible de combiner `déclaration` et `assignation` de variable sur la même ligne :

![Variable assignation and declaration](../../ressources/basics/variables/assignation_declaration.png)

### Les différents type de données

* **Le type Number**

Une variable peut contenir un nombre absolue ou relatif, positif ou négatif.

![Variable assignation and declaration](../../ressources/basics/variables/number.png)

* **Le type String**

Une variable peut contenir une chaîne de caractères, appelée `String`.

![Variable assignation and declaration](../../ressources/basics/variables/string.png)

* **Le type Boolean**

Une variable peut contenir une donnée de type `boolean` dans ce cas il n'y a que deux valeurs possibles : `true` ou `false`.

![Variable assignation and declaration](../../ressources/basics/variables/boolean.png)

* **Le type Array**

Voir la page wiki consacré [aux tableaux](./Les_tableaux.md).

* **Le type Object**

Voir la page wiki consacré [aux objets](./Les_objets.md).

* **Les autres types**

Il existe deux autres types de données qu'une variable peut contenir : le type `null` et le type `undefined`.

Le type `null` est une valeur comme les autres.

![Variable assignation and declaration](../../ressources/basics/variables/null.png)
> `null` n'est ni un `String` ni un `Number`, `null` est de type `null`

Le type `undefined` signifie que la variable ne possède pas de valeur, qu'elle n'a pas été définie.

![Variable assignation and declaration](../../ressources/basics/variables/undefined.png)

## Afficher la valeur d'une variable :

Pour afficher la valeur contenue dans une variable on utilise l'instruction `console.log(nomDeLaVariableAAfficher)`

![Print variable value](../../ressources/basics/variables/print_variable.png)


### Exemple :

![Example](../../ressources/basics/variables/example.png)

> Résultat :

![Result](../../ressources/basics/variables/result.png)

