# Perfect Pose Front End Layout

---
 
This project does not use any frameworks or libraries. The preprocessing steps are compilation from `.less` to `.css` files and compilation from __ES6__ to __ES5__ JavaScript with __Babel__.  
Build files are located in the `./dist/`  directory and can be used as is.  
The component can be viewed in the browser by running `npm run start` or you can manually select `index.html` file from the `./dist/` directory and view it as is. 

---

## Getting Started

### Prerequisites

You will need the following installed:

* [npm, nodejs v.10.xx](https://nodejs.org/en/)
* [npx](https://www.npmjs.com/package/npx)

### To install the project:

* In the project directory: `npm install `

---

## Main Scripts

In the project directory, you can run:

#### `npm run start`

Builds the landing page in the `./dist/` directory and serves in on the port `5000`<br>

Open __http://localhost:5000__ to view it in the browser.

#### `npm run serve`

Serves the landing page locally on __http://localhost:5000__

#### `npm run build`

* Copies necessary files to the `./dist/` directory.
* Compiles `.less` to `.css` files.
* Compiles `ES6 Javascript` files to `ES5 JavaScript` using [Babel](https://babeljs.io/). 
 
---

## Project Structure & Layout

* Project naming and styling principles adhere to [BEM methodology](https://en.bem.info/methodology/)
* CSS selector follow naming convention to create `blocks`, `elements` and `modifiers`.
* Each __block__ has it's own folder in `./src/common.blocks` that provides modularity for stylesheets and allows easy refactoring for `React.js` components if needed.

---

## Notes

* __Prefixes & Minification__: For production it would be better to minify all the scripts and stylesheets and add automatically browser prefixes. Here, for simplicity, basic `less` mixin arte used for prefixing.
<br>
<br>

__author__ [Ksenia  Koldaeva](https://kseniacodes.com)
