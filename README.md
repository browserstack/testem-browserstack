# testem-browserstack

[Testem](https://github.com/testem/testem) Integration with BrowserStack.

## Setup

- Clone the repo
- Install dependencies `npm install`
- Update `testem.json` file with your BrowserStack Username and Access Key. (These can be found in the [settings](https://www.browserstack.com/accounts/settings) section on BrowserStack accounts page)
- Alternatively, you can export the environment variables for the Username and Access Key of your BrowserStack account. `export BROWSERSTACK_USERNAME=<browserstack-username> && export BROWSERSTACK_ACCESS_KEY=<browserstack-access-key>`

### Run the tests

- To run single test, run `npm run single`
- To run parallel tests, run `npm run parallel`

### Notes

- In order to test on different set of browsers, check out our [code generator](https://www.browserstack.com/automate/python#setting-os-and-browser)
