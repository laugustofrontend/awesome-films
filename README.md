# Started Kit React

> development web app of films

## Stack Project
- Module Bundle [Webpack](https://webpack.js.org)
- Framework JS [ReactJS](https://reactjs.org)
- Pre-processor Sass [Sass](https://sass-lang.com)

## Structure Folder
    .
    |_ src/
    |   |_ App/
    |   |   |_ App.jsx
    |   |_ assets/
    |   |   |_ sass
    |   |   |   |_ partials/
    |   |   |   |   |_ _grid.scss
    |   |   |   |   |_ _placeholders.scss
    |   |_ Films/
    |   |   |_ film-detail.jsx
    |   |   |_ film-genres.jsx
    |   |   |_ film-input.jsx
    |   |   |_ film-item.jsx
    |   |   |_ film.jsx
    |   |   |_ film.scss
    |   |_ services/
    |   |   |_ api.js
    |   |_ index.jsx
    |_ .babelrc
    |_ .gitignore
    |_ package.json
    |_ README.md
    |_ webpack.config.js
    |_ yarn.lock
    |

## Run the project locally
**1 -** Prepare the enviroment
```sh
$ yarn add --global webpack webpack-cli
```
**2 -** Clone the project and install dependencies:
```sh
$ git clone https://github.com/laugustofrontend/starter-kit-react.git
$ cd starter-kit-react
$ yarn install
```
**3 -** Run static server and livereload
```sh
$ yarn run dev
```
