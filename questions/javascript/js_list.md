- Quelles sont les différences entre **Java** et **JavaScript**

  - Réponse : _JavaScript est un langage **front-end**, Java est un langage **back-end**_.  
    _Le seul point commun est qu'ils sont tout les deux de type C_.  
    _Le nom d'origine de JavaScript était **LiveScript**, il a peut-être été modifié pour bénéficier de la notoriété de Java_.

- Combien de façon existe t'il pour lier un fichier **JavaScript** à un fichier _HTML_?

  - Réponse : _Il en existe_ **2**.

- Comment lié un fichier **JavaScript** à un fichier _HTML_ ?

  - Réponse : _Soit avec la méthode dite **inline** , c'est à dire en insérant directement du code JavaScript vià une balise _`<script></script>`_.
    \_Soit avec la méthode dite **external** , c'est à dire d'insérer le fichier via une balise_ `<script type="text/javascript" src="monscript.js"></script>`.

- Quel est le but de la fonction "_alert_"?

  - Réponse : _La fonction **alert** sert à afficher un message à l'utilisateur dans la fenêtre courante_.

- Completez moi cette définition avec le ou les bons termes : Une variable est un “\_**\_” pour y stocker de la \_\_\_** .

  - Réponse : _Une variable est "**entrepôt nommé**" pour y stocker de la **donnée**_.

- Donnez moi les **3 mots-clés** servant à créer une **variable**.

  - Réponse : **Let, Var _et_ Const**.

- Quel **mot-clé** faut-il utiliser pour créer une variable birthdayDate ?

  - Réponse : _Le mot-clé **const**._

- Pour bien nommé vos **variables**, quelle méthode faut-il utiliser ?

1. La kebabCase
2. Le camelCase
3. Le snakeCase
   - Réponse : _Le **camelCase**_

- Vrai ou faux : Les symboles "\$" et "_", peuvent être utilisés pour déclarer un nom de variable ?

  - Réponse : _Vrai_

- Où est l'erreur dans cette partie de code et corrigez la :

  ```let name;
   name = "Maëlys;
   let 1age;
   age = "1 an";
  ```

  - Réponse : _Le 1 devant age. Un nom de variable ne peut pas commencer par un digite_.

- Vrai ou faux : C'est deux variables sont les mêmes : yesWEweb et yEsWeWeb ?

  - Réponse : _Faux. Le code est sensible à la casse en JavaScript_.

- Combien de types de **types de données** existent-ils en JavaScript ?

1. 10
2. 4
3. 7
   - Réponse : _Il existe 7 types de données en JavaScript_

- Que veux dire **l'acronyme NaN** ?

  - Réponse : _Il signifie Not a Number_

- Quels sont **les différents types de quotes** ?

  - Réponse : _Le double quote ", le simple quote ', et le backticks_

- Vrai ou faux : **True** est le résulat d'un type boolean?

  - Réponse : _Vrai, le type boolean retourne deux valeurs, True et False_

- À quoi correspond **Null** ?

  - Réponse : _Null correspond à une valeur qui représente soit une valeur vide, ou une valeur inconnue_

- A quoi peut bien servir **l'undefined value** ?

  - Réponse : _En JavaScript nous nous servons de l'undefined value, afin de savoir si une variable a été déclarer_

* Comment sont appellés tout les types de données n'étant pas de **type objet ou symbole** ?

  - Réponse : _Ils sont appellés primitive_

* Que retournera ce code : `typeof alert` ?

  - Réponse : _Ce code nous retournera fonction, le typeof operator nous retourne le type de données d'une variable_

- À quoi sert `String(value)` ?

  - Réponse : _Il convertit la valeur d'une variable en type **String**_

- Vrai ou faux : `alert("6" / "3")` nous retournera comme résultat "2" ?

  - Réponse : _Faux, les opérateur - , * , /, % convertissent les string en Number_

- Que nous retournera cette fonction `alert (Numer("toto"));` ?

  -Réponse : _Elle nous retourner la valeur NaN car "toto" ne peut être convertit en nombre_

