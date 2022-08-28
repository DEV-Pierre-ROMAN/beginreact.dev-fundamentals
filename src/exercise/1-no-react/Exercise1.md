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

## Exercice 2

Quand tu cliques sur notre div "Hello", ajoute un cœur sur la page.

Regarde-le résultat de la solution 2 (pas le code, mais le rendu) et essaie de cliquer sur la div.

💌 Tu apprends à gérer un événement sans React.

## Exercice 3

Maintenant, crée un composant "Counter" qui affiche un bouton. Quand tu cliques sur le bouton, 
le compteur doit s'incrémenter d'un.

Tu pourras ajouter ce composant à la div "root". Il faut savoir que ce composant doit être une fonction, 
qui peut être appelée plusieurs fois si besoin.

Voici le début du code pour t'aider :

```js
const Counter = () => {
  const button = ''; // remplace "" par la création d'un bouton
  button.addEventListener('click', () => {
    /* increment counter */
  });
  return button;
};
```

Ajoute deux counter à ta page pour vérifier que ton "composant" fonctionne 
même plusieurs fois.

Regarde-le résultat de la solution 3 et essaie de cliquer sur la div.

💌 Tu apprends à faire des composants sans React !
