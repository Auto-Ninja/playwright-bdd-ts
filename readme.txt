Install VS code extension 
    Playwright Test for VSCode - v1.1.12
Install Playwright (https://playwright.dev/docs/intro#installing-playwright)
    npm init playwright@latest
Running test example
    npx playwright test
Show HTML report
    npx playwright show-report
Run Test in UI mode
    npx playwright test --ui

Set up BDD (https://vitalets.github.io/playwright-bdd/#/getting-started/installation)
npm i -D playwright-bdd

map the feature file and steps definition in playwright.config.ts

To shorten the test run command , set the "npx bddgen && npx playwright test"  in package.json script tag;
    Run > npm test 

