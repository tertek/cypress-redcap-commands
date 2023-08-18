# cypress-redcap-commands

still unpublished

A REDCap command library that helps to create e2e tests.


## Table of Contents

- [Installation](#installation)
- [Usage](#usage)


## Installation

The package is distributed via [npm][npm] and should be installed as one of your project's `devDependencies`:

```bash
npm install --save-dev cypress-redcap-commands
```

or

```bash
yarn add cypress-redcap-commands --dev
```

## Usage

`cypress-redcap-commands` extends Cypress' `cy` command.
Add this line to your project's `cypress/support/commands.js`:

```javascript
import 'cypress-redcap-commands'
```

Now you are ready to use the command. Here is a basic example:

```javascript
cy.login('user', 'pass')
```


## License

[MIT][mit]

[cypress]: https://cypress.io
[mit]: https://opensource.org/licenses/MIT
[npm]: https://www.npmjs.com/
