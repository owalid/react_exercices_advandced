# todo advanced

Reprennez le code de votre application de todo list et ajoutez les fonctionnalités suivantes:

# Context

- Créer un nouveau composant `TodoContext` qui contiendra le state de toute votre application.
- Utiliser `useReducer` pour gérer le state de votre application.

# custom hooks

- Créer un dossier hooks, et créer des customs hooks.
- Par exemple, vous pouvez créer un hook `useFetch` qui permet de faire des requêtes http.

# react-router

Ajouter les librairies suivantes:
```
npm i react-router react-router-dom
```

- Restructurer votre application en ajoutant un dossier pages.
- Separer vos composants en pages d'edition, de creation, de liste et de detail pour chaque tache.
- Crée un nouveau composant Navbar qui contient les liens vers la page de creation et la home page
- Utiliser `react-router` pour naviguer entre ces pages
- Pour la page de detail d'un todo. Penser à utiliser `useParams` pour récupérer l'id du todo dans l'url.
- Lorsque vous soumettez le formulaire d'edition ou de creation, vous devez rediriger vers la page d'accueil.