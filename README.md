# Next.js + Jest

This example shows how to configure Jest to work with Next.js.

This includes Next.js' built-in support for Global CSS, CSS Modules and TypeScript. This example also shows how to use Jest with the App Router and React Server Components.
Cliquez sur Settings (en haut à droite).

Dans le menu de gauche, descendez jusqu'à Secrets and variables > Actions.

Cliquez sur New repository secret (Nouveau secret de dépôt).

Créez deux secrets :

Secret 1 :

Name : DOCKERHUB_USERNAME

Secret : bahaj (votre nom d'utilisateur Docker Hub)



> **Note:** Since tests can be co-located alongside other files inside the App Router, we have placed those tests in `app/` to demonstrate this behavior (which is different than `pages/`). You can still place all tests in `__tests__` if you prefer.

## Deploy your own

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/vercel/next.js/tree/canary/examples/with-jest&project-name=with-jest&repository-name=with-jest)

## How to Use

Quickly get started using [Create Next App](https://github.com/vercel/next.js/tree/canary/packages/create-next-app#readme)!

In your terminal, run the following command:

```bash
npx create-next-app --example with-jest with-jest-app
```

```bash
yarn create next-app --example with-jest with-jest-app
```

```bash
pnpm create next-app --example with-jest with-jest-app
```

## Running Tests

```bash
npm test
```


Voici le cycle de travail standard que nous avons reproduit ensemble, et qui est utilisé par tous les développeurs professionnels :

On part de main (le code qui fonctionne).

On crée une branche (ma-nouvelle-fonctionnalite). C'est notre espace de travail isolé.

On modifie le code (votre commentaire dans le README).

On pousse la branche sur GitHub (git push).

On crée la Pull Request : On demande à GitHub de comparer notre branche avec main.

GitHub fait les vérifications (il lance vos Actions).

On fusionne (Merge) si tout est bon.

On supprime la branche devenue inutile.


