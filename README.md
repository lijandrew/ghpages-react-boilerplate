# ghpages-react-boilerplate

&rarr; A boilerplate for building React web applications for GitHub Pages

## Table of Contents

[About](#about)  
[Installation](#installation)  
[Usage](#usage)

## About

GitHub Pages allows users to host static webpages for the low price of free. While this is often used for project documentation and blogging, it is also a great way to host web applications that feature entirely clientside functionality, such as in-browser tools for file converting/manipulating, image editing (think <a href="https://www.photopea.com/">Photopea</a>), and content consumption (<a href="https://github.com/lijandrew/ame">shameless plug</a>).

This boilerplate provides a fully configured webpack project with React, Babel, and SCSS, along with separate development and production webpack configurations and a basic `src/` folder structure template. It also comes with some essential npm scripts so you can start developing right away.

By building to `docs/` instead of a traditional build folder name like `dist/`, we take advantage of GitHub Page's option to host from `docs/` instead of `/`, keeping our code separate from the files we serve.

## Installation

First, clone the repository:

    git clone https://github.com/lijandrew/ghpages-react-boilerplate.git


Then, install dependencies:

    npm i

## Usage

`npm start` - Starts the live-reload development server.  
`npm run build-dev` - Builds the project to `docs/` in development mode.  
`npm run build` - Builds the project to `docs/` in production mode.
