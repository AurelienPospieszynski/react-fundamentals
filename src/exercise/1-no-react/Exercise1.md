# JS sans React

Cet exercice va t'aider à mieux comprendre où React apporte de la valeur.
On va commencer en faisant du React... sans React...

Puis, dans l'exercice 2, on va modifier ce code AVEC React sans JSX.

Oui, on va faire du simple JavaScript avec la gestion du DOM.

1. Pour te rafraîchir la mémoire
2. Pour mieux comprendre React par la suite !

## Exercice

Le but est tout simplement d'afficher une div sur la page, juste avec du JavaScript.

⚠️ Le `innerHtml` est interdit.

💌 Tu apprends à afficher un élément en utilisant JavaScript uniquement.

## Extra 2 - Interaction avec des events

Quand tu cliques sur notre div "Hello", il t'affiche une `alert`
avec `Tu as cliqué sur Hello !` !

Regarde-le résultat de la solution 2 (pas le code, mais le rendu) et essaie de cliquer sur la div.

[📖 addEventListener](https://developer.mozilla.org/fr/docs/Web/API/EventTarget/addEventListener)

💌 Tu apprends à gérer un événement sans React.

## Extra 3 - Composants sans React

Maintenant, crée un composant "Counter" qui affiche un bouton. Quand tu cliques sur le bouton,
le compteur doit s'incrémenter d'un.

Tu pourras ajouter ce composant à la div "root". Il faut savoir que ce composant doit être une fonction,
qui peut être appelée plusieurs fois si besoin.

Voici le début du code pour t'aider :

```js
const Counter = (initialValue) => {
  const button = ''; // 🦁 remplace "" par la création d'un bouton
  // 🦁 Ajout du text
  // 🦁 Ajout de l'event
  return button;
};
```

⚠️ Il faut ajouter une valeur par défaut pour notre button (`initialValue`).

Ajoute deux counter à ta page pour vérifier que ton "composant" fonctionne
même plusieurs fois.

Regarde-le résultat de la solution 3 et essaie de cliquer sur la div.

💌 Tu apprends à faire des composants sans React !

## Extra 4 - Afficher une liste

Voici un tableau de fruits :

```js
const fruits = ['banana', 'apple', 'strawberry'];
```

Sous nous boutons, ajoute une liste (`ul`) avec chacun de
nos fruits (`li`) !
