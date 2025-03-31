# Test-project

This test project was generated via the Cypress GUI.

This project can be updated to the latest Cypress default scaffolded E2E test specs by carrying out the following steps in the directory `/test-project`:

```shell
rm -rf cypress cypress.config.js
npm install cypress@latest --no-package-lock
npx cypress open
```

- Select "Continue" for "What's New in Cypress" if displayed
- Select "E2E Testing"
- Select "Continue" in "Configuration files"
- Select "Electron" browser
- Select "Start E2E Testing in Electron"
- Select "Scaffold example specs"
- Close all Cypress windows

Test that scaffolded specs run:

```shell
npm test
```

Remove Cypress from `package.json`:

```shell
npm uninstall cypress --no-package-lock
```

## Tests

Tests are run via [circle.yml](../circle.yml).
