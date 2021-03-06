# ember-cli-twitter-typeahead

[![Build Status](https://travis-ci.org/thefrontside/ember-cli-twitter-typeahead.png?branch=master)](https://travis-ci.org/thefrontside/ember-cli-twitter-typeahead)




This is an ember wrapper for Twitter's JQuery Typeahead. It's packaged as a
simple ember cli add on. All you have to do is use `npm install --save
ember-cli-twitter-typeahead` and you'll be able to use the typeahead helper in
your ember-cli app.

## Prerequisites

You will need the following things properly installed on your computer.

* [Git](http://git-scm.com/)
* [Node.js](http://nodejs.org/) (with NPM) and [Bower](http://bower.io/)
* [Twitter Typeahead](https://github.com/twitter/typeahead.js/) via Bower

## Usage

To use this in your app, simply use:
```javascript
{{twitter-typeahead
content=arrayOfDataForTypeahead
filterContent=filterContentFn
displayKey="propertyToDisplay"
valueToken="propertyForValue"
footerTemplate=handlebarsFooterTemplate
emptyTemplate=handlebarsEmptyTemplate
on-select-without-match="ActionToRunWhenEnterIsHitWithoutAMatch"
}}
```


## Installation

* `npm install --save ember-cli-twitter-typeahead`

### Running Tests

To develop and test locally, simply clone the repository and run:
* `ember test`
* `ember test --server`

## Further Reading / Useful Links

* ember: http://emberjs.com/
* ember-cli: http://www.ember-cli.com/
