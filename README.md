# Project Title

A brief description of what this project does and who it's for

# Project Name

Project structure for ExpressJS

## Table of Contents

- [Root Files](#root-Files)
- [Src](#src)
  - [Routes](#routes)
  - [Models](#models)
  - [Middleware](#middleware)

## Root Files

- `app.js` - app.js- This file would basically be the entry point of the Express application and should be as minimal as possible
- `package.json` - file which contains all the project npm details, scripts and dependencies.
- `.gitignore` - The files you don’t want to push to git.

## Src

- `/src` - Src folder will further hold directories.

  ### Routes

  - `/Routes` - This folder would contain all the routes that you have created using Express Router and what they do would be exported from a Controller file. Naming of files: `xxxxx.routes.js`

  ### Models

  - `/Models` - This folder would contain all your schema files and the functions required for the schema would also lie over here. Naming of files: `xxxxx.js`

  ### Middleware

- `/Middleware` - This folder would contain all the middleware that you have created, whether it be authentication/some other function. Naming of files: `xxxxx.middleware.js`

  ### Utils

  - `/Utils` (Optional) - The common functions that you would require multiple times throughout your code. Naming of files: Normal project file naming scheme.

  ### Templates

  - `/Templates` (Optional) - If your code requires you to send certain emails/ HTML code to the client-side, store it in this files. Naming of files: Normal project file naming scheme.

  ### Config

  - `/Config` (Optional) - Configuration files for third party APIs/services like passport/S3,etc. Naming of files: Normal project file naming scheme.
