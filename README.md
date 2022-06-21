# cypress-cucumber-typescript-example
Example of using Cypress with Cucumber and TypeScript + Xpath + reports (html, json)

install :
npm install

command :
npm test

Open cypress :
npx cypress open

All the configuration is in [cypress/plugins/index.js](cypress/plugins/index.js)

TypeScript step definitions are in [cypress/integration/passWithTypescript](cypress/integration/passWithTypescript)

(I'm using the nonGlobalStepDefinitions configuration in the [package.json](package.json) )

You can also use our Cucumber plugin with TypeScript and webpack: [https://github.com/TheBrainFamily/cypress-cucumber-webpack-typescript-example/](https://github.com/TheBrainFamily/cypress-cucumber-webpack-typescript-example/)
