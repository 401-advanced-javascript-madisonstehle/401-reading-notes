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
- **ecosystem**: We run code in an ecosystem. It contains compilers that interpret our code and do some admin work so it runs correctly
- **Node.js**: Node runs JS code - one language for font-end and back-end. Has a lot of packages from other developers that you can easily install
- **V8 Engine**: Google's high performant open-source program that runs JS code. It powers the Chrome web browsers
- **module**: a self-contained piece of code, meant to be imported and called
- **package**: packages have a package.json file. Node uses this to figure out what dependencies to install, how to run your code (which file to run), and any custom scripts developers might want. _packages_ = _modules_ + _dependencies_ + _scripts_
- **npm**: node package manager. Allows us to install packages from external developers and maintain package versions and updates
- **Test Driven Development (TTD)**: Conceptually break up yor planned code into small segments, or _units_. Three steps are writing tests before code is written, writing code the quick way until all tests pass, clean up your code while checking that tests pass along the way
- **jest**: a package that makes it very siimple to test JS code. It is installed globally. We describe a collection of tests, for each test, we say what it does. Within each test, we expect something to be a certain result
- **Continuous Integrationj (CI)**: for every code change, treat it like a complete build. Run all tests and merge with master
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
3. **What is one benefit of Test Driven Development?** Test Driven Development (writing tests for your code before writing the code itself) can help prevent uncertainty during the development process. It also helps to ensure that the application is written for testability. It forces developers to plan ahead, makes refactoring simple, and makes it easier to catch mistakes.
4. **What is one potential downside of Test Driven Development?** When unit tests created are created by the developer who is writing the code being tested, there may be blind spots in the code. It is time consuming, some unit tests can be redundant, and it may not be possible to plan code ahead of time.
5. **What does the node package manager do?** npm is a software registry that allows developers to share and borrow packages. It can also be used to manage private development. npm consists of three components: website, CLI, and registry.


[Back to Home](README.md)