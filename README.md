
# ExpressJS Backend Boilerplate
 This is a boilerplate code for creating a backend application using ExpressJS.
 It provides a basic structure and setup for building RESTful APIs.


## Table of Contents

- [Root Files](#root-Files)
- [Src Folder](#src)
  - [Routes](#routes)
  - [Models](#models)
  - [Middleware](#middleware)
  - [Utils](#utils)
  - [Templates](#templates)
  - [Config](#config)

## Root Files

- `app.js` - app.js- This file would basically be the entry point of the Express application and should be as minimal as possible
- `package.json` - file which contains all the project npm details, scripts and dependencies.
- `.gitignore` - The files you don’t want to push to git.

## Src

- `/src` - Src folder will further hold directories.

  ### Routes
    `src/routes` - This folder would contain all the routes that you have created using Express Router and what they do would be exported from a Controller file. Naming of files: `xxxxx.routes.js`

  ### Models
    `src/models` - This folder would contain all your schema files and the functions required for the schema would also lie over here. Naming of files: `xxxxx.js`

  ### Middleware
    `src/middleware` - This folder would contain all the middleware that you have created, whether it be authentication/some other function. Naming of files: `xxxxx.middleware.js`

  ### Utils
    `src/utils` (Optional) - The common functions that you would require multiple times throughout your code. Naming of files: Normal project file naming scheme.

  ### Templates
    `src/templates` (Optional) - If your code requires you to send certain emails/ HTML code to the client-side, store it in this files. Naming of files: Normal project file naming scheme.

  ### Config
    `src/config` (Optional) - Configuration files for third party APIs/services like passport/S3,etc. Naming of files: Normal project file naming scheme.
