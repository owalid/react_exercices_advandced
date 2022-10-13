# Router

- Créer un nouveau projet
```
npx create-react-app router-example
cd router-example
npm i react-router react-router-dom
npm start
```

- Créer un dossier `pages` et y ajouter les pages suivantes:
  - `Home.js` (`/`) sera la page d'accueil vous afficherez un titre quelquonque. 
  - `Create.js` (`/create`) sera une page de création avec un formulaire, vous afficherez un titre quelquonque.
  - `Detail.js` (`/detail/:id`) sera une page de détail (il prendra un id en paramètre), vous afficherez un titre quelquonque et le paramètre id.
  - `NotFound.js` (`*`) sera une page 404, vous afficherez un titre quelquonque.

- Créer un dossier `components` et y ajouter le composant `Navbar.js` qui contiendra un lien vers chaque page. utilisez un nombre aléatoire pour l'id de la page `Detail.js`.
