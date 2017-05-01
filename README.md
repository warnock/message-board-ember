## Seek & Find

#### By Megan Warnock

### Description
Seek & Find is a message-board website that allows users to post technical questions and get them answered by the Seek & Find community.

### Prerequisites

You will need the following things properly installed on your computer.

* [Git](https://git-scm.com/)
* [Node.js](https://nodejs.org/) (with NPM)
* [Bower](https://bower.io/)
* [Ember CLI](https://ember-cli.com/)
* [PhantomJS](http://phantomjs.org/)

### Installation
This application also uses a Firebase database. If you want to connect using your own database create a new Firebase application and configure the settings in the environment.js file found in the config folder:

`firebase: {
  apiKey: "YOUR API KEY",
  authDomain: "YOUR AUTH DOMAIN",
  databaseURL: "YOUR DATABASEURL",
  storageBucket: "YOUR STORAGEBUCKET",
},`

In your terminal run these commands:
* `git clone <https://github.com/warnock/message-board-ember.git>` this repository
* `cd message-board`
* `npm install`
* `bower install`

### Running / Development

* `ember serve`
* Visit your app at [http://localhost:4200](http://localhost:4200).

### Code Generators

Make use of the many generators for code, try `ember help generate` for more details

### Building

* `ember build` (development)
* `ember build --environment production` (production)

### Further Reading / Useful Links

* [ember.js](http://emberjs.com/)
* [ember-cli](https://ember-cli.com/)
* Development Browser Extensions
  * [ember inspector for chrome](https://chrome.google.com/webstore/detail/ember-inspector/bmdblncegkenkacieihfhpjfppoconhi)
  * [ember inspector for firefox](https://addons.mozilla.org/en-US/firefox/addon/ember-inspector/)

### Support or contact details

Contact Megan at megandwarnock@gmail.com if any questions.

### License

Copyright (c) 2017 **_MIT License_**
