# Shoe-Shop
> This is a markup of [VictorThemes](https://victorthemes.com/freebies/ecommerce-website-template/)'s template

## Preview
![Website preview](build/img/preview.png)

### How to run this project?
Just clone this repository into any directory and open "index.html" file
or just simply [see](https://p1xar.github.io/Shoe-Shop) online

### Contribution
Contributions are always **welcome and recomended**. Here is how:
* Fork a repository ([here's how](https://help.github.com/en/articles/fork-a-repo));
* Clone to your directory ```https://github.com/p1xar/Shoe-Shop```;
* Make a changes;
* Create a pull request.

## Requirments
For development, you will only need Node.js installed on your environement

#### Node installation on OS X

You will need to use a Terminal. On OS X, you can find the default terminal in
`/Applications/Utilities/Terminal.app`.

Please install [Homebrew](http://brew.sh/) if it's not already done with the following command.

    $ ruby -e "$(curl -fsSL https://raw.github.com/Homebrew/homebrew/go/install)"

If everything when fine, you should run

    brew install node

#### Node installation on Linux

    sudo apt-get install python-software-properties
    sudo add-apt-repository ppa:chris-lea/node.js
    sudo apt-get update
    sudo apt-get install nodejs

#### Node installation on Windows

Just go on [official Node.js website](http://nodejs.org/) & grab the installer.
Also, be sure to have `git` available in your PATH, `npm` might need it.

### Install dependencies
    $ git clone https://github.com/p1xar/Shoe-Shop
    $ cd Shoe-Shop
    $ npm run start

## Language and tools
### HTML 5
  - [BEM Methodology](https://en.bem.info/) to make reusable interface components;
### CSS 3
  - [Node SASS](https://www.npmjs.com/package/node-sass) to compile SASS into CSS;
  - [Autoprefixer](https://www.npmjs.com/package/autoprefixer) to add vendor prefixes to CSS rules;
  - [CSSO-cli](https://www.npmjs.com/package/csso-cli) to minify CSS;
### Javascript
  - [JSHint](https://www.npmjs.com/package/jshint) to prevent JavaScript errors;
  - [UglifyJS](https://www.npmjs.com/package/uglify-js) to minify JavaScript files;
  - [nodemon](https://www.npmjs.com/package/nodemon) to watch for changes in files and restart npm scripts.
