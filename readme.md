# Simple WebPack 4 Template

This is a template for getting a project started fast and clean with Webpack 4. It will minimize and compile your sass, html and js.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

You must have node v8.10 or greater.
And node package manager v6.1 or greater.

### Installing

The get the development environment running, simply download or clone the respository into the directory you would like start the project in.

Then simply run the npm installer.

```
cd my-nifty-project
npm install
```

The dependencies from package.json will automatically be installed.
And the webpack.config.js and .babelrc will take care of the npm build configurations.

### Testing the installation

Simply run a dev test and see if you get a working project.

Hello World on the web-page.

and

"Hello (console) world" in the console.

```
npm run start
```

### Development

Modify the files in ./src/ and add files there, they will automatically compile to ./dist/

```
npm run dev
```

The ./dist files will not be minified in order to facilitate debugging.

## Deployment

Modify the files in ./src/ and add files there, they will automatically compile to ./dist/

The ./dist files will be minified and transpiled for efficiency and browser compatibility.

```
npm run build
```

## Built With

* [Webpack4](http://www.dropwizard.io/1.0.2/docs/) - The web framework used

## Authors

* **Will Allen** - *Initial work* - [willallen83](https://github.com/willallen83)

## License

This project is licensed under the MIT License

## Acknowledgments

* Everyone who worked on and developed all of the dependencies of this project!
