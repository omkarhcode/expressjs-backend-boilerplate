
# ExpressJS Backend Boilerplate
 This is a boilerplate code for creating a backend application using ExpressJS.
 It provides a basic structure and setup for building RESTful APIs.


## Table of Contents

- [Root Files](#root-Files)
- [Src Folder](#src)
  - [Config](#config)
  - [Controllers](#controller)
  - [Middleware](#middleware)
  - [Routes](#routes)
  - [Models](#models)
  - [Utils](#utils)

## Root Files

- `app.js` - app.js- This file would basically be the entry point of the Express application and should be as minimal as possible
- `package.json` - file which contains all the project npm details, scripts and dependencies.
- `.gitignore` - The files you don’t want to push to git.

## Src

- `/src` - Src folder will further hold directories.
  
  ### Config
    `src/config` - Configuration files for third party APIs/services like passport/S3,etc. Naming of files: Normal project file naming scheme.

  ### Controllers
    `src/controllers` - Controllers will be responsible to handle all the incoming requests to your application which will either render a page in response, may send a JSON payload or will handle other critical API related actions like POST, PUT, DELETE etc.
  
  ### Middleware
    `src/middleware` - This folder would contain all the middleware that you have created, whether it be authentication/some other function. Naming of files: `xxxxx.middleware.js`
    These helpers could range from critical middleware like Body Parser, Global Error Handlers, Authentication Middleware, enabling CORS, Attaching Custom Headers or setting a View Engine in ExpressJS.

  ### Routes
    `src/routes` - This folder would contain all the routes that you have created using Express Router and what they do would be exported from a Controller file. Naming of files: `xxxxx.routes.js`

  ### Models
    `src/models` - This folder would contain all your schema files and the functions required for the schema would also lie over here. Naming of files: `xxxxx.js`

  ### Utils
    `src/utils` - The utils directory will have all the utilities and helpers needed for the application. It will also act as a place to put shared logic, if any. For example, a simple helper to calculate the offset for a paginated SQL query can be put in a helper.util.js file in this folder.

