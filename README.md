# CSS - Code review 1 - Leica website homepage clone

## Description

This project is a clone of the Leica homepage.  The goal in this project is to practice using CSS grid and Flexbox together to create a responsive replica of their homepage.

## development

1. Find page to clone.  I went with the Leica webpage because they are an incredible camera manufacturer and photography is one of my passions in life, so it just made sense.  Leica is a company that makes incredibly high quality cameras so it should be fun to mess around with their page, and they seem to have made good use of CSS Grid, Flexbox and media queries.

2.  Draw layout for different breakpoints.  The Leica webpage seems to have four media queries.  The first for 1000px + displays, the second for 760 - 999px displays, the third for 460 - 759px displays, and the fourth for displays smaller than 460px.  Scans of my drawings are available to be viewed in the drawings folder.

3. Begin Creating README.md.  Here we are.   

4.  Starting with the outside and working my way into nested grids and flex boxes, create a grid for the page.  Make three columns, and have the browser generate new rows as they are needed, with a minimum of 50px for the navbars, and a maximum of auto to fit the longer sections such as the footer.

5.  Place various sections of content on grid using grid-column-start and adding a span to reflect where different sections should go.

6.  Start adding media queries.  Although I now know it's best practice to start with the mobile version of my webpage and build bigger from there, I am going to start with the desktop version in order to stick to how I have the most practice and make sure I get something put together I am proud of.  As I gain more experience with UI layouts I will start switching to follow best practices.

7.  Focus on styling details and adding pseudo-classes to my page to create a more friendly user experience.  

## Setup and Installation

### To clone project to your machine:

* Clone the path from Github
* With command line, change directories into Desktop/
* With command line, enter "git clone + path"
* Change directories into new folder on Desktop
* With command line, enter "npm install" to add npm to folder

### To view source code on your machine:

* From in the project root directory with the command line, open your preferred text editor (eg "atom .")

### To view in live development server

* Follow instructions below under "Development Server"
* Add --serve to automatically open in browser  



This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 1.6.5.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `-prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).
