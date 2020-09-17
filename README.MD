# webpack

writing modern javascript that all browser can understand.
-features include minification, asset mangement.

# webpack-dev-server

webpack-dev-server is a convenient package for development. Once configured, we can launch a local server to serve our files. (localhost:8080)

## To Run

```
npm run build
```

- By the localhost:8080 you can run it.

## Entry point,Output, Loaders,Plugins

### Entry point :

- An entry point for webpack is the starting point from which all the dependencies of a frontend project are collected.
- Default entry point is src/index.js in our project entry point is src/js/app.js

### Output :

- The output is where the resulting JavaScript and static files are collected during the build process.
- Default output folder dist/

### Loaders :

- Loaders are third-party extensions that help webpack deal with various file extensions. For example there are loaders for CSS, for images, or for txt files.

### Plugins :

- Plugins are third-party extensions that can alter how webpack works.
- For example there are plugins for extracting HTML, CSS, or for setting up environment variables.
