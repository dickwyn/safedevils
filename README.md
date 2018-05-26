## testorange safe

testorange-safe application. Built with the SafeTrek API

## Project Dependencies

This project is built with:

1. SafeTrek
2. [NodeJS](http://nodejs.org)
3. [Angular](https://angular.io/) - `$ npm install @angular/cli -g`
4. [GulpJS](https://gulpjs.com/) - `$ npm install gulp-cli -g`
5. [PugJS](https://pugjs.org/api/getting-started.html) - `$ npm install pug`

## Running the Project

**Get Started**

1. Clone or download this repository
2. `$ npm install` on the directory

**Development Mode**

1. `$ gulp`
2. Browsersync can be accessed through `localhost:5000`

**Production Mode**
1. `$ gulp deploy

## Folder Structure

    .  
    ├── public              # All additional assets of the projects
    │   ├── assets          # All stylesheets (.css and .scss)
    │   ├── scripts          # All images used by the project
    │   ├── styles          # All unprocessed .scss files
    │   └── └── src         # All unprocessed .scss files
    ├── .gitattributes
    ├── .gitignore          # Folders and files that are ignored by git
    ├── README.md           # Readme file for repository
    ├── gulpfile.js         # Automate compilation of pug, sass and jekyll
    ├── index.js            # main entry point
    ├── package-lock.json
    └── package.json        # Document node dependencies
