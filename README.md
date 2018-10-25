# Project description

The project was to implement the web design according to the specifications. We were supposed to employ various tools such as `browser-sync`, `node-sass` `stylelint` etc.

## How to run the project
### Run procedure:
* Pull/clone all of the content to the local .git repository;
* Go to this folder through command line interface (CLI);
* Run command `npm install` inside the folder;
* Run command `npm run dev`. This will start the server in the browser where the project can be inspected.

### Project set up
The project has `index.html` for the front page and `styles.css` for styles file. Files such as `package.json` and `package-lock.json` contain the information on the dependencies necessary to run the project (it is the one `npm install` refers to when installing dependencies). Actual styling is developed inside `.scss`-files since it enables us higher flexibility and readability of the CSS code. Then the SCSS-files convert to CSS-files using `node-sass` package.

All `.html` pages of the project except the front page are stored in `/pages` folder. All the `.scss` files except the main `styles.scss` are stored in `/scss` folder.

### Students who worked on the project: 
Kjartan Elí Guðnason, Þorri Már Sigurþórsson and Dmitrii Fufachev

Original repo is from: https://github.com/vefforritun/vef1-2018-h1
