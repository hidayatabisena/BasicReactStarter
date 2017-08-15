# ReactBasicStarter

For frontend web development, let's take a look [React](https://facebook.github.io/react/) as our main library.

I've created this boilerplate React starter as basic as possible while still including [Babel](http://babeljs.io/) and [Webpack](http://webpack.github.io/).

### Getting Started
Open up your Terminal, checkout this repo, install dependencies with do this following:

Setup
---
 
```
npm install
```
 
 
 
Compile
---
 
```
npm run compile
```



### Usage
Open [http://localhost:3000/](http://localhost:3000/).

### Why Basic?
The primary purposes of this project is `basic` as its name.
Too many dependencies can cause confusion at the beginning. The process of selecting and adding what you need to a minimal project
can be a good way to learn.

Babel and Webpack are the tooling that completely essential in a React project.

**Webpack:** Webpack serves as both the web server and the JavaScript bundler.
**Babel:** We will use JSX in our components, and JSX is a succinct way to write out the layout of a React component. Babel transforms the ES6 JavaScript that we will be writing into ES5 JavaScript that current browsers can understand.

### More Details
* no CSS. Will add later on the next release, perhaps.
* no Flux. If you need it - try [Redux](https://github.com/reactjs/redux) or I'll add later too. 
* Webpack is run with the `express` and `webpack-dev-middleware`.
* The 'content base' is set to `www`. Any files in that directory will be served by express.
