# Javascript

## Basic
- est-ce que javascript est sensible à la casse ?
- la différence entre `"=="` et `"==="` ? la bonne pratique ?
- est-ce qu'il y a des arrays associatifs ? alternative ?
- comment créer un objet ? comment y assigner/lire une propriété ?
- `var obj = {}`
    - `var obj = new Object()`
    - `obj.key = value`
- quand utiliser `var` lors de la déclaration d'une variable ?
- qu'est-ce qu'un callback ?
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
- explique moi le sens de `this`
    - le contexte dans lequel s'exécute une méthode
    - défaut est `window`
    - ...
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
