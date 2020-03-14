# Class-01
## npm & Node.js


### Links
- [About npm](https://docs.npmjs.com/about-npm/index.html)
- [Jest API Docs](https://jestjs.io/docs/en/getting-started)
- [V8 Engine Docs](https://v8.dev/docs)
- [Wiki - Test Driven Development](https://en.wikipedia.org/wiki/Test-driven_development)
- [GitHub Actions Docs](https://help.github.com/en/actions)
- [Continuous Integration, Delivery, and Deployment](https://www.atlassian.com/continuous-delivery/principles/continuous-integration-vs-delivery-vs-deployment)
- [Node.js Modules](https://nodejs.org/docs/latest/api/modules.html)


### Vocabulary
- **ecosystem**
- **Node.js**
- **V8 Engine**
- **module**
- **package**
- **npm**
- **Test Driven Development (TTD)**
- **jest**
- **Continuous Integrationj (CI)**
- **unit test**


### Code Snippets
- `npm init` | Initializes a package with a package.json file
- `npm start` | Executes the “start” script within the package.json file
- `npm test` | Executes the “test” script within the package.json file
- `npm install <package>` | Installs a specified <package> onto the current package
- `npm install -g <package>` | Installs a specified <package> for the entirety of Node.js on your machine
- `node <file>` | Runs a specified <file> using the Node.js ecosystem


### Discussion Questions
1. **Why would you want to run JavaScript code outside of a browser?** We can "do a lot more with JavaScript aside from simple websites" by using a new environment (aka _ecosystem_) called Node.js. By doing this, we can work with databases, APIs, events, triggers, etc.
2. **What is the difference between a module and a package?** A _module_ is a piece of JS code that is meant to be called in another file. It doesn't run until it's called. A _package_ is an extension of modules.
3. **What is one benefit of Test Driven Development?** Test Driven Development (writing tests for your code before writing the code itself) can help prevent uncertainty during the development process. It also helps to ensure that the application is written for testability.
4. **What is one potential downside of Test Driven Development?** When unit tests created are created by the developer who is writing the code being tested, there may be blind spots in the code.
5. **What does the node package manager do?** npm is a software registry that allows developers to share and borrow packages. It can also be used to manage private development. npm consists of three components: website, CLI, and registry.


[Back to Home](README.md)