- Qu'est ce que la **concatenation** ?

  - Réponse : _La concaténation, ou la fusion est le résultat d'une fusion de deux **String** ainsi que l'opérateur **+**_

- Sachant que **ToBoolean** convertie la valeur d'une variable en boolean, que nous retrounerait cette fonction `alert( Boolean("") );` ?

1. 1
2. True
3. False
   - Réponse : _False, car le **String** est vide_

- Dans cette opération, donnez moi, le ou les **opérateurs**, **opérands** : "7" + 4 - "toto"

  - Réponse : _Les opérateurs sont : **+ -** et les opérands sont **"7" 4 "toto"**_

- Complétez cette definition : Un _ est **unary** si il possède ___.

  - Réponse : _Un **opérateur** est unary si il possède **un seul operand**_

- Cette opération est elle un **unary**, si oui de quel type d'unary s'agit-il ? `let x = 7; x = -x; alert(x);`

      - Réponse : _Cette opération est bien un unary car elle ne possède qu'un seul operand, et elle est de type négatif ou soustractive (-)_

- Cette opération est elle un **unary**, si ce n'est pas le cas de quel type s'agit-il ? `let x = 7 y = 9; alert(x+y);`

  - Réponse : _Non il s'agit en revanche d'un binary positif car celui ci possède deux operands et le signe +_

- Vrai ou Faux : **+x** ou **-x** sont des raccourcis à **Number(x)** ?

  - Réponse : _Vrai, ce sont tout deux unary qui convertissent en nombre la valeur d'une variable_

- Voici un morceau de code : `let apples = "2"; let oranges = "3"; alert( apples + oranges );` Qui nous retourne comme résultat **23**, pourquoi ne nous retourne t'il ça et comment pouvons nous avoir pour résulat **5** ?

  - Réponse : _Il nous retourne **23** car il y'a eu concatenation de deux **String** avec l'opérateur **+**. Pour en revanche avoir comme résultat **5**, nous devrions convertir ces **String** en Number de la sorte `.... alert(+apples + +oranges);`_

- À quoi pouvons nous comparer la **précendence** de JavaScript ?

  - Réponse : _Nous pouvons la comparer à la **spécification** en CSS_

- Qu'allons nous avoir comme résultat à cette opération : `alert("2" + "7"(10 / 5))`

1. "214"
2. NaN
3. "2714"

   - Réponse : _"214"_

- Vrai ou Faux : L'opérateur **=** à une précedence supérieur à la **()**

  - Réponse : _Faux, l'opérateur = à une précédence de **3** tandis que la () une précédence de **20**_

- Le modulo nous retourne :

1. Le résultat d'une division euclidienne
2. Null
3. Le reste d'une division euclidienne

   - Réponse : _Le reste d'une division euclidienne_

- Quel est le résulat de 10 % 3 ?

  - Réponse : _1, 10 / 3 = 3 + **1**_

- Qu'est ce que **++** ou **--** ?

    - Réponse : _Il s'agit de l'incrémentation (+1) et de la décrémentation (-1)_

- Ceci : `alert (++x)` est ce la version **postfixe** ou **prefixe**  et que retourne t'elle ?

    - Réponse : _Ceci est la version prefixe, elle retourne la nouvelle valeur_

- Quel résulat va nous être retourné avec ce code ` let x = 1; alert(x++);` ?

1. 0
2. 1
3. 2
    - Réponse : _1 est le résultat qui va nous être retourner car x++, nous affiche d'abord x puis ensuite incrémente_

- Quel résulat va nous être retourné par le deuxième alert() avec ce code ` let x = 1; alert(x++); alert(++x)` ?

1. 1
2. 3
3. 2
    - Réponse : _3 car il y'a eu deux incrémentations_

- Quel serait le raccourci pour dire ` let n = 5; n = n * 5;`

    - Réponse : _Le raccourci pouvant nous dire n = n * 5 est le suivant : **n*=5**_

- Vrai ou faux : ce code va nous retourner 10 : `let n = 2; n+=4; alert(n+=4);`

    - Réponse : _Vrai, car nous ajoutons 4 à n donc 2 + 4 = 6 puis nous rajoutons de nouveau à n 4 donc 6 + 4 = 10_
