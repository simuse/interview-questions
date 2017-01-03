# Javascript

## Basic
- est-ce que javascript est sensible à la casse ?
- la différence entre `"=="` et `"==="` ? la bonne pratique ?
- est-ce qu'il y a des arrays associatifs en JS ? alternative ?
- comment créer un objet ? comment y assigner/lire une propriété ?
- `var obj = {}`
    - `var obj = new Object()`
    - `obj.key = value`
- quand utiliser `var` lors de la déclaration d'une variable ?
- qu'est-ce qu'un callback ?
- explique moi le sens de `this`
    - le contexte dans lequel s'exécute une méthode
    - défaut est `window`
    - ...
- qu'est-ce que le scope d'une variable ? quels sont possibles ?
    - global (window)
    - local (inside a function)
    - no block-scope (inside if)
- qu'est-ce que le 'hoisting' ?
    - les déclarations de fonctions/variables sont silencieusement déplacées tout au dessus du scope
- explique-moi strict mode
    - meilleur debugging
    - empêche les variables globales par accident
    - répond par une erreur dans certains cas qui précédemment ne le faisaient pas
    - répond par une erreur sur une action "non-safe"
    - permet certaines optimisations des moteurs, evitant certaines erreurs

## Intermediaire
- comment transformer un string en nombre ?
    - `parseInt("1000")`
    - `+"1000"` - unary plus
    - `Number("1000")`
    - `~~"1000"`
- comment vérifier si une variable est un objet ?
    - `if (bar !== null) && (typeof bar === "object")`
    - piège: null est aussi considéré un objet
- quelle est la différence entre `"1"+2+3` et `1+2+"3"` ?
    - 123 et 33
- quelle méthode interne permet de trouver l'index de la première occurence d'un charactère dans un string ?
    - `str.indexOf(search)`
- quelle méthode interne permet d'ajouter un élément à la fin d'un array ?
    - `arr.push(element)`
- quel est l'intérêt d'englober tout un code JS dans une fonction ?
    - `(function() { /* code */ } )();`
- qu'est-ce qu'une 'closure' ?
    - une fonction qui utilise des variables d'une fonction parente, utilisées localement, mais définies dans la portée englobante, autrement dit, la fonction interne capture son environnement
    - on les utilise pour assurer que des datas restent dans un scope privé
    - un exemple pratique ?
- une 'fonction pure' est une fonction qui ?
    - pour un input donné, donnera toujours le même output
    - n'a pas d'effet secondaire
    - ne dépend pas de données externes

## Extra
- à quoi sert jQuery ? examples de fonctions ?
    - avantages/désavantages
    - alternative
- qu'est-ce que ES6/ES2015 ?
    - babel
    - examples de nouveauté
- quels frameworks existent ? avec lesquels as-tu travaillé ?
    - angular
    - ember
    - react
    - backbone
    - ...

## Tricks
- quel est le résultat de [1] + [2] - [3] ?
    - 9
    - [coercion](https://github.com/getify/You-Dont-Know-JS/blob/master/types%20%26%20grammar/ch4.md): "1" + "2" - "3" = 12 - "3" = 9 
