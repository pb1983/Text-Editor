# Text-Editor

## Table of Contents
- [Description](#description)
- [Installation](#installation)
- [Links](#links)    

## Description

A Progressive Web App (PWA) is an application that is designed to function as if it were running on it's own independant platform, however it is built using standard web-based technologies. By generating a manifest and a registered service worker, we are able to create a Text Editor application that functions using cached content, and can be installed and utilized outside of a web browser. IndexedDB saves the data that is provided by the user even after the application is closed or refreshed. 

## Installation

- Node.js - To download the latest version of npm, on the command line, run the following command: 
"npm install -g npm". Once installed, the routes can be accessed by typing "node index.js" in the terminal. 

- Express.js - Create a package.json first with the npm init command. Installation is done using the npm install command: $ npm install express

- Babel - Make sure all of the below Babel pluggins are installed:

    - npm install --save-dev @babel/core
    - npm install --save-dev @babel/plugin-transform-runtime
    - npm install --save-dev @babel/plugin-proposal-object-rest-spread
    - npm install --save-dev @babel/preset-env
    - npm install --save @babel/runtime

- Webpack - Run the following command in your terminal: npm install --save-dev webpack


## Links

[Repository](https://github.com/pb1983/Text-Editor)

[Heroku Link](https://drive.google.com/file/d/1G7_u7y81_6NCCbg7tRAGhstb6rtgjDP0/view)