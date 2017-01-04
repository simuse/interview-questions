# PHP

## Basic
- différence entre `include()` et `require()` ?
- comment récuperer les infos envoyées par un formulaire ?
    - différence entre GET et POST
- disons que le champ 'email' est obligatoire, comment tester s'il a été rempli ? 
    - `if (!empty($_POST['email'])) {}`
- que fait la fonction `in_array()` ?
- quels types de loops existent ?
    - for, while, do while, foreach
- comment faire une concaténation ?
- la différence entre une constante et une variable ?
- quels sont les types d'erreurs que PHP peut signaler ?
    - notices, warning, fatal
- comment connaître le nombre d'éléments dans un array ?
    - `count()`
- comment créer une constante ?
    - `define(KEY, $value)`
- que signifie `$_SERVER` ?

## OOP
- en orienté objet, comment fonctionne une classe ?
    - `class SimpleClass {}`
    - `__contruct()`
- qu'est-ce que l'héritage ?
- que veut dire le mot clé `final` en OOP ?

## Intermediaire
- quelle est la différence entre mysql et PDO ?
- quelle est la différence entre `mysql_fetch_array` et `mysql_fetch_object` ?
    - object retourne le premier élément qui match
    - array retourne la collection
- qu'appelle-t-on l'opérateur de condition ternaire ? example ?
    - `$variable = isTrue() ? true : false`
- avec quelle fonction lis-tu un fichier sur le serveur ?
    - `file_get_contents()`
- quelle est la différence entre `unlink() ` et `unset()` ?
    - supprime un fichier / supprime une variable
- quelles méthodes de hashing sont recommandées ?
    - `crypt()`
    - `hash()`
- comment faire persister des datas d'une page à l'autre ?
    - session, cookies, database, post
- que veut dire MVC ?

## Symfony
- en quelques phrases, explique-moi ce qu'est Symfony, et ses avantages ?
- quelles sont les tâches exécutées par un Controller ?
    - recoit une HTTP Request, retourne une HTTP Response (une page HTML, XML, JSON, image, redirect, error page)
- quel est le rôle du routing ?
- le fichier de configuration du routing peut être écrit en PHP, YAML, XML ?
    - tous sont correct. par défaut: app/config/routing.yml
- pour utiliser la méthode `render()` dans un controller, tu dois étendre quelle classe ?
    - `Controller`

