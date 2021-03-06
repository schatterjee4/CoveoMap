# CoveoMap 
This is a branch of the [Coveo Search-ui-seed](https://github.com/coveo/search-ui-seed) a fast starter / seed project to extend the Coveo Javascript Framework

Read our [Blog](https://github.com/coveo/search-ui-seed) to better understand the full scope of the project.

Visit the [live map](https://coveo-map.herokuapp.com/) to have fun with it. (Initial load of the map might take a few seconds)

## Requirements
Node JS => 8.0

Google Map API key

Coveo Cloud Organization (with data containing lat/long fields)

## Setup

1. Fork / clone the repository.
2. `npm install` at the top of the repository.
3. Configuration of Coveo Cloud and Google API key
4. `npm run watch` at the top of the repository.
5. Open your browser and and paste in the url  

## Get Our Data
If you wish to use our data to try to experiment with the map, you can clone our [Python Pusher](https://github.com/coveo/samples/tree/master/push-api/python-pusher) configure the script with your Push source key and execute it to index the data into your Coveo Cloud organization. You can find all the individual JSON file in the ressource folder of this project.

## Structure

The code is written in [typescript](http://www.typescriptlang.org/) and compiled using [webpack](https://webpack.github.io/)

## Build task

* `npm run setup ` will copy the needed ressources (`index.html`, `templates`, etc.) in the `bin` folder.
* `npm run css` will build the sass files into a css file in the `bin` folder.
* `npm run build` will run the `setup`, `css` task, then compile the typescript code.

## Dev

`npm run watch` will start a [webpack dev server](https://webpack.js.org/concepts/). After it finishes, load [http://localhost:3000](http://localhost:3000) in a browser, and the `index.html` page should load.

Then, anytime you hit save in a typescript file, the server will reload your application.

## Useful Visual Studio Code Extensions

If you are using Visual Studio Code, you can install the following extensions:

### [TSLint](https://marketplace.visualstudio.com/items?itemName=eg2.tslint)

Shows inline linter problems in the code based on the `tslint.json` file. This will ensure that you are consistent with the formatting standards. 


