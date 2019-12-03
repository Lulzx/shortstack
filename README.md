### Javascript ›
[Rollup](https://rollupjs.org) to **bundle**, **treeshake**, **import from NPM, local or URLs**, and **import CSS**. 

### CSS ›
[PostCSS](https://postcss.org) to **import from NPM, local or URLs**, [postcss-preset-env](https://preset-env.cssdb.org/) for **CSS features from the spec**, and handy [easings](https://easings.net). 

### Dev Server ›
[Browsersync](https://www.browsersync.io) with all the goodies: **live reload**, **hot swap CSS**, **scroll syncing**, **remote debugging**, [etc](https://www.browsersync.io).

<br><br>

## Getting Started
1. `mkdir new-project-name && cd $_`
1. `git clone --depth=1 https://github.com/argyleink/shortstack.git . && rm -rf ./.git`
1. `npm i`
1. `npm start`

## Development
Running `npm start` runs Browsersync, which watches changes to your files in `./app` and refreshes connected browsers.

## Production
Running `npm run build` compiles and minifies your code in `app` and outputs the optimised result to a folder called `dist` that's ready for static hosting.

<br><br>

#### Note:
This is meant to be built upon but is currently great for small projects and prototypes. 
