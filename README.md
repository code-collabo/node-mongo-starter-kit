# node-mongo-esm-kit

The ***ES Module template*** a.k.a esm, for the [node-mongo project](https://code-collabo.gitbook.io/docs/contributor-guide/node-mongo-project/project-overview)'s starter kit. Other templates to choose from are the [commonjs](https://github.com/code-collabo/node-mongo-cjs-kit) and typescript (coming soon) templates, depending on what you prefer or use.

`import express from 'express';`



![contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat) ![License: ISC](https://img.shields.io/badge/License-ISC-blue.svg) ![GitHub issues](https://img.shields.io/github/issues/code-collabo/node-mongo-cli?color=red) ![GitHub pull requests](https://img.shields.io/github/issues-pr/code-collabo/node-mongo-esm-kit?color=goldenrod) 

<!--
![GitHub all releases](https://img.shields.io/github/downloads/code-collabo/node-mongo-esm-kit/total?color=green)
-->

The node-mongo starter kit helps to make mongoDB development in nodejs easier. Using the node-mongo starter kit has been made easier with the [node-mongo-cli](https://github.com/code-collabo/node-mongo-cli). While you can also choose to download/clone this starter kit directly from github, the cli let's you not only install your preferred starter kit template, but also allows you to add new model & controller files with content using simple commands. Opt for the [cli](https://github.com/code-collabo/node-mongo-cli) for better experience.

## How to use the starter kit
Development environment has been set up already i.e. connection to server & db, eslint and babel transpiler. For use locally, you need to have `mongoDB` [installed](https://docs.mongodb.com/guides/server/install/) with database and collection created and mongoDB running. If you choose to use `mongoDB atlas` then you don't need to have mongoDB installed - just turn on wifi/data connection, [create database and connect to your cluster](https://docs.atlas.mongodb.com/getting-started/).

**Installation:**
* Install preferred starter kit template through cli or download from github.
* Cd into the folder you installed it and run `npm install` to install dependencies.
* Run `npm start` or `npm start -s` to start the server and mongoDB connection.
* There are two options - `installed MongoDB` option and `MongoDB ATLAS` option. To setup successful connection for whichever option you wish to use for your project, follow the guide written in yellow, which comes up after `Server running at http://localhost:3000` and `Error in DB connection` message in the console.

**Customizing dev environment:**

Replace `insert-your-project-name` with your own project name in `srcServer > startMessage.js`.

## Contributing to the starter kit
See [contributor guide](https://code-collabo.gitbook.io/docs/contributor-guide/contributor-guide) and [node-mongo project](https://code-collabo.gitbook.io/docs/contributor-guide/node-mongo-project) portion of the documentation guide for how to contribute to the starter kit templates.

## Technologies

[<img alt="javascript" height="25px" src="https://www.freepnglogos.com/uploads/javascript/javascript-online-logo-for-website-0.png" />](https://github.com/code-collabo/node-mongo-cli)
[<img alt="node js" height="25px" src="https://nodejs.org/static/images/logos/nodejs-new-pantone-black.svg" />](https://github.com/code-collabo/node-mongo-cli)
[<img alt="mongoDB" height="25px" src="https://webassets.mongodb.com/_com_assets/cms/MongoDB_Logo_FullColorBlack_RGB-4td3yuxzjs.png" />](https://github.com/code-collabo/node-mongo-cli)

