# Just Another Text Editor - JATE

## Description

The purpose of this project is to build  a web-based text editor. This text editor is a single-page application that meets the progressive web application criteria. It also has some data persistence features that serve as redundancy in case one of the options is not supported by the browser. It uses methods to get and store data to an indexedDB database. Further, this application is deployed to Heroku and functions on and off-line

- This application is an alternative tool that can be used by developers to create notes or code snippets
- Able to retrieve, update, and store information, this application extends off-line operability to users in case of internet disruption.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Credits](#credits)
- [License](#license)

## Installation

### Client
* The following dependencies should be installed:
    * babel core/preset-env/runtime/loader
    * css-loader
    * html-webpack-plugin
    * style-loader
    * webpack/webpack-cli/dev-server/pwa-manifest/workbox-webpack-plugin

### Server
* The following dependencies should be installed:
    * express
    * nodemon

### Root-level
* The following ***scripts*** should be installed:
    * `start:dev`: concurrently cd client && npm run build cd server && npm run server
    * `start`: npm run build && cd server && node server.js
    * `server`: cd server server.js --ignore client
    * `build`: cd client && npm run build
    * `install`: cd server && npm i && cd../client && npm i

* The following ***dependencies*** should be installed:
    * express
    * if-env
    * concurrently
    * nodemon

## Usage

Link to Heroku: https://bell-text-editor-bd3409a70b40.herokuapp.com

![alt text](/assets/images/text_editor_screenshot.png)

1. Right click on the server.js, open in integrated terminal
2. enter npm i to install node_modules
3. npm run start:dev
4. Interact with the text editor in the browser

## Credits

https://www.markdownguide.org/cheat-sheet/

https://gist.github.com/lukas-h/2a5d00690736b4c3a7ba

https://coding-boot-camp.github.io/full-stack/github/professional-readme-guide

## MIT License

Copyright (c) 2023 G6-2Flyy

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.




