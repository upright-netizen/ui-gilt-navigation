# Gilt Navigation Component

A web component for the Gilt navigation created using Polymer. This is just a stub used for prototyping and is not fully functional.

## Setup

1. `npm install`
2. `cd gilt-navigation && bower install`

## Development

Start the local webserver by typing `grunt` from the root of the project.

Make changes to the web-component in `gilt-navigation/gilt-navigation.html` and check it out in the browser at [http://0.0.0.0:5555/gilt-navigation](http://0.0.0.0:5555/gilt-navigation)

## Project Structure

The root directory of this project is the workspace. The web component itself lives in `gilt-navigation`.

`Gruntfile.js` - the standard gruntfile. Belongs in the root so that everything can be served in the browser via the grunt connect module.

`package.json` - your standard package.json (mainly for grunt)

`README.md` - You're reading it!

`gilt-navigation` - The contents of the web component

- `.bowerrc` - Configured with the following settings: `{"directory":"../"}` so that bower modules are installed in the root workspace (where this README file is located). This allows the component to be worked on as if it were a web-component installed in a project via bower. All imports are referenced via `../` where all components live equally in the `bower_modules` folder (or wherever bower dependencies are installed). See this [DivShot](http://www.divshot.com/blog/web-components/polymer-and-bower-getting-it-right/) article for more info.
- `bower.json` - The Bower file for the web component
- `gilt-navigation.html` - The Polymer component.
- `index.html` - The preview file for the component for use during development. From the root of the project, type `grunt` and visit [http://0.0.0.0:5555/gilt-navigation](http://0.0.0.0:5555/gilt-navigation) to see it.
- `README.md` - The readme for the web component itself. Should outline any APIs and explain the usage.
