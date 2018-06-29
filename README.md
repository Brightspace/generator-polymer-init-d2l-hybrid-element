# generator-polymer-init-d2l-hybrid-element

Template for creating BrightspaceUI Polymer `1.x`/`2.x` hybrid elements.

With the template, you get:
* Project boilerplate including: `.editorconfig`, `.gitignore`, `bower.json`, `package.json`, `polymer.json`, `CODEOWNERS` and `LICENSE` (Apache-2.0)
* A basic Polymer hybrid element scaffold
* Demo page for the element
* Test page for the element
* Travis CI ready-to-go
* Local tests that do linting using ESLint, `polymer lint` and unit tests using Chome headless
* Cross-browser testing from Travis CI using Sauce Labs
* README

## Setup

Assuming you have Node.js already, install `polymer-cli`, [Bower](https://bower.io/) and the hybrid element generator globally:

```shell
npm install -g polymer-cli
npm install -g generator-polymer-init-d2l-hybrid-element
```

In an empty project directory, run the CLI's `init` command:

```shell
mkdir my-element
cd my-element
polymer init
```

Choose `d2l-hybrid-element` from the list and follow the prompts.

Alternately, you can jump right into the wizard:

```shell
polymer init d2l-hybrid-element
```

That's it! Follow the instructions in the `README` to learn how to get a local development server running and run the tests.
