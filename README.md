# challenge-interview
Welcome to Ricky and Morty challenge. The main goal of this challenge is to implement a simple application using the given project scaffolding which have in advance [Next.js](https://nextjs.org/), [Storybook](https://storybook.js.org/) and [Jest](https://jestjs.io/). To get the needed information, you should use the [Ricky and Morty](https://rickandmortyapi.com/documentation) API, and you'll be free to choose between REST or GraphQL.

Before start the challenge, we suggest to `fork` this repository to your own github workspace.


# Acceptance Criteria

- Allow users to see all available characters

- When user choose one character, should be redirected to his specific page, showing his base information

- Should have a pagination mechanism (infinite loading or basic pagination)

- Each component should have unit tests

- Each component should have his own story representation

- Use [Ricky and Morty](https://rickandmortyapi.com/documentation) API. You're free to choose between GraphQL or REST.


# Getting started
## Instalation
Install the dependencies so you can run the project
```bash
npm install
```

## Start project
First, run the development server and open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

```bash
npm run dev
```
## Start storybook
First, run the development server and open [http://localhost:6006](http://localhost:6006) with your browser to see the result.

```bash
npm run storybook
```
## Running tests
```bash
npm run test
```


## Deploy on Vercel
We strongly suggest to deploy the application through the Vercel platorm, so we can easily check the final result. Please check the link [documentation](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme), give permission to your github workspace, and you just need to import the project.